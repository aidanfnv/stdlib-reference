---
layout: stdlib-reference
---

# QuadAny

## Description

Returns true if <span class='code'><a href="quadany-04.md#decl-expr" class="code_param">expr</a></span> is true in any lane of the current quad.




## Signature 

<pre>
<span class="code_keyword">bool</span> <a href="quadany-04.md">QuadAny</a>(<span class="code_keyword">bool</span> <a href="quadany-04.md#decl-expr" class="code_param">expr</a>);

</pre>

## Parameters

####  <a id="decl-expr"></a>expr  : bool

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### metal
Available in all stages.

#### spirv
Available in all stages.

Requires capabilities: `spvGroupNonUniformVote`, `spvMaximalReconvergenceKHR`, `spvQuadControlKHR`.



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
