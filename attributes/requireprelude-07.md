---
layout: stdlib-reference
---

# attribute [RequirePrelude]

## Description

Mark a type to require a target specific prelude.
The prelude will be included in the generated code for the specified target if the resulting code uses
the marked type.


## Signature

<pre>
[<a href="requireprelude-07.md">RequirePrelude</a>(<a href="requireprelude-07.md#decl-target" class="code_param">target</a>, <a href="requireprelude-07.md#decl-prelude" class="code_param">prelude</a> : <a href="../types/string-0/index.md" class="code_type">String</a>)]
</pre>

## Parameters

####  <a id="decl-target"></a>target
####  <a id="decl-prelude"></a>prelude  : [String](../types/string-0/index.md)


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
