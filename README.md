# Learn Rust
A compilation of my recommended Rust learning resources, in addition with a learning roadmap. There are various other resources out there, but I will not be naming them all in preference of brevity.

# Table of Contents

- [Learning Path](#learning-path)
- [Additional Resources](#additional-resources)

# Learning Path

1. [The Rust Programming Language Book](https://doc.rust-lang.org/stable/book/): This book is intended to help people with prior programming experience learn about how Rust works. It establishes a solid foundation that you can easily build upon. Make sure to follow along with the code and projects that are part of the book.
2. [Rustlings](https://github.com/rust-lang/rustlings): Rustlings is a series of Rust exercises to help you start writing basic Rust code and get used to the semantics of the language. You should do it in tandem with reading the book.
3. [Rust By Example](https://doc.rust-lang.org/rust-by-example/): This book explains examples of Rust code to help you figure out what is going on. It is helpful to see how different parts of Rust work together. I recommend going over this book 
5. Start writing some Rust code. Figure out a project that aligns with your interests and start writing it in Rust. Some easy programs to make as a Rust beginner are programs that take user input, CLI applications, and basic web APIs. You should have enough knowledge by this point to write said projects.
6. [async/.await Book]((https://rust-lang.github.io/async-book/): The Rust book introduces how Rust does concurrency through multithreading. Rust also provides another avenue to do concurrency through `async` and `.await` or `Future`s. This book goes into detail about how it all works.
7. [Crust of Rust series by Jon Gjengset](https://youtube.com/playlist?list=PLqbS7AVVErFiWDOAVrPt7aYmnuuOLYvOa): At this point, you could probably be considered an "intermediate" Rust programmer. This series helps you gain intermediate knowledge about Rust that continues to build on what you already know and explain how certain things work. Topics discussed include interior mutability, subtyping and variance, atomics, and more.
8. [Rust for Rustacenas by Jon Gjengset](https://www.amazon.com/Rust-Rustaceans-Programming-Experienced-Developers-ebook/dp/B0957SWKBS): Another intermediate Rust resource that acts as a great compliment to the Crust of Rust series. It introduces topics not in Crust of Rust such as designing libraries, the Cargo package manager, and more.
9. [Too Many Linked Lists](https://rust-unofficial.github.io/too-many-lists/): This book talks about how to make linked-list data structures in Rust, both safely and unsafely. This might be your first introduction to the `unsafe` world of Rust, so be ready.
10. [The Rustonomicon](https://doc.rust-lang.org/stable/nomicon/): By this point, you will have decent Rust experience and would have been introduced to `unsafe` Rust. But, you might be wondering how things work on a lower level and what `unsafe` really is and what it is for. This book will explain `unsafe` and how it interacts with other Rust code.
  
# Additional Resources

These resources can act as references for when you need assistances with other sections of the Rust language and ecosystem.

1. [The Cargo Book](https://doc.rust-lang.org/cargo/)
2. [The Rustup Book](https://rust-lang.github.io/rustup/)
3. [The Rustc Book](https://doc.rust-lang.org/rustc/what-is-rustc.html)
4. [Rust Cheat Sheet](https://cheats.rs)
5. [The Rustdoc Book](https://doc.rust-lang.org/rustdoc/index.html)
6. [The Rust Edition Guide](https://doc.rust-lang.org/edition-guide/index.html)
7. [The Rust Unstable Book](https://doc.rust-lang.org/nightly/unstable-book/index.html)
8. [The Little Book of Rust Macros](https://danielkeep.github.io/tlborm/book/)
9. [Rust Idioms, Design Patterns, and Anti-Patterns](https://rust-unofficial.github.io/patterns/intro.html)
10. [The Rust Reference](https://doc.rust-lang.org/reference/introduction.html)
11. [Visualizing memory layout of Rust's data types](https://www.youtube.com/watch?v=rDoqT-a6UFg)
