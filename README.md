# Compiler - Lexical Analyzer

## Project Description

This project corresponds to the first stage of a compiler developed for the **Compilers and Interpreters** course at the **Universidad Nacional del Sur**.

The main goal of this stage is to implement a **lexical analyzer** capable of reading source code, identifying and classifying tokens, and reporting lexical errors in a clear and detailed way.

The analyzer was implemented in **Java** using a state-machine-based approach, where each state is responsible for recognizing a specific type of token.

---

## Key Features

- **Token recognition:** identifies keywords, identifiers, literals, operators, and punctuation symbols.
- **Keyword detection:** recognizes reserved words such as `class`, `if`, `else`, `while`, `return`, `public`, `static`, `void`, `int`, `float`, and others.
- **Literal handling:** supports integer, character, string, and floating-point literals.
- **Operator recognition:** supports simple and compound operators such as `+`, `-`, `*`, `/`, `+=`, `-=`, `==`, `!=`, `<=`, `>=`, `&&`, and `||`.
- **Detailed error reporting:** reports the line number, column number, invalid lexeme, and the corresponding source line.
- **Error recovery:** continues analyzing the source code after detecting a lexical error, allowing multiple errors to be reported in a single execution.
- **Modular organization:** separates lexical analysis, token representation, keyword handling, and custom exceptions into independent classes/packages.

---

## Requirements

- Java 8 or higher
- Java compiler (`javac`)

---

## Installation and Execution

### 1. Clone the repository

```bash
git clone https://github.com/candela-ledesma/compiler-lexical-analyzer.git
cd compiler-lexical-analyzer
