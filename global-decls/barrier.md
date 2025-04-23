---
layout: stdlib-reference
---
# Memory and control barriers

This category contains the following declarations:

#### [AllMemoryBarrier](allmemorybarrier-039.md)

#### [AllMemoryBarrierWithGroupSync](allmemorybarrierwithgroupsync-039gkp.md)

#### [DeviceMemoryBarrier](devicememorybarrier-06c.md)

#### [DeviceMemoryBarrierWithGroupSync](devicememorybarrierwithgroupsync-06cjns.md)

#### [GroupMemoryBarrier](groupmemorybarrier-05b.md)

#### [GroupMemoryBarrierWithGroupSync](groupmemorybarrierwithgroupsync-05bimr.md)


```{toctree}
:titlesonly:
:hidden:

AllMemoryBarrier <allmemorybarrier-039>
AllMemoryBarrierWithGroupSync <allmemorybarrierwithgroupsync-039gkp>
DeviceMemoryBarrier <devicememorybarrier-06c>
DeviceMemoryBarrierWithGroupSync <devicememorybarrierwithgroupsync-06cjns>
GroupMemoryBarrier <groupmemorybarrier-05b>
GroupMemoryBarrierWithGroupSync <groupmemorybarrierwithgroupsync-05bimr>
```

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
