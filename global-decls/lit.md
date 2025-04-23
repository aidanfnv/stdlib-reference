---
layout: stdlib-reference
---

# lit

## Description

Legacy lighting function (obsolete).




## Signature 

<pre>
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 4&gt; <a href="lit.md">lit</a>(
    <span class="code_keyword">float</span> <a href="lit.md#decl-n_dot_l" class="code_param">n_dot_l</a>,
    <span class="code_keyword">float</span> <a href="lit.md#decl-n_dot_h" class="code_param">n_dot_h</a>,
    <span class="code_keyword">float</span> <a href="lit.md#decl-m" class="code_param">m</a>);

</pre>

## Parameters

####  <a id="decl-n_dot_l"></a>n\_dot\_l  : float
The dot product of the normal and light vectors.

####  <a id="decl-n_dot_h"></a>n\_dot\_h  : float
The dot product of the normal and half-angle vectors.

####  <a id="decl-m"></a>m  : float
The material shininess factor.


## Return value
The lighting coefficients, (ambient, diffuse, specular, 1.0).

## Remarks
In HLSL, this function is implemented as an intrinsic. It is emulated for other targets.

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

#### metal
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
      const href = link.getAttribute('href');
      if (href && href.includes('.md')) {
        // This regex will handle .md links with or without fragment identifiers or query parameters
        link.href = link.href.replace(/(.+)\.md(#[^?]*)?(\?.*)?$/, '$1.html$2$3');
      }
    });
  });
}
</script>
