---
layout: stdlib-reference
---
# Buffer types

This category contains the following declarations:

#### [AppendStructuredBuffer\<T, L\>](appendstructuredbuffer-06g/index.md)

#### [ByteAddressBuffer](byteaddressbuffer-04b/index.md)

#### [ConsumeStructuredBuffer\<T, L\>](consumestructuredbuffer-07h/index.md)

#### [RWByteAddressBuffer](rwbyteaddressbuffer-0126d/index.md)

#### [RWStructuredBuffer\<T, L\>](rwstructuredbuffer-012c/index.md)

#### [RasterizerOrderedByteAddressBuffer](rasterizerorderedbyteaddressbuffer-0ahls/index.md)

#### [RasterizerOrderedStructuredBuffer\<T, L\>](rasterizerorderedstructuredbuffer-0ahr/index.md)

#### [StructuredBuffer\<T, L\>](structuredbuffer-0a/index.md)


```{toctree}
:titlesonly:
:hidden:

AppendStructuredBuffer <../types/appendstructuredbuffer-06g/index>
ByteAddressBuffer <../types/byteaddressbuffer-04b/index>
ConsumeStructuredBuffer <../types/consumestructuredbuffer-07h/index>
RWByteAddressBuffer <../types/rwbyteaddressbuffer-0126d/index>
RWStructuredBuffer <../types/rwstructuredbuffer-012c/index>
RasterizerOrderedByteAddressBuffer <../types/rasterizerorderedbyteaddressbuffer-0ahls/index>
RasterizerOrderedStructuredBuffer <../types/rasterizerorderedstructuredbuffer-0ahr/index>
StructuredBuffer <../types/structuredbuffer-0a/index>
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
