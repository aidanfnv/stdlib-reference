---
layout: stdlib-reference
---

# attribute [AutoPyBindCUDA]

> #### Experimental Feature
> The feature described in this page is marked as experimental, and may be subject to change in future releases.
> Users are advised that any code that depend on this feature may not be compilable by future versions of the compiler.

## Description

Mark a function for automatic pytorch binding.


## Signature

<pre>
[<a href="autopybindcuda-046abcd.md">AutoPyBindCUDA</a>]
</pre>


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
