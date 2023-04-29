---
title: Introduction
---

# Introduction

Tree-sitter is a parser generator tool and an incremental parsing library. It can build a concrete syntax tree for a source file and efficiently update the syntax tree as the source file is edited. Tree-sitter aims to be:

* **General** enough to parse any programming language
* **Fast** enough to parse on every keystroke in a text editor
* **Robust** enough to provide useful results even in the presence of syntax errors
* **Dependency-free** so that the runtime library (which is written in pure [C](https://github.com/tree-sitter/tree-sitter/tree/master/lib)) can be embedded in any application

### Language Bindings

There are currently bindings that allow Tree-sitter to be used from the following languages:

* [Go](https://github.com/smacker/go-tree-sitter)
* [Haskell](https://github.com/tree-sitter/haskell-tree-sitter)
* [JavaScript (Node.js)](https://github.com/tree-sitter/node-tree-sitter)
* [JavaScript (Wasm)](https://github.com/tree-sitter/tree-sitter/tree/master/lib/binding_web)
* [Lua](https://github.com/euclidianAce/ltreesitter)
* [OCaml](https://github.com/returntocorp/ocaml-tree-sitter-core)
* [Perl](https://metacpan.org/pod/Text::Treesitter)
* [Python](https://github.com/tree-sitter/py-tree-sitter)
* [Ruby](https://github.com/tree-sitter/ruby-tree-sitter)
* [Ruby](https://github.com/calicoday/ruby-tree-sitter-ffi)
* [Rust](https://github.com/tree-sitter/tree-sitter/tree/master/lib/binding_rust)
* [Swift](https://github.com/ChimeHQ/SwiftTreeSitter)
* [Kotlin](https://github.com/oxisto/kotlintree)
* [Java](https://github.com/serenadeai/java-tree-sitter)

### Parsers

* [Ada](https://github.com/briot/tree-sitter-ada)
* [Agda](https://github.com/tree-sitter/tree-sitter-agda)
* [Apex](https://github.com/aheber/tree-sitter-sfapex)
* [Bash](https://github.com/tree-sitter/tree-sitter-bash)
* [Beancount](https://github.com/zwpaper/tree-sitter-beancount)
* [Cap'n Proto](https://github.com/amaanq/tree-sitter-capnp)
* [C](https://github.com/tree-sitter/tree-sitter-c)
* [C++](https://github.com/tree-sitter/tree-sitter-cpp)
* [C#](https://github.com/tree-sitter/tree-sitter-c-sharp)
* [Clojure](https://github.com/sogaiu/tree-sitter-clojure)
* [CMake](https://github.com/uyha/tree-sitter-cmake)
* [Comment](https://github.com/stsewd/tree-sitter-comment)
* [Common Lisp](https://github.com/theHamsta/tree-sitter-commonlisp)
* [CSS](https://github.com/tree-sitter/tree-sitter-css)
* [CUDA](https://github.com/theHamsta/tree-sitter-cuda)
* [Dart](https://github.com/UserNobody14/tree-sitter-dart)
* [D](https://github.com/gdamore/tree-sitter-d)
* [Dockerfile](https://github.com/camdencheek/tree-sitter-dockerfile)
* [DOT](https://github.com/rydesun/tree-sitter-dot)
* [Elixir](https://github.com/elixir-lang/tree-sitter-elixir)
* [Elm](https://github.com/elm-tooling/tree-sitter-elm)
* [Emacs Lisp](https://github.com/Wilfred/tree-sitter-elisp)
* [Eno](https://github.com/eno-lang/tree-sitter-eno)
* [ERB / EJS](https://github.com/tree-sitter/tree-sitter-embedded-template)
* [Erlang](https://github.com/WhatsApp/tree-sitter-erlang/)
* [Fennel](https://github.com/travonted/tree-sitter-fennel)
* [Fish](https://github.com/ram02z/tree-sitter-fish)
* [Formula](https://github.com/siraben/tree-sitter-formula)
* [Fortran](https://github.com/stadelmanma/tree-sitter-fortran)
* [gitattributes](https://github.com/ObserverOfTime/tree-sitter-gitattributes)
* [gitignore](https://github.com/shunsambongi/tree-sitter-gitignore)
* [Gleam](https://github.com/gleam-lang/tree-sitter-gleam)
* [GLSL (OpenGL Shading Language)](https://github.com/theHamsta/tree-sitter-glsl)
* [Go](https://github.com/tree-sitter/tree-sitter-go)
* [Go mod](https://github.com/camdencheek/tree-sitter-go-mod)
* [Go work](https://github.com/omertuc/tree-sitter-go-work)
* [Graphql](https://github.com/bkegley/tree-sitter-graphql)
* [Hack](https://github.com/slackhq/tree-sitter-hack)
* [Haskell](https://github.com/tree-sitter/tree-sitter-haskell)
* [HCL](https://github.com/MichaHoffmann/tree-sitter-hcl)
* [HTML](https://github.com/tree-sitter/tree-sitter-html)
* [Java](https://github.com/tree-sitter/tree-sitter-java)
* [JavaScript](https://github.com/tree-sitter/tree-sitter-javascript)
* [jq](https://github.com/flurie/tree-sitter-jq)
* [JSON5](https://github.com/Joakker/tree-sitter-json5)
* [JSON](https://github.com/tree-sitter/tree-sitter-json)
* [Julia](https://github.com/tree-sitter/tree-sitter-julia)
* [Kotlin](https://github.com/fwcd/tree-sitter-kotlin)
* [LALRPOP](https://github.com/traxys/tree-sitter-lalrpop)
* [Latex](https://github.com/latex-lsp/tree-sitter-latex)
* [Lean](https://github.com/Julian/tree-sitter-lean)
* [LLVM](https://github.com/benwilliamgraham/tree-sitter-llvm)
* [LLVM MachineIR](https://github.com/Flakebi/tree-sitter-llvm-mir)
* [LLVM TableGen](https://github.com/Flakebi/tree-sitter-tablegen)
* [Lua](https://github.com/Azganoth/tree-sitter-lua)
* [Make](https://github.com/alemuller/tree-sitter-make)
* [Markdown](https://github.com/ikatyang/tree-sitter-markdown)
* [Markdown](https://github.com/MDeiml/tree-sitter-markdown)
* [Meson](https://github.com/Decodetalkers/tree-sitter-meson)
* [Meson](https://github.com/staysail/tree-sitter-meson)
* [Motorola 68000 Assembly](https://github.com/grahambates/tree-sitter-m68k)
* [Nix](https://github.com/cstrahan/tree-sitter-nix)
* [Objective-C](https://github.com/jiyee/tree-sitter-objc)
* [OCaml](https://github.com/tree-sitter/tree-sitter-ocaml)
* [Org](https://github.com/milisims/tree-sitter-org)
* [Pascal](https://github.com/Isopod/tree-sitter-pascal)
* [Perl](https://github.com/ganezdragon/tree-sitter-perl)
* [Perl](https://github.com/tree-sitter-perl/tree-sitter-perl)
* [Perl POD](https://github.com/tree-sitter-perl/tree-sitter-pod)
* [PHP](https://github.com/tree-sitter/tree-sitter-php)
* [Portable Game Notation](https://github.com/rolandwalker/tree-sitter-pgn)
* [PowerShell](https://github.com/PowerShell/tree-sitter-PowerShell)
* [Protocol Buffers](https://github.com/mitchellh/tree-sitter-proto)
* [Python](https://github.com/tree-sitter/tree-sitter-python)
* [QML](https://github.com/yuja/tree-sitter-qmljs)
* [Racket](https://github.com/6cdh/tree-sitter-racket)
* [Rasi](https://github.com/Fymyte/tree-sitter-rasi)
* [re2c](https://github.com/alemuller/tree-sitter-re2c)
* [Regex](https://github.com/tree-sitter/tree-sitter-regex)
* [Rego](https://github.com/FallenAngel97/tree-sitter-rego)
* [reStructuredText](https://github.com/stsewd/tree-sitter-rst)
* [R](https://github.com/r-lib/tree-sitter-r)
* [Ruby](https://github.com/tree-sitter/tree-sitter-ruby)
* [Rust](https://github.com/tree-sitter/tree-sitter-rust)
* [Scala](https://github.com/tree-sitter/tree-sitter-scala)
* [Scheme](https://github.com/6cdh/tree-sitter-scheme)
* [Scss](https://github.com/serenadeai/tree-sitter-scss)
* [S-expressions](https://github.com/AbstractMachinesLab/tree-sitter-sexp)
* [Smali](https://github.com/amaanq/tree-sitter-smali)
* [Smali](https://git.sr.ht/~yotam/tree-sitter-smali)
* [Sourcepawn](https://github.com/nilshelmig/tree-sitter-sourcepawn)
* [SPARQL](https://github.com/BonaBeavis/tree-sitter-sparql)
* [SQL - BigQuery](https://github.com/takegue/tree-sitter-sql-bigquery)
* [SQL - PostgreSQL](https://github.com/m-novikov/tree-sitter-sql)
* [SQL - SQLite](https://github.com/dhcmrlchtdj/tree-sitter-sqlite)
* [SSH](https://github.com/metio/tree-sitter-ssh-client-config)
* [Svelte](https://github.com/Himujjal/tree-sitter-svelte)
* [Swift](https://github.com/alex-pinkus/tree-sitter-swift)
* [SystemRDL](https://github.com/SystemRDL/tree-sitter-systemrdl)
* [Thrift](https://github.com/duskmoon314/tree-sitter-thrift)
* [TOML](https://github.com/ikatyang/tree-sitter-toml)
* [Tree-sitter Query](https://github.com/nvim-treesitter/tree-sitter-query)
* [Turtle](https://github.com/BonaBeavis/tree-sitter-turtle)
* [Twig](https://github.com/gbprod/tree-sitter-twig)
* [TypeScript](https://github.com/tree-sitter/tree-sitter-typescript)
* [Verilog](https://github.com/tree-sitter/tree-sitter-verilog)
* [VHDL](https://github.com/alemuller/tree-sitter-vhdl)
* [Vue](https://github.com/ikatyang/tree-sitter-vue)
* [WASM](https://github.com/wasm-lsp/tree-sitter-wasm)
* [WGSL WebGPU Shading Language](https://github.com/mehmetoguzderin/tree-sitter-wgsl)
* [YAML](https://github.com/ikatyang/tree-sitter-yaml)
* [YANG](https://github.com/Hubro/tree-sitter-yang)
* [Zig](https://github.com/maxxnino/tree-sitter-zig)

### Talks on Tree-sitter

* [Strange Loop 2018](https://www.thestrangeloop.com/2018/tree-sitter---a-new-parsing-system-for-programming-tools.html)
* [FOSDEM 2018](https://www.youtube.com/watch?v=0CGzC_iss-8)
* [GitHub Universe 2017](https://www.youtube.com/watch?v=a1rC79DHpmY)

### Underlying Research

The design of Tree-sitter was greatly influenced by the following research papers:

- [Practical Algorithms for Incremental Software Development Environments](https://www2.eecs.berkeley.edu/Pubs/TechRpts/1997/CSD-97-946.pdf)
- [Context Aware Scanning for Parsing Extensible Languages](https://www-users.cse.umn.edu/~evw/pubs/vanwyk07gpce/vanwyk07gpce.pdf)
- [Efficient and Flexible Incremental Parsing](http://harmonia.cs.berkeley.edu/papers/twagner-parsing.pdf)
- [Incremental Analysis of Real Programming Languages](http://harmonia.cs.berkeley.edu/papers/twagner-glr.pdf)
- [Error Detection and Recovery in LR Parsers](http://what-when-how.com/compiler-writing/bottom-up-parsing-compiler-writing-part-13)
- [Error Recovery for LR Parsers](https://apps.dtic.mil/sti/pdfs/ADA043470.pdf)