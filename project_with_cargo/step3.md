## build your project

after to begin how let's run command

`cd hello_world_cargo && cargo build && tree .`

### Cargo manage development dependencies

With *Cargo.toml* you can declare your dependencies with *dependencies* section

```
[dependencies]
rand = "0.6.4"
```

for example here i install a *extern crate* (you talk later more about that) to
manage random in my project. you can search a *extern crate* on
https://crates.io/ or `cargo search rand`{{execute}}

*Cargo.lock* this file is create and manage by cargo that's permit to lock
version on your development for example if your wish share your code with
another developper to disable version error with third code (your dev deb)
lock file permit to solve this issue. When you need to update some deb you
run

`cargo update`

Now is you check *target/debug* directory you can see your binary is builded
*hello_world_cargo* is located in *target/debug* if need t release you can run
cargo build with release flag

`cargo build --release`{{execute}}
