---
layout: stdlib-reference
---

# typealias COMMITTED\_STATUS

## Description

Status indicating whether and what type of hit has been committed in a RayQuery.


## Signature

<pre>
<span class='code_keyword'>typealias</span> <a href="committed_status-012345678abcdef.md" class="code_type">COMMITTED_STATUS</a> = <span class="code_keyword">uint</span>;
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
