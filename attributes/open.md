---
layout: stdlib-reference
---

# attribute [open]

> #### Experimental Feature
> The feature described in this page is marked as experimental, and may be subject to change in future releases.
> Users are advised that any code that depend on this feature may not be compilable by future versions of the compiler.

## Description

Mark a type as open, allowing it from being inherited from or implemented by types defined in other modules.
This is the default behavior.

## Signature

<pre>
[<a href="open.md">open</a>]
</pre>

## See also

<span class='code'>[<a href="sealed.md">sealed</a>]</span>.



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
