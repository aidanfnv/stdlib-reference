---
layout: stdlib-reference
---

# attribute [outputcontrolpoints]

## Description

Used on an hull shader entrypoint to declare the number of control points the hull shader will produce per thread.

## Signature

<pre>
[<a href="outputcontrolpoints.md">outputcontrolpoints</a>(<a href="outputcontrolpoints.md#decl-count" class="code_param">count</a> : <span class="code_keyword">int</span>)]
</pre>

## Parameters

####  <a id="decl-count"></a>count  : int
The number of control points the hull shader will produce per thread.


## Remarks

The attribute indicates be the number of times the hull shader function will be executed.



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
