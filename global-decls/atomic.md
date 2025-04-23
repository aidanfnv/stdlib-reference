---
layout: stdlib-reference
---
# Atomic functions

This category contains the following declarations:

#### [InterlockedAdd\<T\>](interlockedadd-0b.md)

#### [InterlockedAnd\<T\>](interlockedand-0b.md)

#### [InterlockedCompareExchange\<T\>](interlockedcompareexchange-0bi.md)

#### [InterlockedCompareExchangeFloatBitwise](interlockedcompareexchangefloatbitwise-0biqv.md)

#### [InterlockedCompareStore\<T\>](interlockedcomparestore-0bi.md)

#### [InterlockedCompareStoreFloatBitwise\<T\>](interlockedcomparestorefloatbitwise-0bins.md)

#### [InterlockedExchange\<T\>](interlockedexchange-0b.md)

#### [InterlockedMax\<T\>](interlockedmax-0b.md)

#### [InterlockedMin\<T\>](interlockedmin-0b.md)

#### [InterlockedOr\<T\>](interlockedor-0b.md)

#### [InterlockedXor\<T\>](interlockedxor-0b.md)


```{toctree}
:titlesonly:
:hidden:

InterlockedAdd <interlockedadd-0b>
InterlockedAnd <interlockedand-0b>
InterlockedCompareExchange <interlockedcompareexchange-0bi>
InterlockedCompareExchangeFloatBitwise <interlockedcompareexchangefloatbitwise-0biqv>
InterlockedCompareStore <interlockedcomparestore-0bi>
InterlockedCompareStoreFloatBitwise <interlockedcomparestorefloatbitwise-0bins>
InterlockedExchange <interlockedexchange-0b>
InterlockedMax <interlockedmax-0b>
InterlockedMin <interlockedmin-0b>
InterlockedOr <interlockedor-0b>
InterlockedXor <interlockedxor-0b>
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
