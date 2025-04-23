---
layout: stdlib-reference
---

# RayQuery\<rayFlagsGeneric:uint\>\.Proceed

## Description

Resume the ray query coroutine.

If the coroutine suspends because of encountering
a candidate hit that cannot be resolved with fixed-funciton
logic, this function returns <span class='code'>true</span>, and the <span class='code'>Candidate*()</span>
functions should be used by application code to resolve
the candidate hit (by either committing or ignoring it).

If the coroutine terminates because traversal is
complete (or has been aborted), this function returns
<span class='code'>false</span>, and application code should use the <span class='code'>Committed*()</span>
functions to appropriately handle the closest hit (it any)
that was found.




## Signature 

<pre>
<span class="code_keyword">bool</span> <a href="index.md" class="code_type">RayQuery</a>&lt;<a href="index.md#decl-rayFlagsGeneric" class="code_var">rayFlagsGeneric</a>:<span class="code_keyword">uint</span>&gt;.<a href="proceed-0.md">Proceed</a>();

</pre>

## Return value
true if a candidate hit needs evaluation, false if traversal is complete

## Remarks
When true is returned, use Candidate* methods to evaluate the hit


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvRayQueryKHR`.



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
