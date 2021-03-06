# backpack
<img src="https://static.thenounproject.com/png/47008-200.png" width="120" />

A shell script to automate the setup of new development environments. Read more [here](https://medium.com/@fulstop/quick-and-painless-linux-development-1c576b479f6c).

``` shell
git clone git@github.com:desertdisk/backpack.git
./backpack.sh
```

Backpack makes a few assumptions out of the box:
- You're using a Debian based distro.
- You're going to be using ruby.
- You're going to be using CLI tools such as git, zsh, vim, and tmux.

Backpack is best served within an existing `~/dotfiles` directory. See [mine](https://github.com/fulstop/dotfiles) as an example.
