---
layout: stdlib-reference
---

# ByteAddressBuffer\.LoadByteOffset

## Description





## Signature 

<pre>
<a href="loadbyteoffset-048.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">ByteAddressBuffer</a>.<a href="loadbyteoffset-048.md">LoadByteOffset</a>&lt;<a href="loadbyteoffset-048.md#typeparam-T" class="code_type">T</a>&gt;(<span class="code_keyword">int</span> <a href="loadbyteoffset-048.md#decl-offset" class="code_param">offset</a>);

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T

## Parameters

####  <a id="decl-offset"></a>offset  : int


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
