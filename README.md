# rustlings 🦀❤️

Greetings and welcome to `rustlings`. This project contains small exercises to get you used to reading and writing Rust code. This includes reading and responding to compiler messages!

## Project Overview

One language that has been gaining popularity is Rust. I learned about Rust from NoBoilerPlate's "[How to Learn Rust](https://www.youtube.com/watch?v=2hXNd6x9sZs&t=294s)" video on YouTube. Rust is a systems programming language that emphasizes safety, performance, and concurrency. If you are interested in learning Rust, here are some great resources that Tris outlines that I will be using, in a slightly different order. 

My basic plan of attack is to use [Rustlings](https://github.com/rust-lang/rustlings) code kata and learn by fixing tiny failing tests. If I get stuck on a rustling, I will reference [Rust By Example](https://doc.rust-lang.org/rust-by-example/) in an attempt to keep pace and gain momentum. Using the compiler messages, I am attempting to self-identify the issue and implement the solution. This, in my opinion, is simulating a traditional problem solving techinque I would use in a real-life scenario. I must be able to identify why it's not working. If all else fails, the `hint` functionality of rustlings will point me to a chapter in [The Book](https://doc.rust-lang.org/stable/book/),

Rustlings is available on Github, and you can install it on a Windows Subsystem for Linux (WSL) to get started.

In addition to these resources, I am going to complete two "sidequests", as suggested by Tris. 
- Sidequest #1: Listen to [Ultralearning](https://www.audible.com/pd/Ultralearning-Audiobook/0062945149?action_code=ASSGB149080119000H&share_location=pdp) Audiobook is a great resource that explains the principles of ultralearning, and you can use these principles to learn Rust quickly. 
- Sidequest #2: Reading "The Book" a second time, this time using [Brown University's Interactive Book Experiment](https://rust-book.cs.brown.edu/experiment-intro.html). This will help you to absorb the information better.

## Rustlings Compiler Intro

- Is this your first time? Don't worry, Rustlings was made for beginners! We are
  going to teach you a lot of things about Rust, but before we can get  
  started, here's a couple of notes about how Rustlings operates:  

  1. The central concept behind Rustlings is that you solve exercises. These
  exercises usually have some sort of syntax error in them, which will cause  
  them to fail compilation or testing. Sometimes there's a logic error instead  
  of a syntax error. No matter what error, it's your job to find it and fix it!  
  You'll know when you fixed it because then, the exercise will compile and  
  Rustlings will be able to move on to the next exercise.  

  2. If you run Rustlings in watch mode (which we recommend), it'll automatically  
  start with the first exercise. Don't get confused by an error message popping  
  up as soon as you run Rustlings! This is part of the exercise that you're  
  supposed to solve, so open the exercise file in an editor and start your  
  detective work!

  3. If you're stuck on an exercise, there is a helpful hint you can view by typing  
  'hint' (in watch mode), or running `rustlings hint exercise_name`.

  4. If an exercise doesn't make sense to you, feel free to open an issue on GitHub!  
  (https://github.com/rust-lang/rustlings/issues/new). We look at every issue,  
  and sometimes, other learners do too so you can help each other out!

  5. If you want to use `rust-analyzer` with exercises, which provides features like  
  autocompletion, run the command `rustlings lsp`.

- Got all that? Great! To get started, run `rustlings watch` in order to get the first
  exercise. Make sure to have your editor open!

## Contributors ✨

Thanks goes to the wonderful people listed in [AUTHORS.md](./AUTHORS.md) for making all of this possible and to NoBoilerPlate for the initial inspiration. 🎉

## Getting Started

### Install Rust

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source "$HOME/.cargo/env"
exec bash
curl -L https://raw.githubusercontent.com/rust-lang/rustlings/main/install.sh | bash
```

### Once Installed:

```bash
rustlings 
rustlings watch
```

### Shortcuts to Streamline

<kbd>control</kbd> <kbd>P</kbd> exercise.rs


Quick add, commit, push
```bash
git add . && git commit -m "fix: exercise name" && git push
```