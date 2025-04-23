---
layout: stdlib-reference
---
# Tessellation functions

This category contains the following declarations:

#### [Process2DQuadTessFactorsAvg](process2dquadtessfactorsavg-089dho.md)

#### [Process2DQuadTessFactorsMax](process2dquadtessfactorsmax-089dho.md)

#### [Process2DQuadTessFactorsMin](process2dquadtessfactorsmin-089dho.md)

#### [ProcessIsolineTessFactors](processisolinetessfactors-07ei.md)

#### [ProcessQuadTessFactorsAvg](processquadtessfactorsavg-07bfm.md)

#### [ProcessQuadTessFactorsMax](processquadtessfactorsmax-07bfm.md)

#### [ProcessQuadTessFactorsMin](processquadtessfactorsmin-07bfm.md)

#### [ProcessTriTessFactorsAvg](processtritessfactorsavg-07ael.md)

#### [ProcessTriTessFactorsMax](processtritessfactorsmax-07ael.md)

#### [ProcessTriTessFactorsMin](processtritessfactorsmin-07ael.md)


```{toctree}
:titlesonly:
:hidden:

Process2DQuadTessFactorsAvg <process2dquadtessfactorsavg-089dho>
Process2DQuadTessFactorsMax <process2dquadtessfactorsmax-089dho>
Process2DQuadTessFactorsMin <process2dquadtessfactorsmin-089dho>
ProcessIsolineTessFactors <processisolinetessfactors-07ei>
ProcessQuadTessFactorsAvg <processquadtessfactorsavg-07bfm>
ProcessQuadTessFactorsMax <processquadtessfactorsmax-07bfm>
ProcessQuadTessFactorsMin <processquadtessfactorsmin-07bfm>
ProcessTriTessFactorsAvg <processtritessfactorsavg-07ael>
ProcessTriTessFactorsMax <processtritessfactorsmax-07ael>
ProcessTriTessFactorsMin <processtritessfactorsmin-07ael>
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
