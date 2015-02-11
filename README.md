# lnk
Creates a symbolic link of a target-file to /usr/bin/.


### Usage

    $ lnk <file>

### Examples


Places a symbolic link of the lnk-script into the /usr/bin/-directory.

    $ ./lnk lnk

Places a symbolic link of ./some/script into the /usr/bin/-directory. Note that the path's will be resolved automatically.

    $ lnk ./some/script
