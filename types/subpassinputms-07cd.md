---
layout: stdlib-reference
---

# typealias SubpassInputMS\<T, isMS:int\>

## Description



## Signature

<pre>
<span class='code_keyword'>typealias</span> <a href="subpassinputms-07cd.md" class="code_type">SubpassInputMS</a>&lt;T, isMS:<span class="code_keyword">int</span>&gt; = 
    __SubpassImpl&lt;T, isMS&gt;;
</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T  = [vector](vector/index.md)\<float, 4\>
####  <a id="decl-isMS"></a>isMS  : int = 1


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
