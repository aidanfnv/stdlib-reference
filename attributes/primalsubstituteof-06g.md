---
layout: stdlib-reference
---

# attribute [PrimalSubstituteOf]

## Description

<span class='code'>[<a href="primalsubstituteof-06g.md">PrimalSubstituteOf</a>(fn)]</span> is the back-reference version of <span class='code'>[<a href="primalsubstitute-06.md">PrimalSubstitute</a>(substFn)]</span>

When used to decorate a function, that function is considered the substitute for the
referenced <span class='code'>fn</span>.
Apart from this difference, the semantics of the substitution are the same as for
<span class='code'>[<a href="primalsubstitute-06.md">PrimalSubstitute</a>(substFn)]</span>


## Signature

<pre>
[<a href="primalsubstituteof-06g.md">PrimalSubstituteOf</a>(<a href="primalsubstituteof-06g.md#decl-function" class="code_param">function</a>)]
</pre>

## Parameters

####  <a id="decl-function"></a>function


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
