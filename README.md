# Binder JupyterLab Development

Example repo to show how to have a binder work for JupyterLab and Lumino dev branches.

It clones a dev verion of lumino, links it to JupyterLab, builds a dev version of JupyterLab with those packages, and then starts JupyterLab in dev mode.

[![Binder](http://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/saulshanabrook/binder-jupyterlab-dev/master?urlpath=lab/)

Local testing:

```bash
pip install jupyter-repo2docker
jupyter-repo2docker .
```