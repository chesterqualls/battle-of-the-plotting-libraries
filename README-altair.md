# Python Battle of the Plotting Libraries - Altair

## Create and Check the Environment

I like to use virtualenvs still, these was done on Ubuntu Linux 18.04.  First
off, I create a virtualenv and install all the dependencies:

```bash
mkvirtualenv -p `which python3` altair
pip install -r requirements-altair.txt
```

Next, checking that I have a good version of Python and altair loads and is
`v4.0.0`.

```bash
python -c 'import sys; print(sys.version)'
3.6.9 (default, Nov  7 2019, 10:44:02) 
[GCC 8.3.0]
python -c 'import altair; print(altair.__version__)'
4.0.0
```

## Challenge Notebooks

The notebooks below contain my solutions to the challenges.  See notes for completeness:

* altair/altair-plot1.ipynb - Done
* altair/altair-plot2.ipynb - Done
* altair/altair-plot3.ipynb - Done
* altair/altair-plot4.ipynb
* altair/altair-plot5.ipynb
* altair/altair-plot6.ipynb
* altair/altair-plot7.ipynb
* altair/altair-plot8.ipynb


https://altair-viz.github.io/index.html
