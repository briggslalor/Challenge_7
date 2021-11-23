# Challenge_7

ETF Analysis through a Web Application

This project contains an analysis of an ETF portfolio using dated imported from the contained database. The project demonstrates using SQL queries to access the data. With the data read into a dataframe, the daily and cumulative returns of a single asset, PYPL, and the entire ETF portfolio are analyzed and visualized using HVPlot. 


---

## Technologies

This project is built in Python and designed to be run in Jupyter Lab. In addition, it uses Voila and a web browser to display the project and output as a more digestable web application. In order to properly utilize the project, the following Python libraries will be used:

   [numpy](https://numpy.org/doc/stable/)

   [pandas](https://pandas.pydata.org/docs/)

   [hvplot](https://hvplot.holoviz.org/user_guide/index.html)

   [sqlalachemy](https://docs.sqlalchemy.org/en/14/)
   
   [voila](https://voila.readthedocs.io/en/stable/using.html)


---

## Installation Guide

This project requires the user to install the additional libraries not included in the base version of Python. To begin, the user must open an instance of Terminal or GitBash. In order to best run the project, a new development environment should be created using the following code:

```python
  conda create --name <environment name>
```

With the new environment created and activated, the user should install the pyviz, hvplot, sqlalchemy and voila libraries using the following lines of code:

```python
  
  conda install -c pyviz holoviews bokeh
  
  pip install SQLAlchemy
  
  pip install voila
```


---

## Usage

Once the proper libraries have been installed into a Python environment, the user can run the project by navigating into the Challenge_7 directory using the command line. When in the directory, the user can choose to run the application by opening an instance of Jupyter Lab or by opening a web application using the Voila library. This can be done by using the following code within the command line:

```
  voila etf_analyzer.ipynb
  
```

This command should output the following web page application:

![Screen record of outputed Voila application](Screen Recording 2021-11-23 at 7.42.17 AM.mov)


---

## Contributors

Briggs Lalor
email: briggsclalor@gmail.com

---

## License

MIT License

Copyright (c) [2021] [Briggs Lalor]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
