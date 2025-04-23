---
layout: stdlib-reference
---

# attribute [allow\_uav\_condition]

> #### Deprecated Feature
> The feature described in this page is marked as deprecated, and may be removed in a future release.
> Users are advised to avoid using this feature, and to migrate to a newer alternative.

## Description

A hint to the downstream compiler that UAV conditions are allowed in the loop.
This attribute has no effect on targets other than HLSL.


## Signature

<pre>
[<a href="allow_uav_condition.md">allow_uav_condition</a>]
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
