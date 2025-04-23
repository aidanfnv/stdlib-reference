---
layout: stdlib-reference
---

# unused

## Description

Use an otherwise unused value
This can be used to silence the warning about returning before initializing an out paramter.




## Signature 

<pre>
<span class="code_keyword">void</span> <a href="unused.md">unused</a>&lt;<a href="unused.md#typeparam-T" class="code_type">T</a>&gt;(<span class="code_keyword">inout</span> <a href="unused.md#typeparam-T" class="code_type">T</a> <a href="unused.md#decl-SLANG_anonymous_5" class="code_param">SLANG_anonymous_5</a>);

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T

## Parameters

####  <a id="decl-SLANG_anonymous_5"></a>SLANG\_anonymous\_5  : [T](unused.md#typeparam-T)
Use an otherwise unused value
This can be used to silence the warning about returning before initializing an out paramter.



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
