# Rust Index Out of Bounds Example

This repository contains a simple Rust program that demonstrates a common runtime error: panicking due to an index out of bounds error when accessing a vector. The example showcases the error and its solution using safe indexing techniques.

## Bug
The `bug.rs` file contains the code that causes the panic. The program attempts to access an element in a vector using an index that is beyond the vector's bounds. This leads to a runtime panic.

## Solution
The `bugSolution.rs` file demonstrates a safe way to handle vector access. This approach uses the `get()` method, which returns an `Option`, allowing for safe handling of out-of-bounds indices.