# Conceptual Aside (Syntax Parsers, Execution Contexts, and Lexical Environments)

## Syntax Parser

> A program that reads your code and determines what it does and if its grammar is valid

- Your code isn't magic. Someone else wrote a program to translate it for the computer.
- translate
  - interpreter
  - compiler
- Your code -> extar Stuff -> Computer Instructions

## Lexical Environment

> Where something sites physically in the code you write

- Lexical means having to do with words or grammar. A lexical environment exists in programming languages in which **where** you wrote something is important.

## Execution context

> A wrapper to help manage the code that is running

- There are lots of lexical environments. Which one is currently running is managed via execution contexts. It can contain things beyond what you've written in your code.
