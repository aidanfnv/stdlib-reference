---
layout: stdlib-reference
---

# enum _AttributeTargets

## Description

Represents the applicable target for an attribute.


## Values 

####  <a id="decl-Struct"></a>_Struct = 1_
####  <a id="decl-Var"></a>_Var = 2_
Struct types.

####  <a id="decl-Function"></a>_Function = 4_
Global and local variables and constants.

####  <a id="decl-Param"></a>_Param = 8_
Functions or member functions.


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
