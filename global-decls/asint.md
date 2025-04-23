---
layout: stdlib-reference
---

# asint

## Description

Reinterpret bits as an int.




## Signature 

<pre>
/// Requires Capability Set 1:
<span class="code_keyword">int</span> <a href="asint.md">asint</a>(<span class="code_keyword">float</span> <a href="asint.md#decl-x" class="code_param">x</a>);

/// Requires Capability Set 1:
<span class="code_keyword">int</span> <a href="asint.md">asint</a>(<span class="code_keyword">uint</span> <a href="asint.md#decl-x" class="code_param">x</a>);

/// Requires Capability Set 1:
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="asint.md#decl-N" class="code_var">N</a>&gt; <a href="asint.md">asint</a>&lt;<a href="asint.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="asint.md#decl-N" class="code_var">N</a>&gt; <a href="asint.md#decl-x" class="code_param">x</a>);

/// Requires Capability Set 1:
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="asint.md#decl-N" class="code_var">N</a>&gt; <a href="asint.md">asint</a>&lt;<a href="asint.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="asint.md#decl-N" class="code_var">N</a>&gt; <a href="asint.md#decl-x" class="code_param">x</a>);

/// Requires Capability Set 2:
<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<span class="code_keyword">int</span>, <a href="asint.md#decl-N" class="code_var">N</a>, <a href="asint.md#decl-M" class="code_var">M</a>&gt; <a href="asint.md">asint</a>&lt;<a href="asint.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="asint.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<span class="code_keyword">float</span>, <a href="asint.md#decl-N" class="code_var">N</a>, <a href="asint.md#decl-M" class="code_var">M</a>&gt; <a href="asint.md#decl-x" class="code_param">x</a>);

/// Requires Capability Set 2:
<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<span class="code_keyword">int</span>, <a href="asint.md#decl-N" class="code_var">N</a>, <a href="asint.md#decl-M" class="code_var">M</a>&gt; <a href="asint.md">asint</a>&lt;<a href="asint.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="asint.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<span class="code_keyword">uint</span>, <a href="asint.md#decl-N" class="code_var">N</a>, <a href="asint.md#decl-M" class="code_var">M</a>&gt; <a href="asint.md#decl-x" class="code_param">x</a>);

<span class="code_keyword">int</span> <a href="asint.md">asint</a>(<span class="code_keyword">int</span> <a href="asint.md#decl-x" class="code_param">x</a>);

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="asint.md#decl-N" class="code_var">N</a>&gt; <a href="asint.md">asint</a>&lt;<a href="asint.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="asint.md#decl-N" class="code_var">N</a>&gt; <a href="asint.md#decl-x" class="code_param">x</a>);

<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<span class="code_keyword">int</span>, <a href="asint.md#decl-N" class="code_var">N</a>, <a href="asint.md#decl-M" class="code_var">M</a>&gt; <a href="asint.md">asint</a>&lt;<a href="asint.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="asint.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<span class="code_keyword">int</span>, <a href="asint.md#decl-N" class="code_var">N</a>, <a href="asint.md#decl-M" class="code_var">M</a>&gt; <a href="asint.md#decl-x" class="code_param">x</a>);

</pre>

## Generic Parameters

####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-x"></a>x  : float
####  <a id="decl-x"></a>x  : uint
####  <a id="decl-x"></a>x  : [vector](../types/vector/index.md)\<float, [N](../types/vector/index.md#decl-N)\>
####  <a id="decl-x"></a>x  : [vector](../types/vector/index.md)\<uint, [N](../types/vector/index.md#decl-N)\>
####  <a id="decl-x"></a>x  : [matrix](../types/matrix/index.md)\<float, [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
####  <a id="decl-x"></a>x  : [matrix](../types/matrix/index.md)\<uint, [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
####  <a id="decl-x"></a>x  : int
####  <a id="decl-x"></a>x  : [vector](../types/vector/index.md)\<int, [N](../types/vector/index.md#decl-N)\>
####  <a id="decl-x"></a>x  : [matrix](../types/matrix/index.md)\<int, [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>

## Availability and Requirements

### Capability Set 1

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cpp
Available in all stages.

#### cuda
Available in all stages.

#### metal
Available in all stages.

#### wgsl
Available in all stages.

#### spirv
Available in all stages.


### Capability Set 2

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
