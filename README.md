<!--🖇🖇🖇🖇🖇-->
 <p align="center">
   <img width="100" height="100" src="./src/assets/linux.png" alt="Logo">
  </p>
  <h1 align="center"><b>Master Linux</b></h1>
  <h3 align="center"><b>The most comprehensive guide to deal with all Linux things and commands.</b></h3>
  <h3 align="center"><b>This repo is under development, you can try to contribute.</b></h3>
<!--🖇🖇🖇🖇🖇-->
<br />
<p align="center">
  Here is you can get started with Linux.
  This tutorial provides basic and advanced concepts of Linux, you can learn for free.
  You can also help us by contributing this repository, and also try to solve any mistakes written in documentation. <br>
    <strong><a href="#">Start Here</a></strong>
</p>
<br>

<!--🖇🖇🖇🖇🖇-->
# Read
You can just <a href="#">Start Here</a> reading.

A book is organized into chapters. Each chapter is a separate page. Chapters can be nested into a hierarchy of sub-chapters. Typically, each chapter will be organized into a series of headings to subdivide a chapter.

<a href="https://rust-lang.github.io/mdBook/guide/reading.html">Learn more about how to interact with this guide.</a>


<!--🖇🖇🖇🖇🖇-->

<!--🖇🖇🖇🖇🖇-->
# Install and Build
This guide is created using [mdBook](https://github.com/rust-lang/mdBook). mdBook is a utility to create modern online books from Markdown files.

### Build from source using Rust
To build the **mdbook** executable from source, you will first need to install Rust and Cargo. Follow the instructions on the [Rust installation page](https://www.rust-lang.org/tools/install). mdBook currently requires at least Rust version 1.54.

Once you have installed Rust, the following command can be used to build and install mdBook:

```bash
cargo install mdbook
```
This will automatically download mdBook from [crates.io](https://crates.io/), build it, and install it in Cargo's global binary directory (**~/.cargo/bin/** by default).

To uninstall, run the command **cargo uninstall mdbook.**

## Render the book
Once you have the mdbook CLI tool installed, you can use it to create and render a book.
There are several ways to render a book, but one of the easiest methods is to use the serve command, which will build your book and start a local webserver:
```bash
mdbook serve --open
```

### Command Line Tool

The `mdbook` command-line tool is used to create and build books.
After you have [installed](../guide/installation.md) `mdbook`, you can run the `mdbook help` command in your terminal to view the available commands.

This following sections provide in-depth information on the different commands available.

* [`mdbook init <directory>`](init.md) — Creates a new book with minimal boilerplate to start with.
* [`mdbook build`](build.md) — Renders the book.
* [`mdbook watch`](watch.md) — Rebuilds the book any time a source file changes.
* [`mdbook serve`](serve.md) — Runs a web server to view the book, and rebuilds on changes.
* [`mdbook test`](test.md) — Tests Rust code samples.
* [`mdbook clean`](clean.md) — Deletes the rendered output.
* [`mdbook completions`](completions.md) — Support for shell auto-completion.

<strong><a href="https://rust-lang.github.io/mdBook/index.html">Read more here</a></strong>
<!--🖇🖇🖇🖇🖇-->

# 