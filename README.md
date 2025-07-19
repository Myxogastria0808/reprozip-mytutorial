## Setup

1. install poetry and poetry-plugin-shell 

```sh
# install pipx
sudo apt update
sudo apt install pipx
pipx ensurepath
# install poetry
pipx install poetry
# install poetry-plugin-shell
poetry self add poetry-plugin-shell
```

2. clone this repository

```sh
git clone https://github.com/Myxogastria0808/reprozip-mytutorial.git
```

## How to use reprozip

1. Trace program written in python

reprozip generate .reprozip-trace directory.

```sh
reprozip trace python3 <relative path of python file>
```

e.g. `./src/simple/main.py`

```sh
reprozip trace python3 ./src/simple/main.py
```

2. Create *.rpz file

```sh
reprozip pack <filename>.rpz 
```

e.g. create `./src/simple/simple-linux.rpz`

```sh
reprozip pack ./src/simple/simple-linux.rp
```

# Unpack and run *.rpz

1. Check compatible 

## Documentation

http://docs.reprozip.org/en/1.x/index.html

