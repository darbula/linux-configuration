# Linux configuration

To install clone files in home dir.

## Bashrc

Currently Included:

* command history search: start typing command and press up arrow to select command


## Pico/Nano Syntax Highlight


    git clone https://github.com/nanorc/nanorc.git
    cd nanorc

### Local

    make clean && make install TEXT=white

Add line `include ~/.nano/syntax/ALL.nanorc` to `~/.nanorc`.

### Global

    make clean && make install-global TEXT=white

Add line `include /usr/local/share/nano/ALL.nanorc` to `/etc/nanorc`.

