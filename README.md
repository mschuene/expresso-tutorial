# Expresso-tutorial
Welcome to the official expresso tutorial.

## What is expresso
[Expresso](https://github.com/clojure-numerics/expresso) is the clojure library
for algebraic manipulation of expressions and symbolic computation I developed
as my Google summer of Code 2013 project.
It builds on top of [core.matrix](https://github.com/clojure-numerics/core.matrix) and [core.logic](https://github.com/clojure/core.logic) and provides a
powerful manipulation framework for algebraic expressions.

## Features
At the end of gsoc, expresso has the following features:
- functions to construct and handle algebraic expressions
- a general rule based translator to succinctly state expression manipulations
- functions to manipulate and simplify algebraic expressions, like
  multiply-out and simplify
- an expression solver which can solve a single equation and set of equations
  for unknowns. The expressions can also contain ndarray input like core.matrix
- an expression optimizer and compiler, which optimizes the expression for
  excecution speed and can compile it to a non-overhead clojure function

## What this tutorial covers
The tutorial is split into multiple section, each contained in its own top level
org file. Each file is itself a literal program and contains working clojure
code. The extracted code can also be found in the src directory.
I highly recommend looking at the example section in 3.1

## Table of contents
   1. Expresso basics
   2. (optional) Advanced expression construction and manipulation
   3. Manipulation of Algebraic Expressions
      1. simplifying and solving expressions
	  2. optimizing and compiling expressions
   4. Rule based semantic Term Rewriting with expresso
   5. Expresso's internals/how it works
   6. Extending expresso

## Getting started
  1. Copy this repo, so you can experiment with the code while reading
  2. Begin reading Expresso's basics
  3. Pick any other section which is of interest



## License

Copyright © 2013 FIXME

Distributed under the Eclipse Public License, the same as Clojure.
