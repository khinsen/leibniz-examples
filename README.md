![Leibniz logo](https://github.com/khinsen/leibniz/raw/master/logo/horizontal-leibniz-logo-500-x-150-png.png)

[Leibniz](https://github.com/khinsen/leibniz) is a digital scientific notation under development. It should be considered experimental at this point.

This repository contains example documents that use Leibniz. These documents are meant to illustrate what a digital scientific notation looks like, and how it can be used.

All content in this repository is published under the [Creative Commons Attribution](https://creativecommons.org/licenses/by/4.0/) licence.

## Quick guide to Leibniz

In the Leibniz documents, computationally relevant definitions and rules are shown on a blue background. Computed content is shown on a green background.

For reading the formulas, the main feature to keep in mind is that Leibniz has no operator precedence rules. For infix operators such as + or ×, the right-hand argument is everything to the right of the operator. For example, 2 × 3 + 4 means 2 × (3 + 4), not (2 × 3) + 4 as in traditional mathematical notation.

An important distinction in Leibniz that is often neglected in traditional mathematical notation is the one between values and variables. For example, a time *value* t refers to a specific moment in time, whereas a time *variable* t stands for an *arbitrary* time value. In Leibniz, variables are typeset in italics.

Each example also contains a link to an XML version, which contains just the definitions and rules. It is meant to be processed by software. There is also a link to the source code, which is written in an extension of the [Scribble](https://docs.racket-lang.org/scribble/index.html) language, which is the documentation language of the [Racket](http://racket-lang.org/) software ecosystem.


## List of examples

 - [Heron's algorithm](examples/heron.html) for computing square roots ([XML](examples/heron.xml), [source code](https://github.com/khinsen/leibniz-examples/blob/master/examples/heron.rkt))
 - [Masses and mass units](examples/masses.html) ([XML](examples/masses.xml), [source code](https://github.com/khinsen/leibniz-examples/blob/master/examples/masses.rkt))
