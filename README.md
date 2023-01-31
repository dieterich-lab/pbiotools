# pbiotools [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/pbiotools/README.html) [![pypi releases](https://img.shields.io/pypi/v/pbiotools.svg)](https://pypi.org/project/pbiotools) [![CI](https://github.com/dieterich-lab/pbiotools/actions/workflows/ci.yml/badge.svg)](https://github.com/dieterich-lab/pbiotools/actions/workflows/ci.yml)

The **pbiotools** package provides miscellaneous bioinformatics and other utilities for Python 3. It is required for the installation of [Rp-Bp](https://github.com/dieterich-lab/rp-bp).

## Installation

If required, set up the conda channels as described [here](https://bioconda.github.io/#usage), and install with

```
conda install pbiotools
```

The package is also available on [PyPI](https://pypi.org/project/pbiotools/).

You can also get a container with **pbiotools** pre-installed

```
# docker or...
docker pull quay.io/biocontainers/pbiotools:<tag>
# ... singularity
singularity pull pbiotools.sif docker://quay.io/biocontainers/pbiotools:<tag>
```

There is no _latest_ tag, you need to specify the version tag. See [pbiotools/tags](https://quay.io/repository/biocontainers/pbiotools?tab=tags) for valid values for <tag>.

## Documentation

There is currently limited [documentation](docs/usage-instructions.md).

## How to report issues

Bugs and issues should be reported in the [bug tracker](https://github.com/dieterich-lab/pbiotools/issues). Follow the instructions and guidelines given in the template.
