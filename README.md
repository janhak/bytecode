# Python Puzzles

Short snippets of Python code with some tricky questions! Knowledge of the `dis` module might be very helpful.

## Getting Started

Problems are split into:

* *fundamental* - great place to start if you haven't got much experience of working with Python and are still building a mental map how it works. They shouldn't be too taxing but will address important aspects of the language.

* *working* - they assume a reasonable familiarity with Python and are actually something you might encounter in your everyday code.

* *esoteric* - you might have a lifetime experience of Python coding and still scratch your head! While fun they do constitute corner cases rarely encountered.

### Prerequisites

You will need a jupyter notebook installed and a Python 3. If you don't know what you are doing follow the steps below:

* Open your terminal or command line or windows and type `pip --version` hopefully it should tell you a current version of pip followed by the path to your default Python installation and its version (If it is 3.x you are good to go)

* `pip install virtualenv` this will install virtualenv a tool to create isolated Python environments.

* `virtualenv notebook` will create a new folder `notebook` which contains Python executable and a copy of `pip` library.

* activate the new virtualenv on Unix type `source notebook\activate` on Windows `notebook\scripts\activate.bat`

* `pip install jupyter` this will install jupyter notebook and all of its dependencies in your new virtualenv.

* change directory to folder with this code samples and run `jupyter notebook`
