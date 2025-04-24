---
layout: stdlib-reference
---

# struct DifferentialPair\<T\>

*Conforms to:* [IDifferentiable](../../interfaces/idifferentiable-01/index.html)

## Description

<span class='code'><a href="index.html" class="code_type">DifferentialPair</a>&lt;<a href="index.html#typeparam-T" class="code_type">T</a>&gt;</span> is a built-in type that carries both the original and derivative value of a term.
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

Differential pairs can be created via constructor or through the <span class='code'><a href="../../global-decls/diffpair-4.html">diffPair</a>()</span> operation
```csharp
DifferentialPair<float> dpa = DifferentialPair<float>(1.0f, 2.0f);
DifferentialPair<float> dpa = diffPair(1.0f, 2.0f);
```
Note that derivative pairs are used to pass derivatives into and out of auto-diff functions.
See documentation on <span class='code'>fwd_diff</span> and <span class='code'>bwd_diff</span> operators for more information.


## Generic Parameters

####  <a id="typeparam-T"></a>T: [IDifferentiable](../../interfaces/idifferentiable-01/index.html)

## Properties

####  <a id="decl-d"></a>[d](d.html)
####  <a id="decl-p"></a>[p](p.html)
####  <a id="decl-v"></a>[v](v.html)

## Methods

* [init](init.html)
* [getDifferential](getdifferential-3.html)
* [getPrimal](getprimal-3.html)
* [dzero](dzero.html)
* [dadd](dadd.html)
* [dmul](dmul.html)


```{toctree}
:titlesonly:
:hidden:

Differential <differential-0>
DifferentialElementType <differentialelementtype-0cj>
d <d>
dadd <dadd>
dmul <dmul>
dzero <dzero>
getDifferential <getdifferential-3>
getPrimal <getprimal-3>
init <init>
p <p>
v <v>
```
