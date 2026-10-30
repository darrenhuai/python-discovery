Query a virtual environment's base interpreter with the ``env`` passed to ``get_interpreter`` rather than the process
environment, so a ``PY_DISCOVERY_TIMEOUT`` set there covers that query too.
