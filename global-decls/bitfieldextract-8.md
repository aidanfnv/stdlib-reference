---
layout: stdlib-reference
---

# bitfieldExtract

## Description

<span class='code'><a href="bitfieldextract-8.md">bitfieldExtract</a></span> extracts a subset of the bits of <span class='code'><a href="bitfieldextract-8.md#decl-value" class="code_param">value</a></span> and
returns it in the least significant bits of the result. The range of bits extracted is [offset, offset + bits - 1].




## Signature 

<pre>
<a href="bitfieldextract-8.md#typeparam-T" class="code_type">T</a> <a href="bitfieldextract-8.md">bitfieldExtract</a>&lt;<a href="bitfieldextract-8.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="bitfieldextract-8.md#typeparam-T" class="code_type">T</a> <a href="bitfieldextract-8.md#decl-value" class="code_param">value</a>,
    <span class="code_keyword">uint</span> <a href="bitfieldextract-8.md#decl-offset" class="code_param">offset</a>,
    <span class="code_keyword">uint</span> <a href="bitfieldextract-8.md#decl-bits" class="code_param">bits</a>);

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T

## Parameters

####  <a id="decl-value"></a>value  : [T](bitfieldextract-8.md#typeparam-T)
####  <a id="decl-offset"></a>offset  : uint
####  <a id="decl-bits"></a>bits  : uint


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
