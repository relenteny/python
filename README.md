# python

Based on the pyenv image (<https://github.com/relenteny/pyenv),> create an image with Python 3.8.5 and set the default version to 3.8.5.

The `ENTRYPOINT` to this image is simply a shell using the builtin user `alpine`. Applications wishing to use this image are encouraged to extend this image and customize as described in the [pyenv](https://github.com/relenteny/pyenv) documentation.
