---
layout: stdlib-reference
---

# OutputVertices\<T, MAX\_VERTS:uint\>\.\_setVertex

## Description





## Signature 

<pre>
<span class='code_keyword'>static</span> <span class="code_keyword">void</span> <a href="index.md" class="code_type">OutputVertices</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-MAX_VERTS" class="code_var">MAX_VERTS</a>:<span class="code_keyword">uint</span>&gt;.<a href="0setvertex-04.md">_setVertex</a>(
    <a href="index.md" class="code_type">OutputVertices</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-MAX_VERTS" class="code_var">MAX_VERTS</a>&gt; <a href="0setvertex-04.md#decl-v" class="code_param">v</a>,
    <span class="code_keyword">uint</span> <a href="0setvertex-04.md#decl-index" class="code_param">index</a>,
    <a href="index.md#typeparam-T" class="code_type">T</a> <a href="0setvertex-04.md#decl-val" class="code_param">val</a>);

</pre>

## Parameters

####  <a id="decl-v"></a>v  : [OutputVertices](index.md)\<[T](index.md#typeparam-T), [MAX\_VERTS](index.md#decl-MAX_VERTS)\>
####  <a id="decl-index"></a>index  : uint
####  <a id="decl-val"></a>val  : [T](index.md#typeparam-T)


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
