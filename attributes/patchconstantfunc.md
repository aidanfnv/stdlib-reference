---
layout: stdlib-reference
---

# attribute [patchconstantfunc]

## Description

Used on a hull shader entrypoint to specify the associated function that computes the patch constant data.

## Signature

<pre>
[<a href="patchconstantfunc.md">patchconstantfunc</a>(<a href="patchconstantfunc.md#decl-name" class="code_param">name</a>)]
</pre>

## Parameters

####  <a id="decl-name"></a>name
The name of the function (in string literal) that computes the patch constant data.



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
