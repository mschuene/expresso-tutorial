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


## License

Copyright © 2013 FIXME

Distributed under the Eclipse Public License, the same as Clojure.
