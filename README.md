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
