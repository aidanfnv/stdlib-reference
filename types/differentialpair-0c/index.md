---
layout: stdlib-reference
---

# struct DifferentialPair\<T\>

*Conforms to:* [IDifferentiable](../../interfaces/idifferentiable-01/index.md)

## Description

<span class='code'><a href="index.md" class="code_type">DifferentialPair</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;</span> is a built-in type that carries both the original and derivative value of a term.
It is defined as follows:
```csharp
struct DifferentialPair<T : IDifferentiable> : IDifferentiable
{
    typealias Differential = DifferentialPair<T.Differential>;
    property T p {get;}
    property T.Differential d {get;}
    static Differential dzero();
    static Differential dadd(Differential a, Differential b);
}
```

Differential pairs can be created via constructor or through the <span class='code'><a href="../../global-decls/diffpair-4.md">diffPair</a>()</span> operation
```csharp
DifferentialPair<float> dpa = DifferentialPair<float>(1.0f, 2.0f);
DifferentialPair<float> dpa = diffPair(1.0f, 2.0f);
```
Note that derivative pairs are used to pass derivatives into and out of auto-diff functions.
See documentation on <span class='code'>fwd_diff</span> and <span class='code'>bwd_diff</span> operators for more information.


## Generic Parameters

####  <a id="typeparam-T"></a>T: [IDifferentiable](../../interfaces/idifferentiable-01/index.md)

## Properties

####  <a id="decl-d"></a>[d](d.md)
####  <a id="decl-p"></a>[p](p.md)
####  <a id="decl-v"></a>[v](v.md)

## Methods

* [init](init.md)
* [getDifferential](getdifferential-3.md)
* [getPrimal](getprimal-3.md)
* [dzero](dzero.md)
* [dadd](dadd.md)
* [dmul](dmul.md)


```{toctree}
:titlesonly:
:hidden:

Differential <../types/differentialpair-0c/differential-0>
DifferentialElementType <../types/differentialpair-0c/differentialelementtype-0cj>
d <../types/differentialpair-0c/d>
dadd <../types/differentialpair-0c/dadd>
dmul <../types/differentialpair-0c/dmul>
dzero <../types/differentialpair-0c/dzero>
getDifferential <../types/differentialpair-0c/getdifferential-3>
getPrimal <../types/differentialpair-0c/getprimal-3>
init <../types/differentialpair-0c/init>
p <../types/differentialpair-0c/p>
v <../types/differentialpair-0c/v>
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
