# BankAccount-DCI v0.1.0
[![Build Status](https://travis-ci.org/kt3k/BankAccount-DCI.png)](https://travis-ci.org/kt3k/BankAccount-DCI) [![Coverage Status](https://coveralls.io/repos/kt3k/BankAccount-DCI/badge.png)](https://coveralls.io/r/kt3k/BankAccount-DCI)

BankAccount DCI example in Java

This example implements the roles of DCI as adapters (wrappers) of the models to the contexts. And it doesn't use traits or method injections. It's just plain java code.

This exmaple is easy to understand and easy to implement, I think. And any IDE can understand this implementation.
It uses no special framework or special language feature. Just plain code.
And has no performance issues about method injections.

A Disadvantage of this example is less reusable roles, I think. A role belongs to its context and not applicable to other contexts.

But one of the main goals of DCI is to separate the interactive behaviours from the model behaviours. And role's unreusability is not so much problem for attaining it.
