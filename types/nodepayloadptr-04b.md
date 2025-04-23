---
layout: stdlib-reference
---

# typealias NodePayloadPtr\<T\>

## Signature

<pre>
<span class='code_keyword'>typealias</span> <a href="nodepayloadptr-04b.md" class="code_type">NodePayloadPtr</a>&lt;T&gt; = <a href="ptr-0/index.md" class="code_type">Ptr</a>&lt;T&gt;;
</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T


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
