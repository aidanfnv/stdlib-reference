---
layout: stdlib-reference
---

# ProcessIsolineTessFactors

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="processisolinetessfactors-07ei.md">ProcessIsolineTessFactors</a>(
    <span class="code_keyword">in</span> <span class="code_keyword">float</span> <a href="processisolinetessfactors-07ei.md#decl-RawDetailFactor" class="code_param">RawDetailFactor</a>,
    <span class="code_keyword">in</span> <span class="code_keyword">float</span> <a href="processisolinetessfactors-07ei.md#decl-RawDensityFactor" class="code_param">RawDensityFactor</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">float</span> <a href="processisolinetessfactors-07ei.md#decl-RoundedDetailFactor" class="code_param">RoundedDetailFactor</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">float</span> <a href="processisolinetessfactors-07ei.md#decl-RoundedDensityFactor" class="code_param">RoundedDensityFactor</a>);

</pre>

## Parameters

####  <a id="decl-RawDetailFactor"></a>RawDetailFactor  : float
####  <a id="decl-RawDensityFactor"></a>RawDensityFactor  : float
####  <a id="decl-RoundedDetailFactor"></a>RoundedDetailFactor  : float
####  <a id="decl-RoundedDensityFactor"></a>RoundedDensityFactor  : float

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.




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
