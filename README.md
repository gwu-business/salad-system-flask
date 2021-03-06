# Salad System (Flask Implementation)

An example database-connected web app,
 using the [Flask](http://flask.pocoo.org/) Python library.

Represents a partial implementation of [Salad System Requirements](https://github.com/gwu-business/salad-system-requirements).

Based on [Salad System (Python Implementation)](https://github.com/gwu-business/salad-system-py).

## Usage

```` sh
git clone git@github.com:gwu-business/salad-system-flask.git
cd salad-system-flask/
````

Setup database (requires mysql).

```` sh
mysql -uroot -p -e "DROP DATABASE IF EXISTS salad_db; CREATE DATABASE salad_db;"
mysql -uroot -p salad_db < schema.sql
````

Install package dependencies.

```` sh
pip install -r requirements.txt
````

Run local web server, and visit http://localhost:5000/ in a browser.

```` sh
python hello.py
````

![a screenshot depicting a menu page with an alert message at the top which reads: 'thanks for adding a menu item'](static/images/menu-screenshot.png)

## [License](LICENCE)
