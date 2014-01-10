# BankAccount-DCI v0.1.0
[![Build Status](https://travis-ci.org/kt3k/BankAccount-DCI.png)](https://travis-ci.org/kt3k/BankAccount-DCI) [![Coverage Status](https://coveralls.io/repos/kt3k/BankAccount-DCI/badge.png)](https://coveralls.io/r/kt3k/BankAccount-DCI)

BankAccount DCI example in Java

This example implements the roles as the adapters of the domain models to the contexts, not using trait nor method injections.

Good aspects:
- easy to implement.
- easy to understand.
- Any IDE understand this implementation.
- No special framework or language feature is needed. Just plain code.
- Any language can implement this.
- No performance issues of method injection.

Poor aspects:
- Less reusable roles.
