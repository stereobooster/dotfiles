# dotfiles

Based on http://github.com/thoughtbot/dotfiles

## Install

Clone onto your laptop:

    git clone git://github.com/stereobooster/dotfiles.git

Install:

    cd dotfiles
    ./install.sh

This will create symlinks for config files in your home directory. If you
include the line "DO NOT EDIT BELOW THIS LINE" anywhere in a config file, it
will copy that file over instead of symlinking it, and it will leave
everything above that line in your local config intact.

You can safely run `./install.sh` multiple times to update.

## Make your own customizations

Put your customizations at the top of files, separated by "DO NOT EDIT BELOW
THIS LINE."

For example, the top of your `~/.gitconfig` might look like this:

    [user]
      name = Joe Ferris
      email = jferris@thoughtbot.com

    # DO NOT EDIT BELOW THIS LINE

    [push]
      default = current

## TODO

 - installation script one liner with `curl` or `wget`, like in Oh My Zsh
 - add [Oh My Zsh](https://github.com/robbyrussell/oh-my-zsh) or [Antigen](https://github.com/zsh-users/antigen)
 - add Puppet for packege installation

## Inspiration

see [wiki](https://github.com/stereobooster/dotfiles/wiki/_pages)
