### Variables

Rust is a statically typed language, meaning that the types are known at compile time and type checking is mandatory. There are many built-in data types and variable types in Rust, the following are some common variable types and data types

Variables are a way to store data. In Rust, variables must have a declared type. You can use the let keyword to declare variables and initialize them to a specific value. Example:

```rust
let x = 5; // declare an integer variable and initialize it to 5

let y: f32 = 3.14; // Declare a 32-bit floating-point variable and initialize it to 3.14

```

### Basic Data Types

Rust supports many basic data types, including integers, floating point numbers, booleans, and characters. The following are some common basic data types:

* Integers: There are several types of integers in Rust, such as i8, i16, i32, i64, an``d usize. Each of these types has signed and unsigned variants, such as u8 and u16. The size and range of integer variables depend on their type.
* Floating-point numbers: There are two types of floating-point numbers in Rust: f32 and f64. These types represent 32-bit and 64-bit floating-point numbers, respectively. As with integers, the size and precision of a floating-point number depends on its type.
* Boolean values: Boolean types in Rust have only two possible values: true and false.
* Character: The character type in Rust is used to represent a single Unicode character and is usually declared using single quotes ('). For example, 'A' and '€' are both characters.

### Composite data types

Rust also supports composite data types, including tuples and arrays. A tuple is an ordered, fixed-size collection that can contain values of different types, such as:

```bash
let tup: (i32, f64, u8) = (500, 6.4, 1);
```
You can use a dot (.) to access individual elements in a tuple, for example:

```bash
let x = tup.0; // Get the first element of the tuple

let y = tup.1; // Get the second element of the tuple

let z = tup.2; // get the third element of the tuple
```

An array is a collection of elements of the same type with a fixed size. Arrays can be declared using square brackets ([]), for example:

```rust
let a = [1, 2, 3, 4, 5];
```

You can use subscripts to access individual elements in an array, for example:

```rust
let x = a[0]; // Get the first element of the array

let y = a[1]; // get the second element of the array

let z = a[2]; // get the third element of the array
```
