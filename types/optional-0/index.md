---
layout: stdlib-reference
---

# struct Optional\<T\>

## Description

<span class='code'><a href="index.md" class="code_type">Optional</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;</span> is a type with one extra value than <span class='code'><a href="index.md#typeparam-T" class="code_type">T</a></span>, this extra value is
used to represent a "missing" or "invalid" <span class='code'><a href="index.md#typeparam-T" class="code_type">T</a></span>. This extra value is called
<span class='code'>none</span>.

<span class='code'>none</span> can be compared against with the operators <span class='code'>==</span> or <span class='code'>!=</span>.

An <span class='code'><a href="index.md" class="code_type">Optional</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;</span> value can also be implicitly or explicitly constructed from
a value of type <span class='code'><a href="index.md#typeparam-T" class="code_type">T</a></span>

<span class='code'><a href="index.md" class="code_type">Optional</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;</span> values can be deconstructed with <span class='code'>if(let myT=myOptionalT)...</span>
where this branch will only be taken if <span class='code'>myOptionalT</span> contains a value
of type <span class='code'><a href="index.md#typeparam-T" class="code_type">T</a></span> (to be put into scope as <span class='code'>myT</span>).


## Generic Parameters

####  <a id="typeparam-T"></a>T

## Properties

####  <a id="decl-hasValue"></a>[hasValue](hasvalue-3.md)
Return <span class='code'>true</span> iff this <span class='code'><a href="index.md" class="code_type">Optional</a></span> contains a value of type <span class='code'><a href="index.md#typeparam-T" class="code_type">T</a></span>

####  <a id="decl-value"></a>[value](value.md)
If this <span class='code'><a href="index.md" class="code_type">Optional</a></span> contains a value of type <span class='code'><a href="index.md#typeparam-T" class="code_type">T</a></span> return that.


## Methods

* [init](init.md)


```{toctree}
:titlesonly:
:hidden:

hasValue <../types/optional-0/hasvalue-3>
init <../types/optional-0/init>
value <../types/optional-0/value>
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
