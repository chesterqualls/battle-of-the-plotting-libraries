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

https://altair-viz.github.io/index.html