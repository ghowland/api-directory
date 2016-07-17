# api-directory
Python library to configure how to access an API, like if it was a file system directory structure

This is a planned project.

This project will be a base library for 2 other projects:

- Wrapping access into an API through the ShellInABox javascript code, so that one can act like they are in a CLI, while actually just making web calls in a browser page, with full VT100 control.

- Using this for FUSE libraries, so that they can connect to APIs when accessing directory structures, primarily for providing a hierarchical organization of reports (as files), and also allowing functions to be run by creating executable scripts which call the API, and return the result.

Currently Im thinking of bundling all these projects together in this project, but I might break the other 2 out into their own.  It's advantageous to have them together because then a single configuration could yield FUSE access and web access.
