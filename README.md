# BankAccount-DCI v0.1.0
[![Build Status](https://travis-ci.org/kt3k/BankAccount-DCI.png)](https://travis-ci.org/kt3k/BankAccount-DCI) [![Coverage Status](https://coveralls.io/repos/kt3k/BankAccount-DCI/badge.png)](https://coveralls.io/r/kt3k/BankAccount-DCI)

BankAccount DCI example in Java

This example implements the roles as the adapters of the models to the contexts. And it doesn't use traits or method injections.

good points:
- easy to implement.
- easy to understand.
- Any IDE understand this implementation.
- No special framework or language feature is needed. Just plain code.
- Any language can implement this.
- No performance issues of method injection.

disadvantages:
- Less reusable roles.
