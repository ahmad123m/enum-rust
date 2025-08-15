# Rust Enum Example

This project shows a simple use of **enums** in Rust.

## What is an Enum?
An **enum** (short for *enumeration*) is a custom data type that can have one of several possible values, called **variants**.  
It is useful when you want a variable to represent **one choice out of many options**.

Example:
```rust
enum TrafficLight {
    Red,
    Yellow,
    Green,
}
