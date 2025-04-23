---
layout: stdlib-reference
---

# property NativeString\.length

## Signature

<pre>
<span class='code_keyword'>property</span> <a href="index.md" class="code_type">NativeString</a>.<a href="length.md">length</a> : <span class="code_keyword">int</span>
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
