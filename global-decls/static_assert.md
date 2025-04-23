---
layout: stdlib-reference
---

# static\_assert

## Description



@experimetal
Perform a compile-time condition check and emit a compile-time error if the condition is false.

## Signature 

<pre>
<span class="code_keyword">void</span> <a href="static_assert.md">static_assert</a>(
    <span class="code_keyword">bool</span> <a href="static_assert.md#decl-condition" class="code_param">condition</a>,
    <a href="../types/nativestring-06/index.md" class="code_type">NativeString</a> <a href="static_assert.md#decl-errorMessage" class="code_param">errorMessage</a>);

</pre>

## Parameters

####  <a id="decl-condition"></a>condition  : bool
The compile-time condition to check.

####  <a id="decl-errorMessage"></a>errorMessage  : [NativeString](../types/nativestring-06/index.md)
The error message to emit if the condition is false.



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
