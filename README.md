# IODyn: A functional language for implicitly-incremental programs with dynamic input and output collections [![Travis](https://api.travis-ci.org/cuplv/iodyn-lang.rust.svg?branch=master)](https://travis-ci.org/cuplv/iodyn-lang.rust)

## IODyn programs are ML programs

IODyn is a functional language, in the ML family of languages (SML, OCaml, Elm, etc.).  
As with other MLs, IODyn consists of a typed core calculus, with (higher-order) functions and persistent algebraic data types.  

## IODyn programs transform collections

IODyn programs in this core calculus operate over a collections library of sequences, sets, finite maps and graphs (in progress).

## IODyn programs implicitly compute incrementally

We give well-typed, well-annotated IODyn programs an implicitly-incremental semantics, via translation to [Fungi](https://github.com/Adapton/fungi-lang.rust), our low-level core calculus for functional programs that name their own cached dependency graphs.

### (Status:)

 - We have implemented the AST structure, concrete syntax (via Rust macros for now) and basic type system.
 - We have begun the translation to Fungi, but are currently focusing on implementing Fungi before proceeding further with the translation.

