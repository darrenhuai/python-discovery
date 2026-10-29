Stop a ``.python-version`` file that is not valid UTF-8, or that cannot be read, from aborting discovery through a
pyenv, mise or asdf shim; the first is read the way pyenv reads it, and the second is skipped like a missing file.
