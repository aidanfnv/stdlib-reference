---
layout: stdlib-reference
---

# struct Ptr\<T, addrSpace:uint64\_t\>

## Description

Represents a pointer type.

## Generic Parameters

####  <a id="typeparam-T"></a>T
The type of the value pointed to.

####  <a id="decl-addrSpace"></a>addrSpace  : uint64\_t = 4294967297 ULL

## Methods

* operator\[\]
* operator$init

## Remarks

<span class='code'><a href="index.md#typeparam-T" class="code_type">T</a>*val</span> is equivalent to <span class='code'><a href="index.md" class="code_type">Ptr</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;val</span>.



```{toctree}
:titlesonly:
:hidden:

init <../types/ptr-0/init>
subscript <../types/ptr-0/subscript>
```

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
