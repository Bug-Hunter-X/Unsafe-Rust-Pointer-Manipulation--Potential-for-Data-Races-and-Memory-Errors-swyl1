# Unsafe Rust Pointer Manipulation: Potential for Data Races and Memory Errors

This repository showcases a common error encountered when working with unsafe Rust code, specifically concerning raw pointers and vector manipulation.

The `bug.rs` file demonstrates how modifying a vector's contents via a raw pointer can lead to issues like data races, memory safety violations, and unexpected behavior if not handled cautiously.  The solution in `bugSolution.rs` shows how to avoid this situation by using safe methods whenever possible.