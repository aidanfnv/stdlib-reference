---
layout: stdlib-reference
---

# DescriptorHandle\<T\>\.init

## Description





## Signature 

<pre>
<a href="index.md" class="code_type">DescriptorHandle</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="init.md">init</a>(<a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 2&gt; <a href="init.md#decl-handleValue" class="code_param">handleValue</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/iopaquedescriptor-017/index.md" class="code_type">IOpaqueDescriptor</a>;

</pre>

## Parameters

####  <a id="decl-handleValue"></a>handleValue  : [vector](../vector/index.md)\<uint, 2\>

## Availability and Requirements

Defined for the following targets:

#### glsl
Available in all stages.

#### spirv
Available in all stages.

#### hlsl
Available in all stages.

#### wgsl
Available in all stages.




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
