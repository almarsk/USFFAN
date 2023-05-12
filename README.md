instalation steps:

get the repository
```sh
git clone https://github.com/almarsk/USFFAN.git
```
go into your directory
```sh
cd USFFAN
```
create a virtual environment
```sh
python3 -m venv venv
```
update pip
```sh
venv/bin/pip install -U pip
```
install packages
```sh
venv/bin/pip install -r setup/requirements.txt
```
import and process data, print hint
```sh
venv/bin/python setup/setup.py
```
start exploring
```sh
venv/bin/python explore.py make word of your choice
```
