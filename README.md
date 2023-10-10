# Fountain Parser

## About

NOTE: Just forked from [fountain](https://github.com/Tagirijus/fountain) to add support for Fountain's built-in markup styling.

This Python script is a Fountain script parser, which converts .fountain files to Python objects.

* Modified by [Tagirijus](https://github.com/Tagirijus/)
* Ported to Python 3 by Colton J. Provias - cj@coltonprovias.com - [original code here](https://gist.github.com/ColtonProvias/8232624)
* based on `Fountain` by Nima Yousefi & John August; original code for Objective-C at [https://github.com/nyousefi/Fountain].

## Install

1. Make a pull request of this repo
3. Go into the repo-dir on your machine
2. `sudo python3 setup.py install`

## Usage

```
from fountain import fountain

F = fountain.Fountain(STRING)
```

This will make `F` into a Fountain object.
