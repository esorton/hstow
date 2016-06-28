hstow: Home Directory Stow
==========================

Simple shell script for managing home directory soft links with stow.

Quick start instructions:

    % cd ${HOME}
    % mkdir .hstow
    % cd .hstow
    % git clone https://github.com/esorton/hstow.git
    % cd ${HOME}
    % ./.hstow/hstow/bin/hstow

As `hstow` is stowed in `${HOME}/bin`, full path to script is not required
after the initial stow as long as `${HOME}/bin` is in the current path.

Checkout additional repositories within `${HOME}/.hstow` and/or create
additional subdirectories with files to be stowed.  Run `hstow` to create the
necessary soft links or to update things change.

List files to ignore in `.stow-local-ignore` file in root of repository.

`stow` utility must be installed on the host computer.  On Debian based
distributions, install with `apt-get`:

    % sudo apt-get install stow

`stow` source can be obtained at https://www.gnu.org/software/stow/.
