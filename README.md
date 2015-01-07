theory14
========

Course repository for Topics in Economic Theory 2014

## Materials

* Nov 5
  * [Updated solutions for Finite Markov Chains in quant-econ.net](http://nbviewer.ipython.org/github/oyamad/theory14/blob/master/markov/finite_mc_solutions_updated.ipynb)

* Jan 7  
  Examples from Miranda and Fackler:
  * [7.6.2: Asset Replacement](http://nbviewer.ipython.org/github/oyamad/mdp/blob/master/mdp_ex_MF_7_6_2.ipynb)
  * [7.6.3: Asset Replacement with Maintenance](http://nbviewer.ipython.org/github/oyamad/mdp/blob/master/mdp_ex_MF_7_6_3.ipynb)
  * [7.6.5: Water Management](http://nbviewer.ipython.org/github/oyamad/mdp/blob/master/mdp_ex_MF_7_6_5.ipynb)


## Homework

* [Homework 1](hw01.md)
* [Homework 2](hw02.md)
* [Homework 3](hw03.md)
* [Homework 4](hw04.md)
* [Homework 5](hw05.md)
* [Homework 6](hw06.md)
* [Homework 7](hw07.md)


## How to install the latest version of QuantEcon (updated 2014/11/4)

We will use the QuantEcon library version 0.1.6 (or above).

* Install [Anaconda](http://continuum.io/downloads);
  follow this [instruction](http://quant-econ.net/py/getting_started.html#installing-anaconda)
  if necessary.

* To install the latest version of
  the [QuantEcon](https://github.com/QuantEcon/QuantEcon.py) package,
  enter

  ```
  pip install quantecon
  ```

  at a Terminal.

  If you have already installed an older version of QuantEcon,
  add a `-U` option:

  ```
  pip install quantecon -U
  ```

* To verify the version 0.1.6 has been successfully installed,
  enter

  ```
  python -c "import quantecon; print quantecon.__version__"
  ```

  at a Terminal.
  The version number will be printed.

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
  pip install quantecon
  ```

* If you want to try the development version, enter

  ```
  pip install git+https://github.com/QuantEcon/QuantEcon.py
  ```

  (with `-U` if necessary),
  instead of `pip install quantecon`.
