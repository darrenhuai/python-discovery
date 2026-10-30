Stop ``PythonInfo.system_include`` returning the interpreter's prefix on Python 3.11 and later when the headers are not
installed; it now returns the sysconfig include path, which does not exist.
