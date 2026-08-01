# Contributing Example

This is a copy of the `exercises/00_intro` folder, with a few modifications to demonstrate how to add a new exercise to Rustlings.

- Name the file `exercises/yourTopic/yourTopicN.rs`. In our case we have [exercises/24_contributing_example/contributing1.rs](/exercises/24_contributing_example/contributing1.rs) and [exercises/24_contributing_example/contributing2.rs](/exercises/24_contributing_example/contributing2.rs).
- Make sure to put in some helpful links, and link to sections of The Book in `exercises/yourTopic/README.md`: In this case, see below section "[Further information](#further-information)" for links to The Book.
- In the exercise, add a `// TODO: … comment` where user changes are required. See file [exercises/24_contributing_example/contributing1.rs](/exercises/24_contributing_example/contributing1.rs#L1-L7) and [exercises/24_contributing_example/contributing2.rs](/exercises/24_contributing_example/contributing2.rs#L2) for examples.
- For each of the exercises, add solutions at `solutions/yourTopic/`. In our case at [solutions/24_contributing_example/](/solutions/24_contributing_example/) with comments explaining it.
- Add the [metadata for your exercise](#exercise-metadata) in the [`rustlings-macros/info.toml`](/rustlings-macros/info.toml#L1215-L1232) file.
- Create a new branch: `git switch -c chore/contributing-example-fix` to check if your exercise runs
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
