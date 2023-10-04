---
marp: true
title: Marp CLI example
description: Hosting Marp slide deck on the web
theme: uncover
transition: fade
paginate: true
_paginate: false
---

![bg opacity](./assets/gradient.jpg)

# <!--fit--> Rust... Why...?

Why you should be coding in Rust

https://github.com/abstecker/why-rust

<style scoped>a { color: #36c; }</style>

<!-- This is presenter note. You can write down notes through HTML comment. -->

---

### Key Features to this developer's heart

* Memory Management 
  * (avoids [Billion Dollar Mistake](https://en.wikipedia.org/wiki/Tony_Hoare#cite_ref-27))
  * No garbage collection [Example](https://github.com/abstecker/rs_scratch)
* Consistency
  * Rustup
  * Cargo
  * Clippy
* Tests in same file (who knew I needed this?)
* [doctests!!!](https://github.com/abstecker/rs_scratch/blob/main/src/lib.rs)

---

## My Advice on using Rust is...

---

# Don't

---


### <!--fit--> JUST DON'T!

---

### <!--fit--> WHY?

---

##### <!--fit--> :scream_cat: It's a Trap!!! :scream_cat:

---

<!-- _backgroundColor: "#123" -->
<!-- _color: "#fff" -->
![It is a trap!](./assets/itsatrap.jpg)

---

# Reasons

* It will make you hate every other language
* ...

---

### Example 1: Managing Installations

* Java: [Oracle](https://www.oracle.com/java/technologies/javase-documentation.html), [sdkman!](https://sdkman.io/), [Homebrew](https://brew.sh/), [Chocolatey](https://chocolatey.org/), [APT](https://ubuntu.com/tutorials/install-jre#1-overview)
* Node.JS: [NPM](https://www.npmjs.com/), [N](https://github.com/tj/n)
* Ruby: [RVM](https://rvm.io/), [rbenv](https://github.com/rbenv/rbenv), [chruby](https://github.com/postmodern/chruby)
* Ubiquitous: [asdf](https://asdf-vm.com/)
* Python: ¯\_(ツ)_/¯ (T-Shirt Cannon, AFAIK)

---

### Example 1 cont... (Rust Version)

* [rustup](https://rustup.rs/)

---

### Example 2: Build Tools

* C++: Make, CMake, Autotools, Meson, [Bazel](https://bazel.build/), [Ninja](https://ninja-build.org/)
* Java: Ant, Maven, Ivy, Gradle, [Bazel](https://bazel.build/), [SBT](https://www.scala-sbt.org/)
* Server-side JS: Node.JS, Deno, NPM, Yarn
* JS: Grunt, Webpack, Parcel, Rollup, Vite, kill me... please...

---

### Example 2 cont... (Rust Version)

* [Cargo](https://doc.rust-lang.org/cargo/)

---

### Example 3: Linting

* C/C++: Lint, IntelliSense, Flint, CppLint, CppCheck, clang-tidy
* JS: ESLint, JSLint
* etc etc etc

---

### Example 3 cont... (Rust Version)

* [Clippy](https://github.com/rust-lang/rust-clippy)

---

### Example 4: Testing

* AceUnit, AcuTest, API Sanity Checker, Aeryn, ATF, Bandit, BDD-for-C, Boost Test Library, BugEye, Cantata++, Casmine, Catch, Catch2, CATCH-VC6, Catsrunner, CBDD, cfix, Cgreen, CHEAT, Check, Cmocka, Cmockery, CppUTest, Cput, CPPOCL/test, CppTest, cpptest-lite, CppUnit, CppUnitLite, CPUnit, Criterion, crpcut, CT, CU, CUTE, cutee, CTest, CUnit, CUnit (CUnity Fork), CUnitWin32, CUT, Cutter, CxxTest, doctest, EmbeddedUnit, Embunit, Exercisix, FakeIt, FCTX, Fructose, GLib Testing, Google C++ Mocking Framework, Google Test,


---

GUnit, Hammocking, Hestia, Hippomocks, Igloo, lcut, lest, libcester, liblittletest, LibU, libunittest, mettle, Microsoft Unit Testing Framework for C++, Mimicc, MinUnit, mock++/mockcpp, mockitopp, mockpp, Mut, Nala, NanoCppUnit, NovaProva, NullUnit, OAKUT, Opmock, Parasoft C/C++test, PicoTest, qc, QtTest, Rexo, SafetyNet, ShortCUT, STRIDE, Symbian OS Unit, TBrun, RCUNIT, Rexo, RTRT, SeaTest, Smarttester, Sput, sTest, STRIDE, LDRA Testbed, Tau, Tessy, TDOG, TestApe, Test Dept., 

---

Test soon, Testwell CTA++, TF unit test, Theft, tinytest, TPT, tpunit++, Trompeloeil, TUT, Typemock Isolator++, Unit++, unit.hpp, UnitTest++, Unity, upp11, UquoniTest, usfstl, μt, VectorCAST/C, Visual Assert, WinUnit, xTests, xUnit++

---

### Example 4 cont... (Rust Version)

* Test

---

# The quantum quandaries of the polyglot programmer

C, C++, Ruby, Python, Perl, Basic, Visual Basic, VBScript, LiveScript, JavaScript, ECMAScript, TypeScript, Go, Scala, Java, Elixir, Erlang, Pascal, C#, F#, Eiffel, Clojure

**x languages TIMES y frameworks = I am too old for this ...**

---

# The Moral:

Just because a language doesn't, doesn't mean you don't have to. 

(How many negatives is this?)

---

# [Embedded Rust](https://www.rust-lang.org/what/embedded)

- Books
  - [The Discovery book](https://docs.rust-embedded.org/discovery/)
  - [The Embedded Rust Book](https://docs.rust-embedded.org/book/)
  - [The Embedonomicon](https://docs.rust-embedded.org/embedonomicon/)
- [Rust on Embedded Devices Working Group](https://github.com/rust-embedded)
- [Awesome Embedded Rust](https://github.com/rust-embedded/awesome-embedded-rust)
- [Running Rust on Microcontrollers](https://blog.mbedded.ninja/programming/languages/rust/running-rust-on-microcontrollers/)
- [Rust for Embedded – Is It Ready Yet?](https://www.inovex.de/de/blog/rust-for-embedded-is-it-ready-yet/)

---

### [5 roadblocks to Rust adoption in embedded systems](https://www.embedded.com/5-roadblocks-to-rust-adoption-in-embedded-systems/)

- Commercial Support
- Training Costs
- Conservative Adoption of Technologies
- Toolchain Integration
- Lack of Standardization

---

# Free Books!

- [The Rust Programming Language](https://doc.rust-lang.org/stable/book/)
- [The Rust Performance Book](https://nnethercote.github.io/perf-book/)
- [The Rustonomicon](https://doc.rust-lang.org/nightly/nomicon/)
- [Rust Design Patterns](https://rust-unofficial.github.io/patterns/)
- [Effective Rust](https://www.lurklurk.org/effective-rust/)
- [Rust Atomics and Locks](https://marabos.nl/atomics/foreword.html)
- [The Little Book of Rust Macros](https://danielkeep.github.io/tlborm/book/index.html)


---

# Rust YouTube Channels

- Jeremy Chone https://youtube.com/@JeremyChone 
- No Boilerplate: https://youtube.com/@NoBoilerplate
- Logan Smith: https://youtube.com/@_noisecode
- Tim Clicks: https://youtube.com/@timClicks
- Lets Get Rusty: https://youtube.com/@letsgetrusty
- Jon Gjengset: https://youtube.com/@jonhoo

---

## The World's Simplest Kata

https://github.com/devplaybooks/rust_worlds_simplest_kata

---

![bg 40% opacity blur](https://avatars.githubusercontent.com/u/132228748?s=200&v=4)

### Created by Christoph ([@folkengine](https://github.com/folkengine))

https://github.com/abstecker/why-rust
