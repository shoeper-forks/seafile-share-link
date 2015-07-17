# README #

A script to create Seafile share-links from the command line plus a 
wrapper that allows you to use it from Nautilus.

The Nautilus-functionality requires `nautilus-script-manager` or
`nautilus-scripts-manager`.

**Version:** 0.2

## How do I set it up? ##

### Prerequisites ###

`seafile-share-link` requires that `sqlite3` is installed.
It is used to access the Seafile-config-files.

`nautilus-seafile-share-link` is meant to be called as a "Nautilus Script",
and requires `nautilus-script-manager` or `nautilus-scripts-manager`.

### Installation ###

    sudo ./install.sh

### Example ###

    $ cd /home/aba/Seafile/pfc/AroFotos/portraits
    $ seafile-share-link kislas.jpg
    Share-link created at: https://seafile.pf-c.dk/f/12bb311a30/

or with full path:

    $ seafile-share-link /home/aba/Seafile/pfc/AroFotos/portraits/kislas.jpg 
    Share-link created at: https://seafile.pf-c.dk/f/12bb311a30/
