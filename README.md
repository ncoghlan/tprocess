# tstrprocess

Experimental library exploring potential interfaces for using Python 3.14's
t-strings to provide more ergonomic subprocess invocation in Python using
shell-style pipelines and IO redirection, but without the security concerns
around mixing user provided input with full system shell invocation.

See [PEP 787](https://peps.python.org/pep-0787/) for additional background.

Note: this initial release just reserves the project name on PyPI. As
[PEP 750](https://peps.python.org/pep-0750/) was accepted after the final
Python 3.14 alpha release, releases with actual code will require
Python 3.14.0b1 or later.
