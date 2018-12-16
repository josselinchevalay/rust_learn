# Install rust toolchain

for install macOs and Linux you can use this command :

`curl https://sh.rustup.rs -sSf | sh -s -- -y`{{execute}}

> for windows see the documentation https://forge.rust-lang.org/other-installation-methods.html

now you need to manually declare all toolchain installed in your *PATH*

`source $HOME/.cargo/env`{{execute}}

you can check with this command

`rustc --version`{{execute}}
