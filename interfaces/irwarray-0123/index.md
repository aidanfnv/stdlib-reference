---
layout: stdlib-reference
---

# interface IRWArray\<T\>

*Inherits from:* [IArray](../iarray-01/index.md)\<[T](../iarray-01/index.md#typeparam-T)\>

## Description

Represents types that provide a subscript operator so that they can be used like a mutable array.

## Generic Parameters

####  <a id="typeparam-T"></a>T
The element type returned by the subscript operator.


## Methods

* [subscript](subscript.md)

## Remarks

This interface is implemented by <span class='code'><a href="../../types/array-0/index.md" class="code_type">Array</a></span>, <span class='code'><a href="../../types/vector/index.md" class="code_type">vector</a></span>, <span class='code'><a href="../../types/matrix/index.md" class="code_type">matrix</a></span>, <span class='code'><a href="../../types/structuredbuffer-0a/index.md" class="code_type">StructuredBuffer</a></span> and <span class='code'><a href="../../types/rwstructuredbuffer-012c/index.md" class="code_type">RWStructuredBuffer</a></span> types.

## Example

The follow example shows how to define a generic function uses the <span class='code'><a href="index.md" class="code_type">IRWArray</a></span> interface to mutate an array-like value.
```csharp
void writeToArray<U, T : IRWArray<U>>(inout T array, int index, U value) { array[index] = value; }
void writeToBuffer<U, T : IRWArray<U>>(T array, int index, U value) { array[index] = value; }
U readFromArray<U, T:IArray<U>>(T array, int index) { return array[index]; }

//TEST_INPUT:ubuffer(data=[0 0 0 0], stride=4):out,name=outputBuffer
RWStructuredBuffer<float> outputBuffer;

[numthreads(1, 1, 1)]
void computeMain(int3 dispatchThreadID: SV_DispatchThreadID)
{
    float arr[3] = { 1.0, 2.0, 3.0 };
    float4 v = float4(1.0, 2.0, 3.0, 4.0);
    float2x2 m = float2x2(1.0, 2.0, 3.0, 4.0);

    // treat `outputBuffer` as a mutable array of `float`.
    writeToBuffer(outputBuffer, 0, 1.0f);

    // treat `arr` as a mutable array of `float`.
    writeToArray(arr, 0, 4.0f);
    outputBuffer[1] = readFromArray(arr, 0); // 4.0

    // treat `v` as a mutable array of `float`.
    writeToArray(v, 3, 3.0f);
    outputBuffer[2] = readFromArray(v, 3);  // 3.0

    // treat `m` as a mutable array of `float2`.
    writeToArray(m, 1, float2(10.0f, 20.0f));
    outputBuffer[3] = readFromArray(m, 1).x + readFromArray(m, 1).y; // 30.0

    writeToBuffer(outputBuffer, 0, readFromArray(outputBuffer, 0));
}
```



```{toctree}
:titlesonly:
:hidden:

subscript <../interfaces/irwarray-0123/subscript>
```

<script>
// Fix .md links to .html when on ReadTheDocs
if (window.location.hostname.includes('readthedocs') || 
    window.location.hostname.includes('rtfd.io')) {
  document.addEventListener('DOMContentLoaded', function() {
    const links = document.querySelectorAll('a');
    links.forEach(link => {
      const href = link.getAttribute('href');
      if (href && href.includes('.md')) {
        // This regex will handle .md links with or without fragment identifiers or query parameters
        link.href = link.href.replace(/(.+)\.md(#[^?]*)?(\?.*)?$/, '$1.html$2$3');
      }
    });
  });
}
</script>
