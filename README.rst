Description
===========
This script is a wrapper for the dig command. It applies your command to a list of resolvers.


Installation
============
Just make sure you have the dig command available. It is part of bind-tools in Fedora.

Then, just put mdig in ~/bin or /usr/local/bin


Examples
========
```bash
    # short results
    mdig +short thepiratebay.se

    # by type
    mdig +short -t mx google.com

    # reverse lookup
    mdig +short -x 8.8.8.8
```
