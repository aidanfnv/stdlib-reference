---
layout: stdlib-reference
---
# Interfaces

Slang's Standard Library defines the following interfaces:

- [IArithmetic](../interfaces/iarithmetic-01/index.md)
- [IArithmeticAtomicable](../interfaces/iarithmeticatomicable-01b/index.md)
- [IArray](../interfaces/iarray-01/index.md)
- [IAtomicable](../interfaces/iatomicable-01/index.md)
- [IBitAtomicable](../interfaces/ibitatomicable-014/index.md)
- [IBufferDataLayout](../interfaces/ibufferdatalayout-017b/index.md)
- [IComparable](../interfaces/icomparable-01/index.md)
- [IDefaultInitializable](../interfaces/idefaultinitializable-018/index.md)
- [IDiffTensorWrapper](../interfaces/idifftensorwrapper-015b/index.md)
- [IDifferentiable](../interfaces/idifferentiable-01/index.md)
- [IDifferentiableFunc](../interfaces/idifferentiablefunc-01f/index.md)
- [IDifferentiableMutatingFunc](../interfaces/idifferentiablemutatingfunc-01fn/index.md)
- [IDifferentiablePtrType](../interfaces/idifferentiableptrtype-01fi/index.md)
- [IFloat](../interfaces/ifloat-01/index.md)
- [IFunc](../interfaces/ifunc-01/index.md)
- [IInteger](../interfaces/iinteger-01/index.md)
- [ILogical](../interfaces/ilogical-01/index.md)
- [IMutatingFunc](../interfaces/imutatingfunc-019/index.md)
- [IOpaqueDescriptor](../interfaces/iopaquedescriptor-017/index.md)
- [IPhysicalBuffer](../interfaces/iphysicalbuffer-019/index.md)
- [IRWArray](../interfaces/irwarray-0123/index.md)
- [IRWPhysicalBuffer](../interfaces/irwphysicalbuffer-0123b/index.md)
- [IRangedValue](../interfaces/irangedvalue-017/index.md)
- [ITexelElement](../interfaces/itexelelement-016/index.md)
- [\_\_BuiltinArithmeticType](../interfaces/0_builtinarithmetictype-029j/index.md)
- [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.md)
- [\_\_BuiltinIntegerType](../interfaces/0_builtinintegertype-029g/index.md)
- [\_\_BuiltinLogicalType](../interfaces/0_builtinlogicaltype-029g/index.md)
- [\_\_ITextureShape](../interfaces/0_itextureshape-023a/index.md)
- [\_\_ITextureShape1D2D3D](../interfaces/0_itextureshape1d2d3d-023agik/index.md)

```{toctree}
:titlesonly:
:hidden:

IArithmetic <../interfaces/iarithmetic-01/index>
IArithmeticAtomicable <../interfaces/iarithmeticatomicable-01b/index>
IArray <../interfaces/iarray-01/index>
IAtomicable <../interfaces/iatomicable-01/index>
IBitAtomicable <../interfaces/ibitatomicable-014/index>
IBufferDataLayout <../interfaces/ibufferdatalayout-017b/index>
IComparable <../interfaces/icomparable-01/index>
IDefaultInitializable <../interfaces/idefaultinitializable-018/index>
IDiffTensorWrapper <../interfaces/idifftensorwrapper-015b/index>
IDifferentiable <../interfaces/idifferentiable-01/index>
IDifferentiableFunc <../interfaces/idifferentiablefunc-01f/index>
IDifferentiableMutatingFunc <../interfaces/idifferentiablemutatingfunc-01fn/index>
IDifferentiablePtrType <../interfaces/idifferentiableptrtype-01fi/index>
IFloat <../interfaces/ifloat-01/index>
IFunc <../interfaces/ifunc-01/index>
IInteger <../interfaces/iinteger-01/index>
ILogical <../interfaces/ilogical-01/index>
IMutatingFunc <../interfaces/imutatingfunc-019/index>
IOpaqueDescriptor <../interfaces/iopaquedescriptor-017/index>
IPhysicalBuffer <../interfaces/iphysicalbuffer-019/index>
IRWArray <../interfaces/irwarray-0123/index>
IRWPhysicalBuffer <../interfaces/irwphysicalbuffer-0123b/index>
IRangedValue <../interfaces/irangedvalue-017/index>
ITexelElement <../interfaces/itexelelement-016/index>
__BuiltinArithmeticType <../interfaces/0_builtinarithmetictype-029j/index>
__BuiltinFloatingPointType <../interfaces/0_builtinfloatingpointtype-029hm/index>
__BuiltinIntegerType <../interfaces/0_builtinintegertype-029g/index>
__BuiltinLogicalType <../interfaces/0_builtinlogicaltype-029g/index>
__ITextureShape <../interfaces/0_itextureshape-023a/index>
__ITextureShape1D2D3D <../interfaces/0_itextureshape1d2d3d-023agik/index>
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
