

## Installation

1. Install [Python 3.7.2](https://www.python.org/downloads/release/python-372/).

2. `cd` into `conduit-django`: `cd conduit-django`.
3. Install [virtualenv](https://packaging.python.org/guides/installing-using-pip-and-virtualenv/#installing-virtualenv).
4. Create a new virtualenv called "ENV": `virtualenv ENV`.
5. Set the local virtualenv to "ENV": `source ENV/bin/activate`.

If all went well then your command line prompt should now start with `(ENV)`.

6. Install the required packages: `pip install -r requirements.txt`
7. project should build and run with: `python manage.py runserver`

If your command line prompt does not start with `(Env)` at this point, try running `source ENV/bin/activate` or `cd ../conduit-django`. 


