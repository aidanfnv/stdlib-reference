---
layout: stdlib-reference
---

# enum MemoryOrder

## Description



## Values 

####  <a id="decl-Relaxed"></a>_Relaxed = 0_
No memory operation ordering constraints

####  <a id="decl-Acquire"></a>_Acquire = 1_
Ensures that all subsequent memory operations in the same thread are not reordered before it

####  <a id="decl-Release"></a>_Release = 2_
Ensures that all prior memory operations in the same thread are not reordered after it

####  <a id="decl-AcquireRelease"></a>_AcquireRelease = 3_
Combines both acquire and release semantics

####  <a id="decl-SeqCst"></a>_SeqCst = 4_
Provides the strongest ordering: total order exists between all SeqCst operations


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
