---
layout: stdlib-reference
---

# updatePair

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="updatepair-6">updatePair</a>&lt;<a href="updatepair-6#typeparam-T" class="code_type">T</a>&gt;(
    <span class="code_keyword">inout</span> <a href="../types/differentialpair-0c/index" class="code_type">DifferentialPair</a>&lt;<a href="updatepair-6#typeparam-T" class="code_type">T</a>&gt; <a href="updatepair-6#decl-p" class="code_param">p</a>,
    <a href="updatepair-6#typeparam-T" class="code_type">T</a> <a href="updatepair-6#decl-newPrimal" class="code_param">newPrimal</a>,
    <a href="updatepair-6#typeparam-T" class="code_type">T</a>.Differential <a href="updatepair-6#decl-newDiff" class="code_param">newDiff</a>)
    <span class='code_keyword'>where</span> <a href="updatepair-6#typeparam-T" class="code_type">T</a> : <a href="../interfaces/idifferentiable-01/index" class="code_type">IDifferentiable</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [IDifferentiable](../interfaces/idifferentiable-01/index)

## Parameters

####  <a id="decl-p"></a>p  : [DifferentialPair](../types/differentialpair-0c/index)\<[T](../types/differentialpair-0c/index#typeparam-T)\>
####  <a id="decl-newPrimal"></a>newPrimal  : [T](updatepair-6#typeparam-T)
####  <a id="decl-newDiff"></a>newDiff  : [T](updatepair-6#typeparam-T)\.Differential

