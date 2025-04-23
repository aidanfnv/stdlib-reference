---
layout: stdlib-reference
---

# attribute [numthreads]

## Description

Specifies the size of the thread group a compute shader.

## Signature

<pre>
[<a href="numthreads.md">numthreads</a>(<a href="numthreads.md#decl-x" class="code_param">x</a> : <span class="code_keyword">int</span>, <a href="numthreads.md#decl-y" class="code_param">y</a> : <span class="code_keyword">int</span>, <a href="numthreads.md#decl-z" class="code_param">z</a> : <span class="code_keyword">int</span>)]
</pre>

## Parameters

####  <a id="decl-x"></a>x  : int
The number of threads in the x dimension of a thread group.

####  <a id="decl-y"></a>y  : int = 1
The number of threads in the y dimension of a thread group.

####  <a id="decl-z"></a>z  : int = 1
The number of threads in the z dimension of a thread group.



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
