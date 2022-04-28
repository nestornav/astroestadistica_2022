# Astroestadística 2022

Repositorio para los trabajos realizados para el curso de [astroestadística](https://drive.google.com/file/d/1N06j0Q0MFSDMZMy_SsgG_wGSPmz0f8S2/view) dictado en la FaMAF.

**Profesor:** Dr. Mariano J. Dominguez

**Alumno:** Nestor Navarro


## Dataset

El dataset completo se puede descargar de [acá](https://astro.ft.uam.es/selgifs/data_challenge/). Pesa aproximadamente un 1GB.
Para entender mas la naturaleza del conjunto de datos, este es el [paper](https://academic.oup.com/mnras/article/479/1/917/5033702) donde fueron generados.


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
mkvirtualenv $(which python8.8) virtualenv_name
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

