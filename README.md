hstow: Home Directory Stow
==========================

Simple shell script for managing home directory soft links with stow.

Quick start instructions:

    % cd ${HOME}
    % mkdir .hstow
    % git co https://github.com/esorton/hstow.git
    % ./hstow/bin/hstow

Be sure `${HOME}/bin` is in your path so your shell can find `hstow`.

Checkout additional repositories within `${HOME}/.hstow` and/or create
additional subdirectories with files to be stowed.  Run `hstow` to create the
necessary soft links or to update things change.

