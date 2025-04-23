---
layout: stdlib-reference
---

# isDifferentialNull

## Description





## Signature 

<pre>
<span class="code_keyword">bool</span> <a href="isdifferentialnull-2e.md">isDifferentialNull</a>(<a href="../interfaces/idifferentiable-01/index.md" class="code_type">IDifferentiable</a> <a href="isdifferentialnull-2e.md#decl-obj" class="code_param">obj</a>);

</pre>

## Parameters

####  <a id="decl-obj"></a>obj  : [IDifferentiable](../interfaces/idifferentiable-01/index.md)


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
