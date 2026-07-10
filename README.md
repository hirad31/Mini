# Mini

Mini is a simple, beginner-friendly interpreted programming language written in C++.

The goal of Mini is to make programming easy to learn while still providing enough features to create games, automation scripts, utilities, and small applications.

Mini focuses on readability, simplicity, and fun.

---

# Features

## Input

```mini
name = input "Name: "
println Hello name
```

## Conditions

```mini
if x > 5
    println "Big"
elif x == 5
    println "Equal"
else
    println "Small"
endif
```

## Loops

### While

```mini
while x < 10
    println x
    inc x
endwhile
```
### Repeat

```mini
repeat 3 times
    println "Hello!"
endrepeat
```

## Functions

```mini
func hello(name)
    println "Hello" name
endfunc

call hello("Mini")
```

Functions can also return values.

```mini
func add(a,b)
    return a+b
endfunc

println call add(5,7)
```

## Arrays

```mini
numbers = [10,20,30]

println numbers[0]
println numbers[1]
println numbers[2]
```
## Math

```mini
println 2+3*4
println (2+3)*4
println 2^8
println sqrt(25)
```

## Random

```mini
println rand(100)
println randrange(1,10)
```

## File Operations

```mini
file_write "save.txt" "Hello"

println file_read "save.txt"
```

---

# Language Philosophy

Mini is designed to be:

- Easy to learn
- Easy to read
- Lightweight
- Fast
- Beginner friendly
- Great for learning programming
- Great for games
- Great for automation

Mini intentionally avoids unnecessary complexity.

---

# Current Features

- Variables
- Automatic types
- Constants
- Input
- Output
- Arithmetic expressions
- Parentheses
- Operator precedence
- Power operator (^)
- if / elif / else
- while loops
- for loops
- repeat loops
- Functions
- Return values
- Arrays
- Dictionaries
- String operations
- Math library
- Random library
- File operations
- Help command

---

# Planned Features

- Modules
- Import system
- Classes (simple)
- Objects
- Enums
- Better error messages
- Package manager
- Standard library expansion
- JSON support
- CSV support
- Networking
- HTTP requests
- Graphics library
- Audio library

---

# Example

```mini
println "=== Guess Game ==="

target = randrange(1,10)

guess = 0

while guess != target

    guess = input "Guess: "

    if guess < target
        println "Too low"
    elif guess > target
        println "Too high"
    else
        println "Correct!"
    endif

endwhile
```

---

# Build

Requirements

- C++17
- Visual Studio 2022

Compile

```
g++ main.cpp -std=c++17 -O2 -o Mini
```

Run

```
Mini.exe
```

---

# Project Goals

Mini is not meant to compete with C++, Python, or Java.

Instead, it aims to be a fun language that is easy for beginners to understand while remaining powerful enough for real projects.

---

# License

MIT License

---

Made with ❤️ in C++
