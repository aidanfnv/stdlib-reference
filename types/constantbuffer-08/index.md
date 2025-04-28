---
layout: stdlib-reference
---

# struct ConstantBuffer\<T, L\>

*Conditionally conforms to:* \_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>

## Generic Parameters

####  <a id="typeparam-T"></a>T
####  <a id="typeparam-L"></a>L: [IBufferDataLayout](../../../interfaces/ibufferdatalayout-017b/index.html) = [DefaultDataLayout](../../defaultdatalayout-07b/index.html)

## Fields

####  <a id="decl-kind"></a>[kind](../kind.html) : [DescriptorKind](../../descriptorkind-0a/index.html) = [DescriptorKind](../../descriptorkind-0a/index.html)\.[Buffer](../../descriptorkind-0a/index.html#decl-Buffer)

## Methods

* [init](../init.html)

## Conditional Conformances

### Conformance to \_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>
`ConstantBuffer<T, L>` additionally conforms to `\_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>` when the following conditions are met:

  * [L](.html#typeparam-L) : [IBufferDataLayout](../../../interfaces/ibufferdatalayout-017b/index.html)

```{toctree}
:titlesonly:
:hidden:

Handle <handle-0>
init <init>
kind <kind>
```
