---
layout: stdlib-reference
---

# property Optional\<T\>\.hasValue

## Description

Return <span class='code'>true</span> iff this <span class='code'><a href="index.md" class="code_type">Optional</a></span> contains a value of type <span class='code'><a href="index.md#typeparam-T" class="code_type">T</a></span>


## Signature

<pre>
<span class='code_keyword'>property</span> <a href="index.md" class="code_type">Optional</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="hasvalue-3.md">hasValue</a> : <span class="code_keyword">bool</span>
{
    get;
}
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
