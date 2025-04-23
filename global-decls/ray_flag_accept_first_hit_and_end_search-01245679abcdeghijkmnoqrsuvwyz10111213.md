---
layout: stdlib-reference
---

# RAY_FLAG_ACCEPT_FIRST_HIT_AND_END_SEARCH

## Description

Accepts the first intersection found and skips searching for closer hits.


## Signature
<pre>
<span class='code_keyword'>static</span> <span class='code_keyword'>const</span> <span class="code_keyword">uint</span> <a href="ray_flag_accept_first_hit_and_end_search-01245679abcdeghijkmnoqrsuvwyz10111213.md" class="code_var">RAY_FLAG_ACCEPT_FIRST_HIT_AND_END_SEARCH</a> = 0x04;
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
