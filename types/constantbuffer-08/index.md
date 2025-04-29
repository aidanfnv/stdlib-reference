---
layout: stdlib-reference
---

# struct ConstantBuffer\<T, L\>

*Conditionally conforms to:* \_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>

## Generic Parameters

####  <a id="typeparam-T"></a>T
####  <a id="typeparam-L"></a>L: [IBufferDataLayout](../interfaces/ibufferdatalayout-017b/index) = [DefaultDataLayout](../types/defaultdatalayout-07b/index)

## Fields

####  <a id="decl-kind"></a>[kind]() : [DescriptorKind](../types/descriptorkind-0a/index) = [DescriptorKind](../types/descriptorkind-0a/index)\.[Buffer](../types/descriptorkind-0a/index#decl-Buffer)

## Methods

* [init](../init)

## Conditional Conformances

### Conformance to \_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>
`ConstantBuffer<T, L>` additionally conforms to `\_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>` when the following conditions are met:

  * [L](index#typeparam-L) : [IBufferDataLayout](../interfaces/ibufferdatalayout-017b/index)

```{toctree}
:titlesonly:
:hidden:

Handle <handle-0>
init <init>
kind <kind>
```
