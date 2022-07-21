# Sorare Py
> A python wrapper for the Sorare API


## Install

#### Pip

`pip install sorarepy`

#### Conda

`conda install sorarepy`

## Login

To receieve your JWT and team name slug.

```python
l = LoginSorare(app_name="test_app", email="abc@gmail.com", password="abc", two_factor="12345")
token, club_name = l.login()
```
