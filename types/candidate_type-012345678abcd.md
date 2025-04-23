---
layout: stdlib-reference
---

# typealias CANDIDATE\_TYPE

## Description

Type of candidate hit that a <span class='code'><a href="rayquery-03/index.md" class="code_type">RayQuery</a></span> is pausing at.
A <span class='code'><a href="rayquery-03/index.md" class="code_type">RayQuery</a></span> can automatically commit hits with opaque triangles,
but yields to user code for other hits to allow them to be
dismissed or committed.


## Signature

<pre>
<span class='code_keyword'>typealias</span> <a href="candidate_type-012345678abcd.md" class="code_type">CANDIDATE_TYPE</a> = <span class="code_keyword">uint</span>;
</pre>


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
