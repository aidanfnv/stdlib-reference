---
layout: stdlib-reference
---
# Wave and quad functions

This category contains the following declarations:

#### [QuadReadAcrossDiagonal\<T\>](quadreadacrossdiagonal-048e.md)

#### [QuadReadAcrossX\<T\>](quadreadacrossx-048e.md)

#### [QuadReadAcrossY\<T\>](quadreadacrossy-048e.md)

#### [QuadReadLaneAt\<T\>](quadreadlaneat-048c.md)

#### [WaveActiveAllEqual\<T\>](waveactiveallequal-04ad.md)

#### [WaveActiveAllTrue](waveactivealltrue-04ad.md)

#### [WaveActiveAnyTrue](waveactiveanytrue-04ad.md)

#### [WaveActiveBallot](waveactiveballot-04a.md)

#### [WaveActiveBitAnd\<T\>](waveactivebitand-04ad.md)

#### [WaveActiveBitOr\<T\>](waveactivebitor-04ad.md)

#### [WaveActiveBitXor\<T\>](waveactivebitxor-04ad.md)

#### [WaveActiveCountBits](waveactivecountbits-04af.md)

#### [WaveActiveMax\<T\>](waveactivemax-04a.md)

#### [WaveActiveMin\<T\>](waveactivemin-04a.md)

#### [WaveActiveProduct\<T\>](waveactiveproduct-04a.md)

#### [WaveActiveSum\<T\>](waveactivesum-04a.md)

#### [WaveBroadcastLaneAt\<T\>](wavebroadcastlaneat-04dh.md)

#### [WaveGetActiveMulti](wavegetactivemulti-047d.md)

#### [WaveGetConvergedMulti](wavegetconvergedmulti-047g.md)

#### [WaveGetLaneCount](wavegetlanecount-047b.md)

#### [WaveGetLaneIndex](wavegetlaneindex-047b.md)

#### [WaveIsFirstLane](waveisfirstlane-046b.md)

#### [WaveMatch\<T\>](wavematch-04.md)

#### [WaveMultiPrefixBitAnd\<T\>](wavemultiprefixbitand-049fi.md)

#### [WaveMultiPrefixBitOr\<T\>](wavemultiprefixbitor-049fi.md)

#### [WaveMultiPrefixBitXor\<T\>](wavemultiprefixbitxor-049fi.md)

#### [WaveMultiPrefixCountBits](wavemultiprefixcountbits-049fk.md)

#### [WaveMultiPrefixProduct\<T\>](wavemultiprefixproduct-049f.md)

#### [WaveMultiPrefixSum\<T\>](wavemultiprefixsum-049f.md)

#### [WavePrefixCountBits](waveprefixcountbits-04af.md)

#### [WavePrefixProduct\<T\>](waveprefixproduct-04a.md)

#### [WavePrefixSum\<T\>](waveprefixsum-04a.md)

#### [WaveReadLaneAt\<T\>](wavereadlaneat-048c.md)

#### [WaveReadLaneFirst\<T\>](wavereadlanefirst-048c.md)

#### [WaveShuffle\<T\>](waveshuffle-04.md)

#### [\_WaveCountBits](0wavecountbits-015a.md)


```{toctree}
:titlesonly:
:hidden:

QuadReadAcrossDiagonal <quadreadacrossdiagonal-048e>
QuadReadAcrossX <quadreadacrossx-048e>
QuadReadAcrossY <quadreadacrossy-048e>
QuadReadLaneAt <quadreadlaneat-048c>
WaveActiveAllEqual <waveactiveallequal-04ad>
WaveActiveAllTrue <waveactivealltrue-04ad>
WaveActiveAnyTrue <waveactiveanytrue-04ad>
WaveActiveBallot <waveactiveballot-04a>
WaveActiveBitAnd <waveactivebitand-04ad>
WaveActiveBitOr <waveactivebitor-04ad>
WaveActiveBitXor <waveactivebitxor-04ad>
WaveActiveCountBits <waveactivecountbits-04af>
WaveActiveMax <waveactivemax-04a>
WaveActiveMin <waveactivemin-04a>
WaveActiveProduct <waveactiveproduct-04a>
WaveActiveSum <waveactivesum-04a>
WaveBroadcastLaneAt <wavebroadcastlaneat-04dh>
WaveGetActiveMulti <wavegetactivemulti-047d>
WaveGetConvergedMulti <wavegetconvergedmulti-047g>
WaveGetLaneCount <wavegetlanecount-047b>
WaveGetLaneIndex <wavegetlaneindex-047b>
WaveIsFirstLane <waveisfirstlane-046b>
WaveMatch <wavematch-04>
WaveMultiPrefixBitAnd <wavemultiprefixbitand-049fi>
WaveMultiPrefixBitOr <wavemultiprefixbitor-049fi>
WaveMultiPrefixBitXor <wavemultiprefixbitxor-049fi>
WaveMultiPrefixCountBits <wavemultiprefixcountbits-049fk>
WaveMultiPrefixProduct <wavemultiprefixproduct-049f>
WaveMultiPrefixSum <wavemultiprefixsum-049f>
WavePrefixCountBits <waveprefixcountbits-04af>
WavePrefixProduct <waveprefixproduct-04a>
WavePrefixSum <waveprefixsum-04a>
WaveReadLaneAt <wavereadlaneat-048c>
WaveReadLaneFirst <wavereadlanefirst-048c>
WaveShuffle <waveshuffle-04>
_WaveCountBits <0wavecountbits-015a>
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
