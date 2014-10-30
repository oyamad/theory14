theory14
========

Course repository for Topics in Economic Theory 2014

* Install [Anaconda](http://continuum.io/downloads);
  follow this [instruction](http://quant-econ.net/py/getting_started.html#installing-anaconda)
  if necessary.
* To install the latest development version of
  the [QuantEcon](https://github.com/QuantEcon/QuantEcon.py) package,
  enter
  ```
  pip install git+https://github.com/QuantEcon/QuantEcon.py
  ```
  at a Terminal.
* If you want to build a separate Python environment for QuantEcon,
  follow Steps 2 and 3 in the Wiki page
  "[Creating a Conda development environment](https://github.com/QuantEcon/QuantEcon.py/wiki/Creating-a-Conda-development-environment)",
  before entering the command above.
  That is, enter
  ```
  conda create -n quantecon-dev anaconda
  ```
  and
  ```
  source activate quantecon-dev
  ```
  and then
  ```
  pip install git+https://github.com/QuantEcon/QuantEcon.py
  ```
