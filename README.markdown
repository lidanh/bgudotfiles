# Ben Gurion University dotfiles

![BGU dotfiles](https://i.imgur.com/90Gg7.png)

## what's inside

- Colors!! colorful shell with orange prompt for BGU.
- [spf13-vim](http://vim.spf13.com/)- the best vim distribution with a lot of useful plugins.
- git plugins (e.g. git-wtf)
- common aliases for fast development
- Unicode support

## install

Run this:

```sh
git clone https://github.com/lidanh/bgudotfiles.git ~/.dotfiles
cd ~/.dotfiles
./bootstrap
```

This will symlink the appropriate files in `.dotfiles` to your home directory.
Everything is configured and tweaked within `~/.dotfiles`.

![BGU dotfiles](https://i.imgur.com/c0GGP.png)

## Best Practices

Generate ssh public keys for your own machine and BGU gateway. Add them to .ssh/authorized_keys so you can perform
ssh and scp without typing the password again and again.  more info [here](http://www.thegeekstuff.com/2008/06/perform-ssh-and-scp-without-entering-password-on-openssh/).
