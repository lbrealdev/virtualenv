# Virtualenv


## Install

```
pip install virtualenv

pip install virtualenvwrapper-win
```

## Create virtualenv

### Execute virtualenv or mkvirtualenv, but creating with mkvirtualenv will create your env in C:\Users\'Username'\Evns\. With virtualenv will create your env in your current directory.

```
virtualenv testspy


mkvirtualenv testpy
```

### Activate Windows

```
activate.bat

or

.\Scripts\activate
```

### Deactivate Windows

```
deactivate.bat

or

.\Scripts\deactivate.bat
```

For check your env execute:

```
pip list

pip        20.0.2
setuptools 45.2.0
wheel      0.34.2
```
You can see the difference of your packages list Python installed on virtualenv with packages Python installed in your system.  
