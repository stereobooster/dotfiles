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

## Inspiration

### Dotfiles

 - Installation script with posibility to override with local setting and keep it updated [thoughtbot/dotfiles](https://github.com/thoughtbot/dotfiles/blob/master/install.sh)
 - Installation script to install all inital packets (alrra/dotfiles)[https://github.com/alrra/dotfiles/blob/master/init/ubuntu.sh]
 - Rakefile, ERB templates, Integrates with Oh My Zsh [ryanb/dotfiles](https://github.com/ryanb/dotfiles)
 - other dotfiles:
   - http://dotfiles.org/
   - http://dotfiles.github.com/
   - http://dotshare.it/
 - [next level dotfile management with libetc](http://blog.piasetzki.name/blog/2012/08/22/next-level-dotfile-management-with-libetc/)
 - [Modular dotfile manager](https://github.com/Ceasar/dots#readme)

### *nix commandline

 - https://github.com/WilliamHackmore/linuxgems/blob/master/cheat_sheet.org.sh
 - http://mmb.pcb.ub.es/~carlesfe/unix/tricks.txt
 - http://www.commandlinefu.com/commands/browse/sort-by-votes/25
 - http://alias.sh
