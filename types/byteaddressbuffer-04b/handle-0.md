---
layout: stdlib-reference
---

# typealias ByteAddressBuffer\.Handle

## Signature

<pre>
<span class='code_keyword'>typealias</span> <a href="index.md" class="code_type">ByteAddressBuffer</a>.<a href="handle-0.md" class="code_type">Handle</a> = <a href="../descriptorhandle-0a/index.md" class="code_type">DescriptorHandle</a>&lt;<a href="index.md" class="code_type">ByteAddressBuffer</a>&gt;;
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
