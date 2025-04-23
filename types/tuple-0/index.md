---
layout: stdlib-reference
---

# struct Tuple\<each T\>

*Conditionally conforms to:* [IComparable](../../interfaces/icomparable-01/index.html), [IDifferentiable](../../interfaces/idifferentiable-01/index.html)

## Description

A variadic generic storing the product of several types.

The member names of individual values are <span class='code'>_0</span>, <span class='code'>_1</span>, <span class='code'>_2</span>, ...

New tuples can also be constructed by swizzling an existing tuple with the
concatenation of these names, for example <span class='code'>x._2_1_0</span> will return the first
three members of the tuple <span class='code'>x</span> in reverse order.

When all tuple elements conform to <span class='code'><a href="../../interfaces/icomparable-01/index.html" class="code_type">IComparable</a></span> tuples can themselves be
compared according to a lexicographic ordering.

The number of elements in a tuple is given by the <span class='code'>countof</span> function.


## Generic Parameters

####  <a id="typeparam-T"></a>T

## Methods

* [init](init.html)
* [lessThan](lessthan-4.html)
* [lessThanOrEquals](lessthanorequals-48a.html)
* [equals](equals.html)
* [dzero](dzero.html)
* [dadd](dadd.html)
* [dmul](dmul.html)

## Conditional Conformances

### Conformance to IComparable
`Tuple<each T>` additionally conforms to `IComparable` when the following conditions are met:

  * [T](index.html#typeparam-T) : [IComparable](../../interfaces/icomparable-01/index.html)
### Conformance to IDifferentiable
`Tuple<each T>` additionally conforms to `IDifferentiable` when the following conditions are met:

  * [T](index.html#typeparam-T) : [IDifferentiable](../../interfaces/idifferentiable-01/index.html)

```{toctree}
:titlesonly:
:hidden:

Differential <../types/tuple-0/differential-0>
dadd <../types/tuple-0/dadd>
dmul <../types/tuple-0/dmul>
dzero <../types/tuple-0/dzero>
equals <../types/tuple-0/equals>
init <../types/tuple-0/init>
lessThan <../types/tuple-0/lessthan-4>
lessThanOrEquals <../types/tuple-0/lessthanorequals-48a>
```
