This repository contains the entire Python Data Science Handbook, in the form of (free!) Jupyter notebooks.

cover image

How to Use this Book
Read the book in its entirety online at https://jakevdp.github.io/PythonDataScienceHandbook/

Run the code using the Jupyter notebooks available in this repository's notebooks directory.

Launch executable versions of these notebooks using Google Colab: Colab

Launch a live notebook server with these notebooks using binder: Binder

Buy the printed book through O'Reilly Media

About
The book was written and tested with Python 3.5, though other Python versions (including Python 2.7) should work in nearly all cases.

The book introduces the core libraries essential for working with data in Python: particularly IPython, NumPy, Pandas, Matplotlib, Scikit-Learn, and related packages. Familiarity with Python as a language is assumed; if you need a quick introduction to the language itself, see the free companion project, A Whirlwind Tour of Python: it's a fast-paced introduction to the Python language aimed at researchers and scientists.

See Index.ipynb for an index of the notebooks available to accompany the text.

Software
The code in the book was tested with Python 3.5, though most (but not all) will also work correctly with Python 2.7 and other older Python versions.

The packages I used to run the code in the book are listed in requirements.txt (Note that some of these exact version numbers may not be available on your platform: you may have to tweak them for your own use). To install the requirements using conda, run the following at the command-line:

$ conda install --file requirements.txt
To create a stand-alone environment named PDSH with Python 3.5 and all the required package versions, run the following:

$ conda create -n PDSH python=3.5 --file requirements.txt
You can read more about using conda environments in the Managing Environments section of the conda documentation.

License
Code
The code in this repository, including all code samples in the notebooks listed above, is released under the MIT license. Read more at the Open Source Initiative.

Text
The text content of the book is released under the CC-BY-NC-ND license. Read more at Creative Commons.