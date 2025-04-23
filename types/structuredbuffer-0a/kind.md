---
layout: stdlib-reference
---

# StructuredBuffer<T, L>.kind

## Signature
<pre>
<span class='code_keyword'>static</span> <span class='code_keyword'>const</span> <a href="../descriptorkind-0a/index.md" class="code_type">DescriptorKind</a> <a href="index.md" class="code_type">StructuredBuffer</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-L" class="code_type">L</a>&gt;.<a href="kind.md" class="code_var">kind</a> = DescriptorKind\.Buffer;
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
