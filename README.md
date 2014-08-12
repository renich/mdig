Description
===========
This script is a wrapper for the dig command. It applies your command to a list of resolvers.

Example
=======
```bash
    # short results
    mdig +short thepiratebay.se

    # by type
    mdig +short -t mx google.com

    # reverse lookup
    mdig +short -x 8.8.8.8
```
