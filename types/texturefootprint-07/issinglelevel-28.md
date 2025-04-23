---
layout: stdlib-reference
---

# property TextureFootprint\<ND:int\>\.isSingleLevel

## Signature

<pre>
<span class='code_keyword'>property</span> <a href="index.md" class="code_type">TextureFootprint</a>&lt;<a href="index.md#decl-ND" class="code_var">ND</a>:<span class="code_keyword">int</span>&gt;.<a href="issinglelevel-28.md">isSingleLevel</a> : <span class="code_keyword">bool</span>
{
    get;
}
</pre>


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
