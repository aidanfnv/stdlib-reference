---
layout: stdlib-reference
---

# asdouble

## Description

Reinterpret bits as a double.




## Signature 

<pre>
<span class="code_keyword">double</span> <a href="asdouble.md">asdouble</a>(
    <span class="code_keyword">uint</span> <a href="asdouble.md#decl-lowbits" class="code_param">lowbits</a>,
    <span class="code_keyword">uint</span> <a href="asdouble.md#decl-highbits" class="code_param">highbits</a>);

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">double</span>, 2&gt; <a href="asdouble.md">asdouble</a>(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 2&gt; <a href="asdouble.md#decl-lowbits" class="code_param">lowbits</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 2&gt; <a href="asdouble.md#decl-highbits" class="code_param">highbits</a>);

</pre>

## Parameters

####  <a id="decl-lowbits"></a>lowbits  : uint
####  <a id="decl-highbits"></a>highbits  : uint
####  <a id="decl-lowbits"></a>lowbits  : [vector](../types/vector/index.md)\<uint, 2\>
####  <a id="decl-highbits"></a>highbits  : [vector](../types/vector/index.md)\<uint, 2\>

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cpp
Available in all stages.

#### cuda
Available in all stages.

#### spirv
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
