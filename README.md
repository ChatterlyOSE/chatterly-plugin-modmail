# chatterly modtools plugin

This plugin adds the /modtools webpages, including modmail alpha.

## installation

First, install the python package:

    python ./setup.py develop

To enable the plugin, you will need to add it to the plugins line of your
reddit .ini file:

    plugins = modtools

To build static files for production, run `make` in the main chatterly repository.
It will detect, build, and merge in the modtools plugin static files for
deployment.
