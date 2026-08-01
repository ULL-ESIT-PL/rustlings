# Contributing Example

This is a copy of the `exercises/00_intro` folder, with a few modifications to demonstrate how to add a new exercise to Rustlings.

- Name the file `exercises/yourTopic/yourTopicN.rs`. In our case we have [exercises/24_contributing_example/contributing1.rs](/exercises/24_contributing_example/contributing1.rs) and [exercises/24_contributing_example/contributing2.rs](/exercises/24_contributing_example/contributing2.rs).
- Make sure to put in some helpful links, and link to sections of The Book in `exercises/yourTopic/README.md`: In this case, see below section "[Further information](#further-information)" for links to The Book.
- In the exercise, add a `// TODO: … comment` where user changes are required. See file [exercises/24_contributing_example/contributing1.rs](/exercises/24_contributing_example/contributing1.rs) 
- Add a solution at solutions/24_contributing_example/24_contributing_example.rs with comments explaining it.
- Add the [metadata for your exercise](#exercise-metadata) in the `rustlings-macros/info.toml` file.
   `git switch -c chore/contributing-example-fix`
- run `cargo dev update` to update the `dev-Cargo.toml` file with your new exercise.
- Make sure your exercise runs with `cargo run --bin rustlings -- run contributing2`
- `cargo run --bin rustlings` and choose `l` and go to the exercise `exercises/24_contributing_example/contributing1.rs` and `exercises/24_contributing_example/contributing2.rs` to check that it works.
- `cargo run -- dev check`
- Si no te convence, descartas toda la rama sin tocar `main`


## Exercise 1

Rust uses the `print!` and `println!` macros to print text to the console.

## Further information

- [Hello World](https://doc.rust-lang.org/rust-by-example/hello.html)
- [Formatted print](https://doc.rust-lang.org/rust-by-example/hello/print.html)
