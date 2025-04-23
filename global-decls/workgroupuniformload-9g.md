---
layout: stdlib-reference
---

# workgroupUniformLoad

## Description

Mark a variable as being workgroup uniform.



## Signature 

<pre>
<a href="workgroupuniformload-9g.md#typeparam-T" class="code_type">T</a> <a href="workgroupuniformload-9g.md">workgroupUniformLoad</a>&lt;<a href="workgroupuniformload-9g.md#typeparam-T" class="code_type">T</a>&gt;(<a href="workgroupuniformload-9g.md#typeparam-T" class="code_type">T</a> <a href="workgroupuniformload-9g.md#decl-v" class="code_param">v</a>);

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T

## Parameters

####  <a id="decl-v"></a>v  : [T](workgroupuniformload-9g.md#typeparam-T)
The variable to mark as workgroup uniform.


## Return value
The value of <span class='code'><a href="workgroupuniformload-9g.md#decl-v" class="code_param">v</a></span>.

## Remarks
This intrinsic maps to <span class='code'><a href="workgroupuniformload-9g.md">workgroupUniformLoad</a></span> when targeting WGSL and is a no-op on other targets.
WGSL is strict on uniformity, and this intrinsic is needed to mark a variable as workgroup uniform in order



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
