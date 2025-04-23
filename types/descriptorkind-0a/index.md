---
layout: stdlib-reference
---

# enum DescriptorKind

## Description

Represent the kind of a descriptor type.


## Values 

####  <a id="decl-Unknown"></a>_Unknown = _
####  <a id="decl-Texture"></a>_Texture = _
Unknown descriptor kind.

####  <a id="decl-CombinedTextureSampler"></a>_CombinedTextureSampler = _
A texture descriptor.

####  <a id="decl-Buffer"></a>_Buffer = _
A combined texture and sampler state descriptor.

####  <a id="decl-Sampler"></a>_Sampler = _
A buffer descriptor.

####  <a id="decl-AccelerationStructure"></a>_AccelerationStructure = _
A sampler state descriptor.


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
