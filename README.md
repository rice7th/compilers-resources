# compilers-resources
A list of compiler (mostly) and programming language related resources

## Index
- [General](#general)
  - [Books](#books)
- [Frontend](#frontend)
  - [Lexers](#lexers)
  - [Parsers](#parsers)
  - [Type Systems](#type-systems)
- [Backend](#backend)
    - [IRs](#irs)
    - [Optimizations](#optimizations)
    - [Analysis](#analysis)
    - [Assemblers](#assemblers)
    - [Linkers](#linkers)
- [Misc](#misc)
    - [Runtime](#runtime)
    - [JIT](#jit)
    - [Loaders](#loaders)
    - [Dynamic Linking](#dynamic-linking)
    - [See Also](#see-also)


# General
## Books
[Crafting Interpreters](https://craftinginterpreters.com/) - Awesome guide that covers lexing, parsing, compiling the ast to bytecode, garbage collection and a bit of optimization.
Extremely useful resource even if it is centered around interpreters.

[Compilers, Principles, Techniques and Tools (2nd Edition) (also known as The Dragon's Book)](https://github.com/qshadun/books/blob/master/Compilers%20Principles%20Techniques%20and%20Tools%20(2nd%20Edition)%20.pdf) - One of the most popular books
ever about compiler design. It covers almost every possible area there is, from the frontend to the backend.

[Acwj](https://github.com/DoctorWkt/acwj) - A compiler writing journey. A step-to-step introduction to compiler design.

# Frontend
## Lexers
## Parsers
## Type systems

# Backend
## IRs
### Sea of Nodes
https://darksi.de/d.sea-of-nodes/

https://github.com/SeaOfNodes/Simple

#### Implementations
[v8](https://github.com/v8/v8/blob/main/src/compiler/turbofan-graph.h) (not sure if this is the right file)

[LibFirm](https://github.com/libfirm/libfirm/tree/master/ir/ir)

### RVSDG
[RVSDG's paper](https://arxiv.org/pdf/1912.05036)
#### Implementations
[JLM](https://github.com/phate/jlm) - RVSDG's reference implementation.

[Rain](https://gitlab.com/old-rain-lang/rain-ir) - An RVSDG implementation in Rust

[Optir](https://github.com/jameysharp/optir) - An attempt to combine RVSDG and Equivalence graphs

## Optimizations

[Mem2Reg under the hood](https://longfangsong.github.io/en/mem2reg-made-simple/) - Explains more indepth about mem2reg

## Analysis
### Liveness analysis
https://www.cl.cam.ac.uk/teaching/1718/OptComp/slides/lecture03.pdf

https://www.inf.ed.ac.uk/teaching/courses/ct/17-18/slides/llvm-4-liveness.pdf

https://klasses.cs.uchicago.edu/archive/2004/spring/22620-1/docs/liveness.pdf

## Assemblers

[X86 WinFastCall Reference](https://andreaspk.github.io/posts/2019-02-16-Windows%20Calling%20Convention.html) - A reference for the x86 Windows Fastcall Calling Convention
[Wasm instruction Reference](https://developer.mozilla.org/en-US/docs/WebAssembly/Reference) - Reference of wasm instructions and their encoding

## Linkers

# Misc
## JIT
## Runtime
## Loaders
## Dynamic Linking
## See also
[Qbe's Bib](https://c9x.me/compile/bib)

[Max Bernstein's PL-Resources](https://bernsteinbear.com/pl-resources/)
