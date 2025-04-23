---
layout: stdlib-reference
---

# GetRenderTargetSamplePosition

## Description





## Signature 

<pre>
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 2&gt; <a href="getrendertargetsampleposition-039fl.md">GetRenderTargetSamplePosition</a>(<span class="code_keyword">int</span> <a href="getrendertargetsampleposition-039fl.md#decl-Index" class="code_param">Index</a>);

</pre>

## Parameters

####  <a id="decl-Index"></a>Index  : int

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### metal
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
