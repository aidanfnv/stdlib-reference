---
layout: stdlib-reference
---

# getStringHash

## Description

Given a string returns an integer hash of that string.




## Signature 

<pre>
<span class="code_keyword">int</span> <a href="getstringhash-39.md">getStringHash</a>(<a href="../types/string-0/index.md" class="code_type">String</a> <a href="getstringhash-39.md#decl-string" class="code_param">string</a>);

</pre>

## Parameters

####  <a id="decl-string"></a>string  : [String](../types/string-0/index.md)


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
