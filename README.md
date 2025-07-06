# Lisp-Interpretor
This is a minimal Lisp interpreter built from scratch in C as part of a self-guided learning project, following the book Build Your Own Lisp by Daniel Holden.
The project includes a fully working REPL (Read-Eval-Print Loop) that can parse and evaluate simple Lisp expressions using a hand-written parser and evaluation engine.

🚀 Features
Interactive Lisp REPL
Custom syntax inspired by traditional Lisp (prefix notation)

📁 Project Structure
lispy.c – Core REPL and interpreter logic
mpc.c and mpc.h – Parser combinator library

🛠️ Build & Run
To compile the interpreter, run:

bash:
gcc -std=c99 -Wall -g main.c mpc.c -o lisp
./lisp

Once running:
lispy> (+ 1 2 3)
6
lispy> (* 2 (- 5 3))
4
