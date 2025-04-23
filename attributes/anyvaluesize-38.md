---
layout: stdlib-reference
---

# attribute [anyValueSize]

> #### Experimental Feature
> The feature described in this page is marked as experimental, and may be subject to change in future releases.
> Users are advised that any code that depend on this feature may not be compilable by future versions of the compiler.

## Description

Mark an interface type to allow dynmaic dispatch, and declare the maximum size in bytes that an implementation type
of the interface can have.


## Signature

<pre>
[<a href="anyvaluesize-38.md">anyValueSize</a>(<a href="anyvaluesize-38.md#decl-size" class="code_param">size</a> : <span class="code_keyword">int</span>)]
</pre>

## Parameters

####  <a id="decl-size"></a>size  : int


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
