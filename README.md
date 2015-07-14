# Data visualization with Plotly and programmatic back-ends

## Slideshow
[http://slides.com/mariannecorvellec/plotly-demo/](http://slides.com/mariannecorvellec/plotly-demo/)

## Setup

I suggest you run [Python 3](https://www.python.org/) because it's the future.
I strongly encourage you to make use of [virtual environments](https://virtualenv.pypa.io/).
Python 3 ships with `virtualenv` but, on Ubuntu 14.04, initiating a virtual environment with

    $ python3 -m venv ~/.virtualenv/plotly-demo-env

currently errors, so I had to use

    $ virtualenv --python=python3.4 ~/.virtualenv/plotly-demo-env

Yes, I tend to keep my virtualenvs under `~/.virtualenv/`; adapt to your own tree and practices.

    $ source ~/.virtualenv/plotly-demo-env/bin/activate
    $ pip install --upgrade pip
    $ pip install -r requirements.txt
    $ ipython notebook

Let me tell you that I read many [Stack Overflow](http://stackoverflow.com/) answers to have
[Jupyter](https://jupyter.org/) (IPython 3) run successfully the Python 3 kernel!
