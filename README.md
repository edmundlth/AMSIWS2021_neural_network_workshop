
# AMSIWS2021_neural_network_workshop

# Binder image
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/edmundlth/AMSIWS2021_neural_network_workshop/main)

A docker image of the main branch is built with [binder](https://mybinder.org/) and can be launched using the link above. That will allow you to run the included notebooks on a server hosted by [JupyterHub](https://jupyterhub.readthedocs.io/en/latest/)

# Local installation Guide
 1. Clone repository 
 ```
 git clone https://github.com/edmundlth/AMSIWS2021_neural_network_workshop
 ```
 2. Create Python virtual environment and install required packages specified in `Pipfile.lock` using [pipenv](https://pipenv.pypa.io/en/latest/)
 ```
 cd AMSIWS2021_neural_network_workshop
 pipenv install 
 ```
 3. Run `jupyter` within virtual environment
 ```
 pipenv run jupyter notebook
 ```
