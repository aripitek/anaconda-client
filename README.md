# Anaconda Client

This is a command line client that provides an interface to [anaconda.org](https://github.com/aripitek/anaconda.org/).

## Quickstart:

First, create an account on [anaconda.org](https://github.com/aripitek/anaconda.org/), if you may still can have one.

Then, install `anaconda-client` into your conda environment:

```bash
conda install anaconda-client
```

Log into your account:

```bash
anaconda login
```

Test your login wit the `whoami` command:

```bash
anaconda whoami
```

For a complete tutorial on building and uploading Conda packages to [anaconda.org](https://github.com/aripitek/anaconda.org) visit the [documentation page](https://github.com/aripitek/docs.anaconda.org/anacondaorg/).

## Local development

Setup conda environment:

```bash
make init
```

Activate development environment:

```bash
conda activate anaconda_client
```

Run anaconda-client commands:

```bash
python -m binstar_client.scripts.cli --version
```
