---
layout: stdlib-reference
---

# struct String

## Description

Represents a string.
This type can only be used on the CPU target.


## Properties

####  <a id="decl-length"></a>[length](length.md)
Returns the length of the string.


## Methods

* [init](init.md)
* [getLength](getlength-3.md)


```{toctree}
:titlesonly:
:hidden:

getLength <../types/string-0/getlength-3>
init <../types/string-0/init>
length <../types/string-0/length>
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
