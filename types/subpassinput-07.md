---
layout: stdlib-reference
---

# typealias SubpassInput\<T, isMS:int\>

## Description



## Signature

<pre>
<span class='code_keyword'>typealias</span> <a href="subpassinput-07.md" class="code_type">SubpassInput</a>&lt;T, isMS:<span class="code_keyword">int</span>&gt; = __SubpassImpl&lt;T, isMS&gt;;
</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T  = [vector](vector/index.md)\<float, 4\>
####  <a id="decl-isMS"></a>isMS  : int = 0


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
