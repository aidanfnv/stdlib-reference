---
layout: stdlib-reference
---

# attribute [maxtessfactor]

## Description

Used on an hull shader entrypoint to declare the upperbound of the tessellation factor that the hull shader can return.

## Signature

<pre>
[<a href="maxtessfactor.md">maxtessfactor</a>(<a href="maxtessfactor.md#decl-factor" class="code_param">factor</a> : <span class="code_keyword">float</span>)]
</pre>

## Parameters

####  <a id="decl-factor"></a>factor  : float
The maximum tessellation factor the hull shader can return.



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
