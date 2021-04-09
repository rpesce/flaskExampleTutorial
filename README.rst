Flaskr
======

This was built by following the basic blog app built during the Flask tutorial: https://flask.palletsprojects.com/en/1.1.x/tutorial/

Official repo: https://github.com/rpesce/flask/tree/master/examples/tutorial


Install
-------

    # clone the repository
    $ git clone https://github.com/rpesce/flaskExampleTutorial.git
    $ cd flask-tutorial


Install Flaskr::

    $ pip install -e .

Run
---

::

    $ export FLASK_APP=flaskr
    $ export FLASK_ENV=development
    $ flask init-db
    $ flask run

Or on Windows cmd::

    > set FLASK_APP=flaskr
    > set FLASK_ENV=development
    > flask init-db
    > flask run

Open http://127.0.0.1:5000 in a browser.
