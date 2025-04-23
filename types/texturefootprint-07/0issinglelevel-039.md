---
layout: stdlib-reference
---

# TextureFootprint<ND:int>._isSingleLevel

## Signature
<pre>
<span class="code_keyword">bool</span> <a href="index.md" class="code_type">TextureFootprint</a>&lt;<a href="index.md#decl-ND" class="code_var">ND</a>:<span class="code_keyword">int</span>&gt;.<a href="0issinglelevel-039.md" class="code_var">_isSingleLevel</a>;
</pre>


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
