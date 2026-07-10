# Mini

Mini is a simple, beginner-friendly interpreted programming language written in C++.

The goal of Mini is to make programming easy to learn while still providing enough features to create games, automation scripts, utilities, and small applications.

Mini focuses on readability, simplicity, and fun.

---

# Important Note

Mini is still in early development. Some features, commands, or examples shown in this documentation may not work correctly or may not be fully implemented yet.

The language is continuously improving, and future updates will fix bugs, improve stability, and complete missing features.

Thank you for understanding and supporting Mini!

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
println 25^0.5
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

Mini intentionally avoids unnecessary complexity.

---

# Build

Requirements

- C++17
---

# Project Goals

Mini is not meant to compete with C++, Python, or Java.

Instead, it aims to be a fun language that is easy for beginners to understand while remaining powerful enough for real projects.

---

# License

MIT License

---

Made with ❤️ in C++
