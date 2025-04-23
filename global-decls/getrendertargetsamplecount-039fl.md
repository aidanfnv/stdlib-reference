---
layout: stdlib-reference
---

# GetRenderTargetSampleCount

## Description





## Signature 

<pre>
<span class="code_keyword">uint</span> <a href="getrendertargetsamplecount-039fl.md">GetRenderTargetSampleCount</a>();

</pre>

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
