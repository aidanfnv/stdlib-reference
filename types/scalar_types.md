---
layout: stdlib-reference
---
# Scalar types

This category contains the following declarations:

#### [float16\_t](float16_t.md)

#### [float32\_t](float32_t.md)

#### [float64\_t](float64_t.md)

#### [int32\_t](int32_t.md)

#### [size\_t](size_t.md)

#### [ssize\_t](ssize_t.md)

#### [uint32\_t](uint32_t.md)

#### [usize\_t](usize_t.md)


```{toctree}
:titlesonly:
:hidden:

float16_t <../types/float16_t>
float32_t <../types/float32_t>
float64_t <../types/float64_t>
int32_t <../types/int32_t>
size_t <../types/size_t>
ssize_t <../types/ssize_t>
uint32_t <../types/uint32_t>
usize_t <../types/usize_t>
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
