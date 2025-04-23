---
layout: stdlib-reference
---

# attribute [deprecated]

## Description

Mark a declaration as deprecated.

## Signature

<pre>
[<a href="deprecated.md">deprecated</a>(<a href="deprecated.md#decl-message" class="code_param">message</a> : <a href="../types/string-0/index.md" class="code_type">String</a>)]
</pre>

## Parameters

####  <a id="decl-message"></a>message  : [String](../types/string-0/index.md)
The diagnostic message to show when the declaration is used.



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
