# Calling Rust from Python

Example where Rust is being called from Python. In the examples, I used CPython 3.9.2 and Rust 1.56.0. The Rust code relies on the std. The Python side relies on `ctypes`, something that comes with Python.
## rust_lib_1

Contains Rust code that can be called from Python to print strings and integers.

## rust_lib_2

Contains and example where on the Python side, a Pydantic Basemodel is used as an argument to a Rust function. Also includes an example to release memory. In the example, Pydantic version `1.8.2` was used.

