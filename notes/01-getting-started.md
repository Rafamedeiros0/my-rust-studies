## link to the book

https://doc.rust-lang.org/book/

## how update

rustup update

## how run the code using rustup

First need to run

'''bash
rustc name-file.rs
'''

later need to run:

'''bash
name-file
'''

## automatic formatter (lint)

rustfmt - look the appendix D for more details

but, just basicaly need to run:

'''
rustfmt name-file.rs
'''

the formatter formate the document

## ! is a macro 

when we use ! we are calling a macro (not a normal function)

## how create and run code using cargo

### crate new project with cargo

'''
cargo new project-name
'''

### just compile

(create executable in target/debug)

'''
cargo build
'''

### compile + run

(create executable in target/debut)

'''
cargo run
'''

### how check if the programming is possible to compile (but not compile the code)

cargo check is faster than cargo build, sometimes to check if the code is right, we can just run cargo check:

'''
cargo check
'''

### build for release

compile the code with optimizations (create executable in target/release)

'''
cargo build --release
'''
