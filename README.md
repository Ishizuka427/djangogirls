## Django Girls

[![CircleCI](https://circleci.com/gh/suwa3/djangogirls.svg?style=svg)](https://circleci.com/gh/suwa3/djangogirls)
↑修正する

### How to use
```sh
git clone git@github.com:Ishizuka427/djangogirls.git
cd djangogirls
python3 -V                 
Python 3.9.7
```
### myvenv
```sh
python3 -m venv myvenv
source myvenv/bin/activate
```
### Django v2.2.5 Install
```sh
(myvenv) ~$ python -m pip install --upgrade pip
(myvenv) ~$ sed -e "s/Django~=.*/Django~=2.2.5/" requirements.txt
(myvenv) ~$ pip install -r requirements.txt
```
### runserver
```
export MY_SECRET_KEY='20!o+*************************'
python3 manage.py runserver
```

http://127.0.0.1:8000/

### admin
http://127.0.0.1:8000/admin/
