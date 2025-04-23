---
layout: stdlib-reference
---

# DescriptorHandle\<T\>\.equals

## Description





## Signature 

<pre>
<span class="code_keyword">bool</span> <a href="index.md" class="code_type">DescriptorHandle</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="equals.md">equals</a>(<a href="index.md" class="code_type">DescriptorHandle</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt; <a href="equals.md#decl-other" class="code_param">other</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/iopaquedescriptor-017/index.md" class="code_type">IOpaqueDescriptor</a>;

</pre>

## Parameters

####  <a id="decl-other"></a>other  : [DescriptorHandle](index.md)\<[T](index.md#typeparam-T)\>


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
