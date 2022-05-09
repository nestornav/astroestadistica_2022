# Astroestadística 2022

Repositorio para los trabajos realizados para el curso de [astroestadística](https://drive.google.com/file/d/1N06j0Q0MFSDMZMy_SsgG_wGSPmz0f8S2/view) dictado en la FaMAF.

**Profesor:** Dr. Mariano J. Dominguez

**Alumno:** Nestor Navarro


## Datasets

### Data clean and analysis
For this assigment I will use the data from the paper [Pipe3D, a pipeline to analyze Integral Field Spectroscopy Data: II. Analysis sequence and CALIFA dataproducts](https://arxiv.org/pdf/1602.01830.pdf). Getting the data avaible for tables 8, 9 and 10 from the paper.
These data can be downloaded as csv file using a FTP service from [here](http://califaserv.caha.es/CALIFA_WEB/public_html/?q=content/science-dataproducts). Inside the archive, scroll to the project name and select the three tables links.


## Run the project

As a recommended create a virtual environment to avoid messing up your system configuration and package.

### Virtualenvwrapper

```
pip install virtualenvwrapper
```

Set up some env vars
```
export WORKON_HOME=$HOME/.virtualenvs
export PROJECT_HOME=$HOME/Devel
source /usr/local/bin/virtualenvwrapper.sh
```
Now you are ready to use it! Let's create a virtualenv

```
mkvirtualenv virtualenv_name
```

If you are using python 2.7 as default also you can do the following command to use python3.8

```
mkvirtualenv $(which python3.8) virtualenv_name
```


### Install dependencies

```
pip install -r requirements.txt
```

## Running the notebook locally

```
jupyter notebook &
```

Then go to **localhost:8888** in your web browser

