---
layout: stdlib-reference
---

# COMMITTED_PROCEDURAL_PRIMITIVE_HIT

## Description

Closest hit is a procedural primitive.
A procedural hit primitive is committed using <span class='code'><a href="../types/rayquery-03/index.md" class="code_type">RayQuery</a>.<a href="../types/rayquery-03/commitproceduralprimitivehit-06gp.md">CommitProceduralPrimitiveHit</a></span>.


## Signature
<pre>
<span class='code_keyword'>static</span> <span class='code_keyword'>const</span> <span class="code_keyword">uint</span> <a href="committed_procedural_primitive_hit-012345678abcdefghijlmnopqrstvwx.md" class="code_var">COMMITTED_PROCEDURAL_PRIMITIVE_HIT</a> = 2;
</pre>


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
