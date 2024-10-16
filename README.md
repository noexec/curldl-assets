# PycURL Builds for Windows Platform

__NOTE:__ PyPI now has native Windows builds for
[PycURL 7.45.3](https://pypi.org/project/pycurl/7.45.3/#files),
so this module is not needed anymore.

To facilitate testing __curldl__ on Windows, win32 builds of PycURL
are required.

Since [PycURL](https://pycurl.io/) has no official win32 builds
at the time of writing this document, unofficial binaries by
Christoph Gohlke are used instead, as downloaded from his
[website](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pycurl).

The downloads have since [moved](https://github.com/cgohlke/win_arm64-wheels)
and the build were restricted to ARM64 architecture.
For this reason, only Python 3.8–3.11 Windows builds are provided here.

PycURL is dual licensed under the LGPL and an MIT/X derivative
license, so keeping these builds in the repo is fine.

## License

This project is released under the [GNU LGPL License Version 3](LICENSE.md) or any later version.
