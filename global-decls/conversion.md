---
layout: stdlib-reference
---
# Conversion functions

This category contains the following declarations:

#### [asdouble](asdouble.md)

#### [asfloat](asfloat.md)

#### [asfloat16](asfloat16.md)

#### [asint](asint.md)

#### [asint16](asint16.md)

#### [asuint](asuint.md)

#### [asuint16](asuint16.md)

#### [bit\_cast\<T, U\>](bit_cast.md)

#### [f16tof32](f16tof32.md)

#### [f32tof16](f32tof16.md)

#### [f32tof16\_](f32tof16_.md)

#### [reinterpret\<T, U\>](reinterpret.md)


```{toctree}
:titlesonly:
:hidden:

asdouble <asdouble>
asfloat <asfloat>
asfloat16 <asfloat16>
asint <asint>
asint16 <asint16>
asuint <asuint>
asuint16 <asuint16>
bit_cast <bit_cast>
f16tof32 <f16tof32>
f32tof16 <f32tof16>
f32tof16_ <f32tof16_>
reinterpret <reinterpret>
```

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
