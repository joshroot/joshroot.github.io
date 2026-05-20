![Learning Rust For Busy People cover art](/assets/img/learning_rust_for_busy_people_cover_art_620x620.png)

A podcast for busy people who want to learn and quickly be productive with the Rust programming language.

# Episodes

### #1 – Introduction

Introduction episode for the Learning Rust For Busy People podcast.

### #2 – Installing Rust and using Cargo to manage a project

Overview of installing Rust and using Cargo to create a new project, compile code, and run the executable that’s built. Discussion of differences and similarities in how projects are set up and managed in Rust versus in Python.

RustRover IDE: [https://www.jetbrains.com/rust/](https://www.jetbrains.com/rust/)

### #3 – Extracting text from a Markdown file, part 1

First practical code example. Use Rust to extract text from a Markdown file. Covers how to use Rust to read the contents of a text file, iterate through lines of a text file, manipulate a String by replacing text, and print the value of a variable to standard output.

Code example: [version 1](https://github.com/joshroot/learning-rust-for-busy-people/tree/main/examples/ex001_extract_text_from_markdown_file/v01)

### #4 – Extracting text from a Markdown file, part 2

Use Rust to extract text from a Markdown file, part 2. Covers concepts that include refactoring a program into a binary crate and a library crate for separation of concerns, passing command-line arguments to a program, using a vector, using the “dbg!” macro, the system of “ownership” in Rust, and what it means for a Rust program to “panic”.

Code example: [version 2](https://github.com/joshroot/learning-rust-for-busy-people/tree/main/examples/ex001_extract_text_from_markdown_file/v02)

### #5 – Extracting text from a Markdown file, part 3

Use Rust to extract text from a Markdown file, part 3. Covers concepts that include how to implement error handling by treating problems as either “unrecoverable” errors (by calling the “panic!” macro) or “recoverable” errors (by returning a “Result” enum), how to propagate errors using the question mark operator, and how to specify return types and return values for functions.

Code example: [version 3](https://github.com/joshroot/learning-rust-for-busy-people/tree/main/examples/ex001_extract_text_from_markdown_file/v03)

### #6 – minised, part 1

Use Rust to develop a miniature version of the “sed” command-line utility, part 1. Covers topics that include a subset of functionality for the “sed” command-line utility that’s used for replacing text, the scope of features that we’ll include in the miniature “sed” utility that we’re building, how to define a “struct” in Rust, how to leverage the “Option” enum for a value that may be either something or nothing, how to instantiate a “struct” in Rust via an associated function in an implementation block, how to bring a “struct” into scope in the binary crate, and how to use the “unwrap_or_else” method on a “Result” enum and define a “closure”.

Code example: [version 1](https://github.com/joshroot/learning-rust-for-busy-people/tree/main/examples/ex002_minised/v01)

### #7 – minised, part 2

Use Rust to develop a miniature version of the “sed” command-line utility, part 2. Covers topics that include an update to the level of detail covered in the podcast, considerations when selecting the name “build” or “new” for a constructor function that is associated with a “struct”, differences between the Python Standard Library and Rust Standard Library when it comes to functionality for command-line interfaces and parsing command-line arguments, using “de-structuring” to create and assign values to multiple variables simultaneously, using the “clone” method to make a “deep copy”, defining a custom “enum” type, several string-related methods (such as “split”, “match_indices”, and “split_at”), using “match” expressions, reading from standard input, using the “format!” macro to create new strings, and converting between “Strings” and “string slices”.

Code example: [version 1](https://github.com/joshroot/learning-rust-for-busy-people/tree/main/examples/ex002_minised/v01)

# Future topics

* Unit tests for the miniature version of the "sed" command-line utility

# Practical code examples

[Repository](https://github.com/joshroot/learning-rust-for-busy-people)
