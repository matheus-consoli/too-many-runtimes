# Getting started

Before we start talking about asynchronous programming, let's lay the groundwork.

For most part of this book, it's not required that you have a local environment,
you can follow along from the [play.rust-lang.org](https://play.rust-lang.org/),
but it's much nicer you create a project locally, and I will assume that you do.


I'm also assuming that you already have a working Rust development environment,
but if you don't, I recommend you to follow the [rustup](rustup.rs) installation guide.

Let's create a new library to accommodate the project:

```sh
cargo new --lib assimio
```

_assimio_ comes from Latin, and means "assimilation", which I think is a good fit
for our purpose, even tho we're only gonna be talking about the `io` part for a
very short part of this book.


And that's everything we need to start. We're gonna be using some dependencies
through the book, but we're gonna introduce them when necessary.
