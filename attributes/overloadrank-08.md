---
layout: stdlib-reference
---

# attribute [OverloadRank]

> #### Internal Feature
> The feature described in this page is marked as an internal implementation detail, and is not intended for use by end-users.
> Users are advised to avoid using this declaration directly, as it may be removed or changed in future releases.

## Description

Specify the overload rank of a function for overload resolution.


## Signature

<pre>
[<a href="overloadrank-08.md">OverloadRank</a>]
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
