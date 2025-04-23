---
layout: stdlib-reference
---

# enum CoopMatScope

## Values 

####  <a id="decl-Device"></a>_Device = 1_
####  <a id="decl-Workgroup"></a>_Workgroup = 2_
####  <a id="decl-Subgroup"></a>_Subgroup = 3_
####  <a id="decl-QueueFamily"></a>_QueueFamily = 5_

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
