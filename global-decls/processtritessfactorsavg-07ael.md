---
layout: stdlib-reference
---

# ProcessTriTessFactorsAvg

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="processtritessfactorsavg-07ael.md">ProcessTriTessFactorsAvg</a>(
    <span class="code_keyword">in</span> <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 3&gt; <a href="processtritessfactorsavg-07ael.md#decl-RawEdgeFactors" class="code_param">RawEdgeFactors</a>,
    <span class="code_keyword">in</span> <span class="code_keyword">float</span> <a href="processtritessfactorsavg-07ael.md#decl-InsideScale" class="code_param">InsideScale</a>,
    <span class="code_keyword">out</span> <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 3&gt; <a href="processtritessfactorsavg-07ael.md#decl-RoundedEdgeTessFactors" class="code_param">RoundedEdgeTessFactors</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">float</span> <a href="processtritessfactorsavg-07ael.md#decl-RoundedInsideTessFactor" class="code_param">RoundedInsideTessFactor</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">float</span> <a href="processtritessfactorsavg-07ael.md#decl-UnroundedInsideTessFactor" class="code_param">UnroundedInsideTessFactor</a>);

</pre>

## Parameters

####  <a id="decl-RawEdgeFactors"></a>RawEdgeFactors  : [vector](../types/vector/index.md)\<float, 3\>
####  <a id="decl-InsideScale"></a>InsideScale  : float
####  <a id="decl-RoundedEdgeTessFactors"></a>RoundedEdgeTessFactors  : [vector](../types/vector/index.md)\<float, 3\>
####  <a id="decl-RoundedInsideTessFactor"></a>RoundedInsideTessFactor  : float
####  <a id="decl-UnroundedInsideTessFactor"></a>UnroundedInsideTessFactor  : float

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
      if (link.getAttribute('href') && link.getAttribute('href').endsWith('.md')) {
        link.href = link.href.replace(/\.md($|#|\?)/, '.html$1');
      }
    });
  });
}
</script>
