# Rust Basics

In this step we explore the basic syntax and concepts.

::include{src="./snippets/hello.rs"}

## Ownership Model

Every value in Rust has a single owner. When the owner goes out of scope, the value is dropped.

::include{src="./tables/missing.md"}

> This step intentionally includes a broken include path (`./tables/missing.md`) to demonstrate diagnostics.
