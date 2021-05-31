# python_tutorial_pipenv_-_pytest


## terminal config 

```json
  {
    "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe"
  }
```

## pipenv install

```
  pip install pipenv
```

## pypenv comands

```properties
  pivenv install
  pipenv uninstall 
  pipenv shell
  pipenv run 
```

## pytest install in virtual env

```
  pipenv install pytest --dev
```

## pytest parametrize

```python
  @pytest.mark.parametrize(
          ["valu" , "result"],
          [("3+5", 8), ("2+4", 6), ("6*9", 42)]
          )
```

## install pylint in virtual env
```sh
  pipenv install pylint --dev
```

## pylint config

### generate file config 
```sh
  pylint --generate-rcfile > .pylintrc
```

### added comand in config 
```python
  init-hook='import sys; sys.path.append("/path/to/root")'
```



