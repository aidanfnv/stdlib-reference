---
layout: stdlib-reference
---
# Derivative functions

This category contains the following declarations:

#### [ddx\<T\>](ddx.md)

#### [ddx\_coarse\<T\>](ddx_coarse.md)

#### [ddx\_fine\<T\>](ddx_fine.md)

#### [ddy\<T\>](ddy.md)

#### [ddy\_coarse\<T\>](ddy_coarse.md)

#### [ddy\_fine\<T\>](ddy_fine.md)

#### [fwidth\<T\>](fwidth.md)


```{toctree}
:titlesonly:
:hidden:

ddx <ddx>
ddx_coarse <ddx_coarse>
ddx_fine <ddx_fine>
ddy <ddy>
ddy_coarse <ddy_coarse>
ddy_fine <ddy_fine>
fwidth <fwidth>
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
