# Expresso-tutorial
Welcome to the official expresso tutorial.

## What is Expresso
[Expresso](https://github.com/clojure-numerics/expresso) is the clojure library
for algebraic manipulation of expressions and symbolic computation I developed
as my Google summer of Code 2013 project.
It builds on top of [core.matrix](https://github.com/clojure-numerics/core.matrix) and [core.logic](https://github.com/clojure/core.logic) and provides a
powerful manipulation framework for algebraic expressions.

```clojure
(solve 'blue
  (ex (= pencils (+ green white blue red)))
  (ex (= (/ pencils 10) green))
  (ex (= (/ pencils 2) white))
  (ex (= (/ pencils 4) blue))
  (ex (= red 45))) ;=> #{{blue 75N}}
```

## Features
At the end of gsoc, expresso has the following features:
- functions to construct and handle algebraic expressions
- a general rule based translator to succinctly state expression manipulations
- functions to manipulate and simplify algebraic expressions
- an expression solver which can solve a single equation and set of equations
  for unknowns. The expressions can also contain core.matrix matrix expressions.
- an expression optimizer and compiler, which optimizes the expression for
  excecution speed and can compile it to an efficient clojure function

## What this tutorial covers
The tutorial is split into multiple section, each contained in its own top level
org file. Each file is itself a literal program and contains working clojure
code. The extracted code can also be found in the src directory.
You can find some example of expresso in the section 3.1 featuring solving
word problems and finding roots and extremata of functions.

## Table of contents
   1. [Expresso Basics](https://github.com/mschuene/expresso-tutorial/blob/master/expresso-basics.org)
   2. (optional) [Advanced Expression Construction and Manipulation](https://github.com/mschuene/expresso-tutorial/blob/master/advanced-expression-construction.org)
   3. Manipulation of Algebraic Expressions
      1. [Simplifying and Solving Expressions](https://github.com/mschuene/expresso-tutorial/blob/master/simplifying-and-solving-expressions.org)
	  2. [Optimizing and Compiling Expressions](https://github.com/mschuene/expresso-tutorial/blob/master/optimizing_and_compiling_expressions.org)
   4. [Rule Based Semantic Term Rewriting with Expresso](https://github.com/mschuene/expresso-tutorial/blob/master/rule_based_semantic_term_rewriting_with_expresso.org)
   5. [Expresso's Internals/How it Works](https://github.com/mschuene/expresso-tutorial/blob/master/expresso-internals.org)
   6. [Extending Expresso](https://github.com/mschuene/expresso-tutorial/blob/master/extending-expresso.org)

## Getting started
  1. Copy this repo, so you can experiment with the code while reading
  2. Begin reading Expresso's basics
  3. Pick any other section which is of interest

## License

Copyright © 2013 FIXME

Distributed under the Eclipse Public License, the same as Clojure.
