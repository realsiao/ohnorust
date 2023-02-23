Rust provides a variety of control flow statements, including if/else statements, looping statements, matching statements, and error handling statements. The following are some common Rust control flow statements:

### if/else
The if/else statements are used to execute different blocks of code depending on the conditions. For example:

```rust
let x = 5;

if x < 10 {

    println!("x is a number less than 10");

} else {

    println!("x is a number greater than or equal to 10");

}
```

Rust also supports an if/else if/else chain to test multiple conditions, for example:

```rust
let x = 7;
if x < 5 {
    println!("x is a number less than 5");
} else if x < 10 {
    println!("x is a number greater than or equal to 5 and less than 10");
} else {
    println!("x is a number greater than or equal to 10");
}

```


### loop/while/for

The loop statement is used for infinite loops, e.g.

```rust
loop {
    println!("It's an infinite loop");
}
```

The while statement is used to loop through a block of code when the condition is true, e.g.

```rust
let mut x = 0;
while x < 10 {
    println!("The value of x is : {}", x);
    x += 1;
}

```

The for statement is used to iterate through the elements of a collection, e.g.

```rust
let arr = [1, 2, 3, 4, 5];
for i in arr.iter() {
    println!("{}", i);
}

```


### match
The match statement is used to match different patterns based on the value of a variable and execute the corresponding block of code, e.g.

```rust
let x = 3;
match x {
    1 => println!("x is 1"),
    2 => println!("x is 2"),
    3 => println!("xis 3"),
    _ => println!("x is not 1, 2 or 3"),
}

```

### Error Handling Statements
Error handling statements are used to handle possible error conditions. The Result enumeration type in Rust is used to indicate possible success or error states. For example:

```rust
use std::fs::File;

let f = File::open("test.txt");

let f = match f {
    Ok(file) => file,
    Err(error) => {
        panic!("Error opening file: {:?}", error)
    },
};

```

The above code tries to open a file named test.txt and returns the file object if it is successfully opened, otherwise it outputs an error message and exits the program.
