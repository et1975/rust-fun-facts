- title : R & D
- description : R & D
- theme : league
- transition : default



***



### Rust

<div>
  <img style="border:0;vertical-align:middle" height="150px" width="150px" src="images/rust.png" />
</div>

10 things you had no idea you wanted to know about Rust!


***
### #10 
It's mature and popular

> - Google, Amazon, Baidu, Intel and GitHub are just some of the sponsors
> - StackOverlow 2018 survey reports it as [Most Loved](https://insights.stackoverflow.com/survey/2018/#technology-most-loved-dreaded-and-wanted-languages)
> - [According to GitHub](https://octoverse.github.com/), Rust is more discussed and reviewed than dotnet/corefx
> - [Friends of Rust](https://www.rust-lang.org/en-US/friends.html)

---
### #9
Rust is among the top choices for security-sensitive projects 

> - Microsoft [IoT security daemon](https://github.com/Azure/iotedge/tree/master/edgelet) is implemented in Rust
> - Heartbleed [would not have been possible](https://www.quora.com/Could-the-Heartbleed-bug-have-happened-if-OpenSSL-had-been-written-in-Rust) if OpenSSL was written in Rust

---

### #8
Has something for every one 

> - [ML](http://www.arewelearningyet.com/)
> - [Actor framework](https://github.com/actix)
> - [Network servers](https://tokio.rs)
> - etc

---
### #7
Just like Clang and Swift, Rust compiler is a frontend for LLVM (cross-compiler)

> - Rust code can run on bare metal: from just `main()` to [RTFM](http://blog.japaric.io/tags/rtfm/), [TockOS](https://www.tockos.org/), [ChibiOS/RT](http://www.chibios.org/) and full-blown POSIX-compatible [Redox](https://www.redox-os.org/) desktop OS
> - Rust code can run in the browser 


---
### #6
Rust's own installation is managed by [rustup](https://rustup.rs/)

> - multiple side-by-side installations of toolchains, targets and components

---
### #5
[Cargo](https://doc.rust-lang.org/cargo/) is the single point of entry into entire build process 

> - Start new project, manage dependencies
> - Built and run tests and publish the crates
> - It's SemVer-compliant
> - Unit-testing and documentation is built-in
> - Build process itself can be extended with Rust

---
### #4

Rust's central philosophy is safety at zero-cost

> - memory management is safe w/o using a GC
> - dynamic dispatch is opt-in
> - No nulls, but `Option` is optimized away
> - Zero-copy by default
> - No exceptions, but flexisble `Error` handling

---
### #3
Rust is for systems programming, but it's influenced by ideas and lessons learned in other fields 

> - strong C FFI
> - statically and richly-typed, w/o classes
> - powerful metaprogramming with procedural macros
> - local type inferrence
> - safe and immutable by default


---
### #2 
Borrow checker

```rust
struct Thing(i32);

fn foo(bar: Thing) {}

let x = Thing(42);
foo(x);
// foo(x); // ERROR: x moved into foo
```

> - Learn about .data, stack and heap from the safety of compiler telling you "You are doing it wrong!"  
> - Concurrency without data races
> - Mutability without unforseen consequences

---
### #1 

Learning to program in Rust will make you a better programmer.

> - A lot of smart people work on Rust, and they want you to feel smart, too!
> - [The Book](https://doc.rust-lang.org/book/second-edition/index.html)
> - [State of Rust](https://forge.rust-lang.org/state-of-rust.html)

