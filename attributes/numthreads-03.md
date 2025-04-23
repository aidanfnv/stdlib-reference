---
layout: stdlib-reference
---

# attribute [NumThreads]

## Description

Specifies the size of the thread group a compute shader.

## Signature

<pre>
[<a href="numthreads-03.md">NumThreads</a>(<a href="numthreads-03.md#decl-x" class="code_param">x</a> : <span class="code_keyword">int</span>, <a href="numthreads-03.md#decl-y" class="code_param">y</a> : <span class="code_keyword">int</span>, <a href="numthreads-03.md#decl-z" class="code_param">z</a> : <span class="code_keyword">int</span>)]
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
      if (link.getAttribute('href') && link.getAttribute('href').endsWith('.md')) {
        link.href = link.href.replace(/\.md($|#|\?)/, '.html$1');
      }
    });
  });
}
</script>
