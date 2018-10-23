# Tabby
* Test design Technique Modeling Tool

## Table of contents

* [Requrement](#Requrement)
* [Setup](#Setup)
* [Usage](#Usage)
* [Licence](#License)

---

## Requirement

* Using this tool, the test system can be modeled
* Support Test design Techniques (ISTQB)
* Easy start up
* Web System

## Setup

* Install tabby

```bash
git clone git@github.com:dandan611/tabby.git
cd tabby
mkvirtualenv --python=/usr/bin/python3.6 tabby
pip install -r requirements.txt
```

* Create super user

```bash
python manage.py createsuperuser
```

* Make pict for linux

```
git clone https://github.com/Microsoft/pict.git
sudo yum install gcc-c++
make
```

## Usage

```bash
workon tabby
cd tabby
python manage.py migrate
python manage.py runserver 0.0.0.0:8000
```

>>>
**Note**  

* Backgraund Start

```
python manage.py runserver 0.0.0.0:8000 &
```

* Stop

```
ps aux | grep python
kill -9 [PID]
```
>>>

## Licence
[MIT]
