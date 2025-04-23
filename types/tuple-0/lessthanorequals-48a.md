---
layout: stdlib-reference
---

# Tuple\<T\>\.lessThanOrEquals

## Description





## Signature 

<pre>
<span class="code_keyword">bool</span> <a href="index.md" class="code_type">Tuple</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="lessthanorequals-48a.md">lessThanOrEquals</a>(<a href="index.md" class="code_type">Tuple</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt; <a href="lessthanorequals-48a.md#decl-other" class="code_param">other</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/icomparable-01/index.md" class="code_type">IComparable</a>;

</pre>

## Parameters

####  <a id="decl-other"></a>other  : [Tuple](index.md)\<[T](index.md#typeparam-T)\>


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
