---
layout: stdlib-reference
---

# attribute [DllImport]

> #### Experimental Feature
> The feature described in this page is marked as experimental, and may be subject to change in future releases.
> Users are advised that any code that depend on this feature may not be compilable by future versions of the compiler.

## Description

Mark a function as imported from a DLL. Valid only on CPU host targets.


## Signature

<pre>
[<a href="dllimport-03.md">DllImport</a>(<a href="dllimport-03.md#decl-modulePath" class="code_param">modulePath</a> : <a href="../types/string-0/index.md" class="code_type">String</a>)]
</pre>

## Parameters

####  <a id="decl-modulePath"></a>modulePath  : [String](../types/string-0/index.md)


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
