---
layout: stdlib-reference
---

# struct DifferentialPtrPair\<T\>

*Conforms to:* [IDifferentiablePtrType](../../interfaces/idifferentiableptrtype-01fi/index.md)

> #### Experimental Feature
> The feature described in this page is marked as experimental, and may be subject to change in future releases.
> Users are advised that any code that depend on this feature may not be compilable by future versions of the compiler.

## Description

<span class='code'><a href="index.md" class="code_type">DifferentialPtrPair</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;</span> is a built-in type that carries both the original and differential of a
pointer-like object.
<span class='code'><a href="index.md#typeparam-T" class="code_type">T</a></span> must conform to <span class='code'><a href="../../interfaces/idifferentiableptrtype-01fi/index.md" class="code_type">IDifferentiablePtrType</a></span>

It is defined as follows:
```csharp
struct DifferentialPtrPair<T : IDifferentiablePtrType> : IDifferentiablePtrType
{
    typealias Differential = DifferentialPtrPair<T.Differential>;
    property T p {get;}
    property T.Differential d {get;}
}
```

## Generic Parameters

####  <a id="typeparam-T"></a>T: [IDifferentiablePtrType](../../interfaces/idifferentiableptrtype-01fi/index.md)

## Properties

####  <a id="decl-d"></a>[d](d.md)
####  <a id="decl-p"></a>[p](p.md)
####  <a id="decl-v"></a>[v](v.md)

## Methods

* [init](init.md)

## Remarks


Differential ptr pairs can be created via constructor.
```csharp
struct DPtrFloat : IDifferentialPtrType 
{ 
    typealias Differential = DPtrFloat;
    float* ptr;
};

DifferentialPtrPair<DPtrFloat> dpa = 
           DifferentialPtrPair<float>({&outputBuffer[0]}, {&outputBuffer[1]});
```
Note that derivative ptr pairs are used to pass derivatives into and out of auto-diff functions.
See documentation on <span class='code'>fwd_diff</span> and <span class='code'>bwd_diff</span> operators for more information.




```{toctree}
:titlesonly:
:hidden:

Differential <../types/differentialptrpair-0cf/differential-0>
DifferentialElementType <../types/differentialptrpair-0cf/differentialelementtype-0cj>
d <../types/differentialptrpair-0cf/d>
init <../types/differentialptrpair-0cf/init>
p <../types/differentialptrpair-0cf/p>
v <../types/differentialptrpair-0cf/v>
```

<script>
// Fix .md links to .html when on ReadTheDocs
if (window.location.hostname.includes('readthedocs') || 
    window.location.hostname.includes('rtfd.io')) {
  document.addEventListener('DOMContentLoaded', function() {
    const links = document.querySelectorAll('a');
    links.forEach(link => {
      if (link.getAttribute('href') && link.getAttribute('href').endsWith('.md')) {
        link.href = link.href.replace(/\.md($|#|\?)/, '.html$1');
      }
    });
  });
}
</script>
