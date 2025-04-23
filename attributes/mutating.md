---
layout: stdlib-reference
---

# attribute [mutating]

## Description

Mark a function or a property or subscript accessor as mutating. A mutating function receives the implicit <span class='code'>this</span> parameter
as an <span class='code'><span class="code_keyword">inout</span></span> parameter, so that mutations to members access from <span class='code'>this</span> argument will be visible to the caller.


## Signature

<pre>
[<a href="mutating.md">mutating</a>]
</pre>

## Remarks


By default, Slang treats all member functions as non-mutating. For example, consider the following function:
```csharp
struct S
{
   int x;
   void foo()
   {
      x = 1; // error: `x` is not an l-value.
   }
}

```
The line <span class='code'>x=1</span> will lead to a compile time error because by-default, all member methods in Slang are non-mutating. To
allow <span class='code'>foo</span> to modify <span class='code'>x</span>, you can use <span class='code'>[<a href="mutating.md">mutating</a>]</span> to mark the function as such:
```csharp
struct S
{
   int x;
   [mutating]
   void foo()
   {
      x = 1; // ok
   }
}
```

## See also

<span class='code'>[<a href="nonmutating.md">nonmutating</a>]</span>.



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
