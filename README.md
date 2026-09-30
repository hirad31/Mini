# Mini

[English](#english) | [فارسی](#فارسی)

---

## English

**Mini** is a simple, beginner-friendly interpreted programming language written in C++.

The goal of Mini is to make programming easy to learn while still providing enough features to create games, automation scripts, utilities, and small applications.

Mini focuses on **readability, simplicity, and fun**.

> **🇮🇷 Made by an Iranian developer**

---

## Important Note

**Mini is still in early development.**  
Some features, commands, or examples shown in this documentation may not work correctly or may not be fully implemented yet.

The language is continuously improving, and future updates will fix bugs, improve stability, and complete missing features.

Thank you for understanding and supporting Mini!

---

## Features

### Input

```mini
name = input "Enter your name: "
println "Hello" name
```

### Conditions

```mini
if x > 5
    println "Big"
elif x == 5
    println "Equal"
else
    println "Small"
endif
```

### Loops

#### While Loop

```mini
while x < 10
    println x
    inc x
endwhile
```

#### Repeat Loop

```mini
repeat 3 times
    println "Hello!"
endrepeat
```

### Functions

```mini
func hello(name)
    println "Hello" name
endfunc

call hello("Mini")
```

Functions can also return values:

```mini
func add(a,b)
    return a+b
endfunc

println call add(5,7)
```

### Arrays

```mini
numbers = [10,20,30]

println numbers[0]
println numbers[1]
println numbers[2]
```

### Math Operations

```mini
println 2+3*4
println (2+3)*4
println 2^8
println 25^0.5
```

### File Operations

```mini
file_write "save.txt" "Hello"

println file_read "save.txt"
```

---

## Language Philosophy

Mini is designed to be:

- Easy to learn
- Easy to read
- Lightweight
- Fast
- Beginner-friendly
- Great for learning programming

Mini intentionally avoids unnecessary complexity.

---

## Requirements

- This program requires **C++17** or **C++14** to run

---

## Important Execution Note

**You must run this program using a Terminal.**

If you use **Windows Command Prompt (cmd.exe)**, the colors in the output may not display correctly and could break.

**Please note:** Colors may also not display properly in **PowerShell**.

For the best experience, use a modern terminal emulator that supports ANSI color codes.

---

## Project Goals

Mini is not meant to compete with C++, Python, or Java.

Instead, it aims to be a **fun language** that is easy for beginners to understand while remaining powerful enough for real projects.

---

## License

MIT License

---

Made with ❤️ in C++ by an Iranian developer 🇮🇷

---

## فارسی

**Mini** یک زبان برنامه‌نویسی تفسیری ساده و مناسب برای مبتدیان است که با C++ نوشته شده است.

هدف Mini این است که یادگیری برنامه‌نویسی را آسان کند و در عین حال ویژگی‌های کافی برای ساخت بازی، اسکریپت‌های خودکارسازی، ابزارهای کاربردی و برنامه‌های کوچک را فراهم کند.

Mini روی **خوانایی، سادگی و لذت‌بخش بودن** تمرکز دارد.

> **🇮🇷 ساخته‌شده توسط یک توسعه‌دهنده ایرانی**

---

## نکته مهم

**Mini هنوز در مراحل اولیه توسعه است.**  
برخی از ویژگی‌ها، دستورها یا مثال‌هایی که در این مستندات نشان داده شده‌اند ممکن است به‌درستی کار نکنند یا هنوز به‌طور کامل پیاده‌سازی نشده باشند.

این زبان به‌طور مداوم در حال بهبود است و به‌روزرسانی‌های آینده باگ‌ها را رفع می‌کنند، پایداری را بهبود می‌بخشند و ویژگی‌های ناقص را کامل می‌کنند.

از درک و حمایت شما از Mini سپاسگزاریم!

---

## ویژگی‌ها

### ورودی

```mini
name = input "Enter your name: "
println "Hello" name
```

### شرط‌ها

```mini
if x > 5
    println "Big"
elif x == 5
    println "Equal"
else
    println "Small"
endif
```

### حلقه‌ها

#### حلقه While

```mini
while x < 10
    println x
    inc x
endwhile
```

#### حلقه Repeat

```mini
repeat 3 times
    println "Hello!"
endrepeat
```

### توابع

```mini
func hello(name)
    println "Hello" name
endfunc

call hello("Mini")
```

توابع همچنین می‌توانند مقدار برگردانند:

```mini
func add(a,b)
    return a+b
endfunc

println call add(5,7)
```

### آرایه‌ها

```mini
numbers = [10,20,30]

println numbers[0]
println numbers[1]
println numbers[2]
```

### عملیات ریاضی

```mini
println 2+3*4
println (2+3)*4
println 2^8
println 25^0.5
```

### عملیات فایل

```mini
file_write "save.txt" "Hello"

println file_read "save.txt"
```

---

## فلسفه زبان

Mini طوری طراحی شده است که:

- یادگیری آن آسان باشد
- خواندن آن آسان باشد
- سبک باشد
- سریع باشد
- مناسب مبتدیان باشد
- برای یادگیری برنامه‌نویسی عالی باشد

Mini عمداً از پیچیدگی‌های غیرضروری پرهیز می‌کند.

---

## پیش‌نیازها

- این برنامه برای اجرا به **C++17** یا **C++14** نیاز دارد

---

## نکته مهم اجرا

**باید این برنامه را با یک ترمینال اجرا کنید.**

اگر از **Windows Command Prompt (cmd.exe)** استفاده می‌کنید، رنگ‌ها در خروجی ممکن است به‌درستی نمایش داده نشوند و خراب شوند.

**لطفاً توجه کنید:** رنگ‌ها ممکن است در **PowerShell** هم به‌درستی نمایش داده نشوند.

برای بهترین تجربه، از یک ترمینال مدرن استفاده کنید که از کدهای رنگ ANSI پشتیبانی می‌کند.

---

## اهداف پروژه

Mini قرار نیست با C++، Python یا Java رقابت کند.

در عوض، هدف آن یک **زبان سرگرم‌کننده** است که برای مبتدیان آسان باشد و در عین حال برای پروژه‌های واقعی به‌اندازه کافی قدرتمند باشد.

---

## مجوز

MIT License

---

ساخته‌شده با ❤️ در C++ توسط یک توسعه‌دهنده ایرانی 🇮🇷
