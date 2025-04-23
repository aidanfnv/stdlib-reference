---
layout: stdlib-reference
---

# String\.init

## Description





## Signature 

<pre>
<a href="index.md" class="code_type">String</a>.<a href="init.md">init</a>(<span class="code_keyword">int</span> <a href="init.md#decl-val" class="code_param">val</a>);

<a href="index.md" class="code_type">String</a>.<a href="init.md">init</a>(<span class="code_keyword">uint</span> <a href="init.md#decl-val" class="code_param">val</a>);

<a href="index.md" class="code_type">String</a>.<a href="init.md">init</a>(int64_t <a href="init.md#decl-val" class="code_param">val</a>);

<a href="index.md" class="code_type">String</a>.<a href="init.md">init</a>(uint64_t <a href="init.md#decl-val" class="code_param">val</a>);

<a href="index.md" class="code_type">String</a>.<a href="init.md">init</a>(<span class="code_keyword">float</span> <a href="init.md#decl-val" class="code_param">val</a>);

<a href="index.md" class="code_type">String</a>.<a href="init.md">init</a>(<span class="code_keyword">double</span> <a href="init.md#decl-val" class="code_param">val</a>);

<a href="index.md" class="code_type">String</a>.<a href="init.md">init</a>(<a href="../nativestring-06/index.md" class="code_type">NativeString</a> <a href="init.md#decl-value" class="code_param">value</a>);

</pre>

## Parameters

####  <a id="decl-val"></a>val  : int
####  <a id="decl-val"></a>val  : uint
####  <a id="decl-val"></a>val  : int64\_t
####  <a id="decl-val"></a>val  : uint64\_t
####  <a id="decl-val"></a>val  : float
####  <a id="decl-val"></a>val  : double
####  <a id="decl-value"></a>value  : [NativeString](../nativestring-06/index.md)

## Availability and Requirements

Defined for the following targets:

#### cpp
Available in all stages.




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
