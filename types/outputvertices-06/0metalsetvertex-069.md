---
layout: stdlib-reference
---

# OutputVertices\<T, MAX\_VERTS:uint\>\.\_metalSetVertex

## Description





## Signature 

<pre>
<span class='code_keyword'>static</span> <span class="code_keyword">void</span> <a href="index.md" class="code_type">OutputVertices</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-MAX_VERTS" class="code_var">MAX_VERTS</a>:<span class="code_keyword">uint</span>&gt;.<a href="0metalsetvertex-069.md">_metalSetVertex</a>(
    <span class="code_keyword">uint</span> <a href="0metalsetvertex-069.md#decl-index" class="code_param">index</a>,
    <a href="index.md#typeparam-T" class="code_type">T</a> <a href="0metalsetvertex-069.md#decl-val" class="code_param">val</a>);

</pre>

## Parameters

####  <a id="decl-index"></a>index  : uint
####  <a id="decl-val"></a>val  : [T](index.md#typeparam-T)


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
