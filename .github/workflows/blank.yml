use std::io;
use std::io::prelude::*;

fn main() {
    let mut input = String::new();
    println!("Please enter a number: ");
    io::stdin().read_line(&mut input).expect("Failed to read line");

    let int_input: u32 = match input.trim().parse().unwrap() {
        num => num,
        _ => {
            println!("Error: Please enter a valid integer number.");
            return;
        }
    };

    println!("The result is: {}", int_input + 2);
}
