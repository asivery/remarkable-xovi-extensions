# Remarkable XOVI extensions

This is a monorepo for all my XOVI extensions for the Remarkable Paper Pro tablet.

Note: I call extensions which themselves do not add functionality, but are a dependency for
other extensions 'modules'

All buildscripts require you to have set the XOVI_REPO environment variable to the directory
you have cloned [XOVI](https://github.com/asivery/xovi) to, and TMP to the directory which will be the
parent of all temporary build directories.

# Currently available extensions:

- [fileman](fileman/) - A module for managing filesystem redirections
- [random-suspend-screen](random-suspend-screen) - Lets you randomize your rM tablet's suspend screens