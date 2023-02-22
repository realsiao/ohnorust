### Variables and Data Types: 

> Rust supports several data types, including integers, floating-point numbers, booleans, and strings. Variables are declared using the let keyword, and the type of the variable can be specified using a colon: followed by the data type. For example:

```rust
let x: i32 = 42;
let y: f64 = 3.14;
let z: bool = true;
let my_string: &str = "Hello, Rust!";
```

### Functions:

> Functions in Rust are declared using the fn keyword, followed by the function name and a set of parentheses that may contain parameters. Functions return a value using the return keyword or the value of the last expression in the function body. For example:

```rust
fn add(a: i32, b: i32) -> i32 {
    return a + b;
}
```

### Control Flow: 
> Rust supports standard control flow constructs such as `if/else` statements and `for` loops. For example:

```rust
let x = 42;
if x < 10 {
    println!("x is less than 10");
} else if x == 10 {
    println!("x is equal to 10");
} else {
    println!("x is greater than 10");
}

for i in 0..10 {
    println!("{}", i);
}
```

### Structs and Enums:
> Rust has a flexible type system that allows you to define custom data types using structs and enums. Structs are similar to classes in other languages, and allow you to group related data together. Enums are a way to define a type that can have one of several variants. For example:

```rust
struct Point {
    x: i32,
    y: i32,
}

enum Color {
    Red,
    Green,
    Blue,
}
```

