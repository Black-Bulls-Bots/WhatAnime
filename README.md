# python-whatanime
[![Documentation Status](https://readthedocs.org/projects/whatanime/badge/?version=latest)](https://whatanime.readthedocs.io/en/latest/?badge=latest)

An unofficial python wrapper/library to interact with trace.moe.
I have no relationship with the API owner.

## Installation

### Install with `setup.py`:

    python setup.py build

### Install from pip:
Installing pip requires python version >=3.9

    pip install python-whatanime

## Example

```py
from WhatAnime import Client

client = Client(token=" ")
me = client.get_me()
url_search = client.search_url(url="sample.com/image.jpg", anilist=False)
result = client.search_file("image.jpeg")
```

## Documentaion 

* Documentation for this library can be found [here.](https://whatanime.readthedocs.io/en/latest/)
* Documentation for the API can be found [here](https://soruly.github.io/trace.moe-api/)