# Lisp Interpreter in C
This is a minimal Lisp interpreter built from scratch in C as part of a self-guided learning project, following the book [*Build Your Own Lisp*](https://www.buildyourownlisp.com/) by Daniel Holden.
The project provides a fully working REPL (Read-Eval-Print Loop) that parses and evaluates simple Lisp expressions with a hand-written parser and evaluation engine.

---

## Features

- Interactive Lisp REPL  
- Prefix-notation syntax familiar to traditional Lisps  

---

## Project Structure

| File / Folder | Purpose                                   |
| ------------- | ----------------------------------------- |
| `lispy.c`     | Core REPL and interpreter logic           |
| `mpc.c`       | Parser combinator library (`mpc`)         |
| `mpc.h`       | Header for the parser combinator library  |

---

## Build & Run

```bash
# Compile
gcc -std=c99 -Wall -g lispy.c mpc.c -o lisp

# Launch the REPL
./lisp

# Example Run
lispy> (* 2 (- 5 3))
4

---


