## Cargo is convention

to respect all best pratrice about rust project : use cargo.

for create a binary project you can use this command

`cargo new hello_world_cargo --bin`{{execute}}

`cargo new hello_lib_cargo --lib` permit to create a library project

`cargo new hello_cargo_vcs --bin --vcs SVN`

after that you can display project structure

`tree hello_world_cargo`

first file into your project is Cargo.toml. This file contain all metadata
about your project name, author dependencies are declare on Cargo.toml.
if you see your Cargo.toml it contains :
```
[package]
name = "hello_world_cargo"
version = "0.1.0"
authors = ["root"]
edition = "2018"

[dependencies]
```

after that cargo have create a directory called *src* this directory contains
a file *main.rs* wich contains a main function that's your entrypoint for your
binary.

Cargo is a convention for write rust program it permit to init your project,
manager your development dependencies etc. this is a magic command !

in next step we will see how to cargo permit to manage dev libraries and build
your project.
