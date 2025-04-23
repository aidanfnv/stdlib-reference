---
layout: stdlib-reference
---

# NativeString\.getBuffer

## Description





## Signature 

<pre>
<a href="../ptr-0/index.md" class="code_type">Ptr</a>&lt;<span class="code_keyword">void</span>&gt; <a href="index.md" class="code_type">NativeString</a>.<a href="getbuffer-3.md">getBuffer</a>();

</pre>

## Availability and Requirements

Defined for the following targets:

#### cpp
Available in all stages.




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
