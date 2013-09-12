
# pyvXRAY

An ABAQUS plug-in for the creation of virtual x-rays from 3D finite element bone models

Copyright 2013, Michael Hogg (michael.christopher.hogg@gmail.com)

MIT license - See license.txt for details

## Requirements

* ABAQUS >= 6.11
* Python Image Library (PIL) >= 1.1.6

NOTES:
1. ABAQUS is a commerical software package and requires a license from [Simulia](http://www.3ds.com/products-services/simulia/overview/)
2. Python and numpy are heavily used by pyvXRAY. These are built in to ABAQUS.

For building cython modules from source (e.g. if not using versions with pre-built modules):
* A c compiler. The msvc compiler works best on Windows.
* Cython >= 0.17 (optional, as c files generated by Cython are provided )

##Documentation

See website for information on pyvXRAY: http://pypi.python.org/pypi/pyvXRAY

## Help
 
For help post a question on the `project support page <https://groups.google.com/forum/#!forum/pyvxray>`_