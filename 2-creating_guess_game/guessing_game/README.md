# 2 - Programming a Guessing Game

- To obtain user input and than print the result as output, we need to bring the io (input/output) library into scope.

```rust
  use str::io;
```

- In Rust, variables are immutable by default, meaning once we give the variable a value, the value won't change. We`ll be discussing this concept in detail in the "Variables and Mutability" section in Chapter 3. To make a variable mutable, we add mut before the variable name:

```rust
  let apples = 5; // immutable
  let mut bananas = 5; // mutable
```

- The :: syntax in the ::new line indicates that new is an associated function of the string type. An associated function is a function that's implemented on a type, in this case String. This new function created a new, empty string. You'll find a new function on many types because it's a common name for a function that makes a new value of some kind.

- To add new module, we can run that command:

```rust
  cargo add module_name
```