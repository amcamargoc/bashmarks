##  Be organized but still lazy af -  Bashmarks version 172.151.92

Based on https://github.com/huyng/bashmarks

Don't do this anymore
> cd Documents/work/bolis/backend/core

Instead do

> cd_ core

## 

## Install

1. git clone https://github.com/amcamargoc/bashmarks
2. cd bashmarks
3. make install
4. Add source **~/.local/bin/bashmarks.sh** from within your **~.bash\_profile** or **~/.bashrc** or **~/.zshrc** file 

## Shell Commands

    s_ <bookmark_name>  - Saves the current directory as "bookmark_name"
    cd_ <bookmark_name> - Goes (cd) to the directory associated with "bookmark_name"
    p_ <bookmark_name>  - Prints the directory associated with "bookmark_name"
    rm_ <bookmark_name> - Deletes the bookmark
    ls_                 - Lists all available bookmarks
    
## Example Usage

    $ cd /var/www/
    $ s_ webfolder
    $ cd /usr/local/lib/
    $ s_ locallib
    $ ls_
    $ cd_ web<tab>
    $ cd_ webfolder

## Where Bashmarks are stored
    
All of your directory bookmarks are saved in a file called ".sdirs" in your HOME directory.
