---
layout: stdlib-reference
---

# attribute [instance]

## Description

Used on a geometry shader entry point to specify the number of instances to execute for each input primitive.

## Signature

<pre>
[<a href="instance.md">instance</a>(<a href="instance.md#decl-count" class="code_param">count</a> : <span class="code_keyword">int</span>)]
</pre>

## Parameters

####  <a id="decl-count"></a>count  : int
The number of instances to execute for each input primitive.


## Remarks

When using this attribute, a geometry shader can declare a parameter with <span class='code'>SV_GSInstanceID</span> semantic to get the instance index.



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
