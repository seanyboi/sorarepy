# Sorare Py
> A python wrapper for the Sorare API


## Requirements

`python >= 3.7`

## Install

`pip install sorarepy`

`conda install -c seanyboi sorarepy`

## How to use

Import

```
from sorarepy.login import LoginSorare
```


    ---------------------------------------------------------------------------

    ImportError                               Traceback (most recent call last)

    Input In [15], in <cell line: 1>()
    ----> 1 from sorarepy.login import LoginSorare


    ImportError: cannot import name 'LoginSorare' from 'sorarepy.login' (/Users/sean/Development/Personal/sorare_py/sorarepy/login.py)


## Login

To receieve your JWT and team name slug.

```
l = LoginSorare(app_name="test_app", email="abc@gmail.com", password="abc", two_factor="12345")
token, club_name = l.login()
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    Input In [16], in <cell line: 1>()
    ----> 1 l = LoginSorare(app_name="test_app", email="abc@gmail.com", password="abc", two_factor="12345")
          2 token, club_name = l.login()


    NameError: name 'LoginSorare' is not defined


## Contributions

If there is any particular data you wish to be added to the package please let me know!

Issues and pull requests are always welcome.

## Acknowledgements

A huge massive thanks to Sorare for open sourcing their API. 
Without them this package wouldn't be possible so please go check them out!

Sorare - https://sorare.com

## Disclaimer

We do not store any personal information like email, password or your two factor password, that is down to you to keep safe!
