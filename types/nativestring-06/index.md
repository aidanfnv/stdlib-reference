---
layout: stdlib-reference
---

# struct NativeString

## Description



## Properties

####  <a id="decl-length"></a>[length](length.md)

## Methods

* [getLength](getlength-3.md)
* [getBuffer](getbuffer-3.md)
* [init](init.md)


```{toctree}
:titlesonly:
:hidden:

getBuffer <../types/nativestring-06/getbuffer-3>
getLength <../types/nativestring-06/getlength-3>
init <../types/nativestring-06/init>
length <../types/nativestring-06/length>
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
