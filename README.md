# Go for Python Devs

This repository hosts the accompanying slides to my talk given
at PyMalta, held on 25/02/2020 at GiG offices in St Julian's

## Installing

The slides I used are an interactive notebook / slides.

To run it as a presentation locally, a few steps should be followed

### 1. Python

A number of python dependencies need to be installed:

* [Jupyter notebook][1]
* [RISE][2] - Jupyter/IPython Slideshow Extension

You can install these either by following the instructions via the links above, or using the requirements.txt file:

    pip install -r requirements.txt

### 2. Gophernotes

The gophernotes is a Go kernel for jupyter notebooks. We use it to make use of runnable go code cells in the notebook.

You can install it locally by following the instructions on their website: [https://github.com/gopherdata/gophernotes][3]

### 3. Reveal.js

To start the slides, open the notebook and use the shortcut (<kbd>alt+r</kbd>) to switch to the slide mode.

Do note that you can also view and exe ute the cells in the usual scroll top to bottom mode of the notebook.

### Attribution

All rights to images and videos used reserved to their creators.

[1]: https://jupyter.readthedocs.io/en/latest/install.html
[2]: https://rise.readthedocs.io/en/stable/
[3]: https://github.com/gopherdata/gophernotes