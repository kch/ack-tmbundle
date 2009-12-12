Ack Textmate Bundle
===================

Version 0.1


Usage
-----

Type ` ⌘⇧A` to ack your project in TextMate… 'nuff said.

You can learn more about ack at <http://betterthangrep.com>.


Installation
------------


* Run this:

        cd ~/Library/Application\ Support/TextMate/Bundles
        git clone git://github.com/protocool/ack-tmbundle.git Ack.tmbundle


Bugs
----

You can [file tickets for any bugs using LightHouse][LightHouse].


Notes
-----

The `ack-standalone.sh` script from <http://betterthangrep.com> is included
in this bundle. You can use a different version of ack by setting the
`TM_ACK` environment variable to point to your version.

This bundle has only been tested against this particular version of
ack-standalone.


Per-project `.ackrc`
--------------------

Ack normally honors the settings in your `$HOME/.ackrc` file. Additionally,
any `.ackrc` file in your project directory (`TM_PROJECT_DIRECTORY`) will
also be read.

You can switch-off loading of any `.ackrc` files in the 'Advanced options'
drawer.


Background
----------

The code is based on GrepInProject++ which was itself based on other's code
as below:

    # By Henrik Nyh (http://henrik.nyh.se) 2007-06-26
    # Free to modify and redistribute with credit.

    # Includes some minor modifications by Max (http://max.xaok.org/webtek) 2007-08-01
    # Adds search UI plus some minor modifications by Robert Thurnher (http://soup.robert42.com) 2007-08-11
    # Further modifications by Trevor Squires (http://somethinglearned.com) 2008-05-21

[LightHouse]: http://protocool.lighthouseapp.com/projects/15530-ack-tmbundle/home
