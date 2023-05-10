# refined1

***Fork of [nikita-volkov/refined](https://github.com/nikita-volkov/refined)
with minimal changes. Hopefully temporary.***

In type theory, a refinement type is a type endowed
with a predicate which is assumed to hold for any element
of the refined type.

This library allows one to capture the idea of a refinement type
using the `Refined` type. A `Refined` `p` `x` wraps a value
of type `x`, ensuring that it satisfies a type-level predicate `p`.

A simple introduction to this library can be found here: http://nikita-volkov.github.io/refined/
