# A tour of Julia, exam template repository

[![Stable](https://img.shields.io/badge/docs-stable-blue.svg)](https://stefanocampanella.github.io/TourOfJuliaExamTemplate.jl/stable/)
[![Dev](https://img.shields.io/badge/docs-dev-blue.svg)](https://stefanocampanella.github.io/TourOfJuliaExamTemplate.jl/dev/)
[![Build Status](https://github.com/fspacheco/TourOfJuliaExercises/actions/workflows/CI.yml/badge.svg?branch=main)](https://github.com/fspacheco/TourOfJuliaExercises/actions/workflows/CI.yml?query=branch%3Amain)

Use this template and edit the source code to implement the functions `problem_1`, `problem_2`, ..., `problem_10`, which should return the solution of the first ten problems listed on [Project Euler](https://projecteuler.net). Use the most idiomatic Julia you can; you are encouraged to show-off all the features you like!

The solutions will be checked using CI via GitHub actions. You can also document your code using docstrings; the documentation will be generated automatically.

# How to activate

Open `julia`, then change to package mode with `]` and `activate .`

One can also write code inside a Pluto environment with `import Pluto; Pluto.run()`

# To run the tests

In the package mode `]`, run `test`
