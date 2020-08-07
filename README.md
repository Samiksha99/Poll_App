# Poll_App

## Setup
The first thing to do is to clone the repository:

$ git clone https://github.com/Samiksha99/Poll_App.git

$ cd Poll_App

Create a virtual environment to install dependencies in and activate it:

> $ py -m venv env

> $ .\env\Scripts\activate

Then install the dependencies:

> (env)$ pip install -r requirements.txt

Note the (env) in front of the prompt. This indicates that this terminal session operates in a virtual environment set up by virtualenv.

Once pip has finished downloading the dependencies:

> (env)$ cd project

> (env)$ python manage.py runserver

And navigate to http://127.0.0.1:8000/
