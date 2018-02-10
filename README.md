# IODyn: A functional language for implicitly-incremental programs with dynamic input and output collections [![Travis](https://api.travis-ci.org/cuplv/iodyn-lang.rust.svg?branch=master)](https://travis-ci.org/cuplv/iodyn-lang.rust)

## IODyn is an ML-like language with collections

IODyn is a functional language, in the ML family of languages (SML, OCaml, Elm, etc.).  As with other languages in this family, IODyn consists of a typed core calculus, with functions and algebraic data types.  Further, we enrich this core calculus with a collections library over sequences, sets, finite maps and graphs (in progress).  Finally, we give well-typed, well-annotated programs in this language an implicitly-incremental semantics, via translation to Fungi, our low-level core calculus for functional programs that name their own cached dependency graphs.

### (Status:)

 - We have implemented the AST structure, concrete syntax (via Rust macros for now) and basic type system.
 - We have begun the translation to Fungi, but are currently focusing on implementing Fungi before proceeding further with the translation.

