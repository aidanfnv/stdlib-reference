---
layout: stdlib-reference
---

# ProcessQuadTessFactorsMin

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="processquadtessfactorsmin-07bfm.md">ProcessQuadTessFactorsMin</a>(
    <span class="code_keyword">in</span> <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 4&gt; <a href="processquadtessfactorsmin-07bfm.md#decl-RawEdgeFactors" class="code_param">RawEdgeFactors</a>,
    <span class="code_keyword">in</span> <span class="code_keyword">float</span> <a href="processquadtessfactorsmin-07bfm.md#decl-InsideScale" class="code_param">InsideScale</a>,
    <span class="code_keyword">out</span> <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 4&gt; <a href="processquadtessfactorsmin-07bfm.md#decl-RoundedEdgeTessFactors" class="code_param">RoundedEdgeTessFactors</a>,
    <span class="code_keyword">out</span> <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 2&gt; <a href="processquadtessfactorsmin-07bfm.md#decl-RoundedInsideTessFactors" class="code_param">RoundedInsideTessFactors</a>,
    <span class="code_keyword">out</span> <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 2&gt; <a href="processquadtessfactorsmin-07bfm.md#decl-UnroundedInsideTessFactors" class="code_param">UnroundedInsideTessFactors</a>);

</pre>

## Parameters

####  <a id="decl-RawEdgeFactors"></a>RawEdgeFactors  : [vector](../types/vector/index.md)\<float, 4\>
####  <a id="decl-InsideScale"></a>InsideScale  : float
####  <a id="decl-RoundedEdgeTessFactors"></a>RoundedEdgeTessFactors  : [vector](../types/vector/index.md)\<float, 4\>
####  <a id="decl-RoundedInsideTessFactors"></a>RoundedInsideTessFactors  : [vector](../types/vector/index.md)\<float, 2\>
####  <a id="decl-UnroundedInsideTessFactors"></a>UnroundedInsideTessFactors  : [vector](../types/vector/index.md)\<float, 2\>

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
