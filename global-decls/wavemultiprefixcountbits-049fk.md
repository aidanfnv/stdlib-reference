---
layout: stdlib-reference
---

# WaveMultiPrefixCountBits

## Description





## Signature 

<pre>
<span class="code_keyword">uint</span> <a href="wavemultiprefixcountbits-049fk.md">WaveMultiPrefixCountBits</a>(
    <span class="code_keyword">bool</span> <a href="wavemultiprefixcountbits-049fk.md#decl-value" class="code_param">value</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 4&gt; <a href="wavemultiprefixcountbits-049fk.md#decl-mask" class="code_param">mask</a>);

</pre>

## Parameters

####  <a id="decl-value"></a>value  : bool
####  <a id="decl-mask"></a>mask  : [vector](../types/vector/index.md)\<uint, 4\>

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### cuda
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
