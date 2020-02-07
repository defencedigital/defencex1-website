# DefenceX 0 conference website

A simple Flask app that uses a free Bootstrap theme.

## Contributing

This website won't be around for long, but if you want to contribute then just raise a pull request and we'll get back to you as soon as we can.

## Getting started

You'll need Python 3 installed and on your PATH. FWIW, I'm using 3.8.

Steps (if you're using Windows, you're on your own):

1. `git clone git@github.com:defencedigital/defencex0-website.git` or over SSH if you prefer
2.  Set up a virtual environment in the root `defencex0-website` folder

`python3 -m venv venv`

3. Activate the environment

`source venv/bin/activate`

4. Install dependencies

`pip install -r requirements.txt`

## Running the application locally

With your virtual environment activated (see above), from the root folder, run the following commands:

`export FLASK_APP=main.py`

`export FLASK_ENV=development` < this will ensure that the debugger is running in your terminal

`flask run` < run's the app. The URL to visit will be shown in your terminal. Press `Ctrl + C` to stop the local server.
