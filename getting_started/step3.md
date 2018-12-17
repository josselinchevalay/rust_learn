## Your first project

here we create projects directory.

`mkdir $HOME/projects`{{execute}}

in this projects directory we create a directory named hello_world

`mkdir $HOME/projects/hello_world`{{execute}}

now in this project your first rust file !

`touch $HOME/projects/hello_world/main.rs`{{execute}}

after that in IDE you can open this file *root/projects/hello_world/main.rs*

```
fn main() {
  println!("hello world");
}
```

we explain this code

*fn* : function statement that permit to declare function.
*main* : this name is reserved but rust to run in first.
*println!* : this is a macro permit to display on screen a message
all *<name_macro>!* id format to use a macro.
