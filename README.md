

# MY-PY-ENV

![](https://img.shields.io/github/actions/workflow/status/joxborrow/my-py-env/test-jto-env.yml)

A long time ago in a galaxy far, far away there were
statistical/programming packages where individual packages did not need
to be individually installed and loaded. This environment file is meant
to be a collection of common packages for analysis and data science.
This README is meant to be the manual, linking to the documentation for
each key package.

This “manual” is organized by topic. If you feel something should be
added, please feel free to submit a pull request.

## Index

1.  [Programming Modules](#programming-modules)
2.  [Data compression](#data-compression)
3.  [Performance Management and
    Profiling](#performance-management-and-profiling)
4.  [Quality Control](#quality-control)
5.  [System and Environment](#system-and-environment)
6.  [Data Input and Output](#data-input-and-output)
7.  [Data Munging and Validation](#data-munging-and-validation)
8.  [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
9.  [Math, Statistics, ML, and Data
    Analytics](#math-statistics-ml-and-data-analytics)
10. [Time Series](#time-series)
11. [General Visualization and
    Reporting](#general-visualization-and-reporting)
12. [Graph, Diagrams and Technical Drawing Analysis and
    Visualization](#graph-diagrams-and-technical-drawing-analysis-and-visualization)
13. [Image and Video](#image-and-video)

## Environment Documentation

### Programming Modules

[Return to Index](#index)

| Module | Description |
|----|----|
| [argparse](https://docs.python.org/3/library/argparse.html#module-argparse)\* | Makes it easy to write user-friendly command-line interfaces |
| [click](https://click.palletsprojects.com/en/8.1.x/) | Package for creating beautiful command line interfaces in a composable way with as little code as necessary. |
| [alive-progress](https://github.com/rsalmei/alive-progress?tab=readme-ov-file#alive-progress) | Beautiful progress bars in python. |
| [colorama](https://github.com/tartley/colorama) | Colored terminal output |
| [re](https://docs.python.org/3/library/re.html#module-re)\* | Provides regular expression matching operations similar to those found in Perl |
| [smtplib](https://docs.python.org/3/library/smtplib.html#module-smtplib)\* | Defines an SMTP client session object that can be used to send mail to any internet machine with an SMTP or ESMTP listener daemon |
| [datetime](https://docs.python.org/3/library/datetime.html#module-datetime)\* | Supplies classes for manipulating dates and times |
| [collections](https://docs.python.org/3/library/collections.html#)\* | Implements specialized container datatypes providing alternatives to Python’s general purpose built-in containers, [`dict`](https://docs.python.org/3/library/stdtypes.html#dict "dict"), [`list`](https://docs.python.org/3/library/stdtypes.html#list "list"), [`set`](https://docs.python.org/3/library/stdtypes.html#set "set"), and [`tuple`](https://docs.python.org/3/library/stdtypes.html#tuple "tuple"). |

### Data compression

[Return to Index](#index)

| Module | Description |
|----|----|
| [zlib](https://docs.python.org/3/library/zlib.html#module-zlib)\* | Functions in this module allow compression and decompression, using the zlib library. |
| [gzip](https://docs.python.org/3/library/gzip.html#module-gzip)\* | Provides a simple interface to compress and decompress files just like the GNU programs gzip and gunzip. |
| [bz2](https://docs.python.org/3/library/bz2.html#module-bz2)\* | Provides a comprehensive interface for compressing and decompressing data using the bzip2 compression algorithm. |
| [lzma](https://docs.python.org/3/library/lzma.html#module-lzma)\* | Provides classes and convenience functions for compressing and decompressing data using the LZMA compression algorithm |
| [zipfile](https://docs.python.org/3/library/zipfile.html#module-zipfile)\* | Provides tools to create, read, write, append, and list a ZIP file. |
| [tarfile](https://docs.python.org/3/library/tarfile.html#module-tarfile)\* | Makes it possible to read and write tar archives, including those using gzip, bz2 and lzma compression. |

### Performance Management and Profiling

[Return to Index](#index)

| Module | Description |
|----|----|
| [timeit](https://docs.python.org/3/library/timeit.html#module-timeit) | A simple way to time small bits of Python code. |
| [profile](https://docs.python.org/3/library/profile.html#module-profile) | A pure Python module whose interface is imitated by [`cProfile`](https://docs.python.org/3/library/profile.html#module-cProfile "cProfile"), but which adds significant overhead to profiled programs. If you’re trying to extend the profiler in some way, the task might be easier with this module |
| [cProfile](https://docs.python.org/3/library/profile.html#module-profile) | A C extension with reasonable overhead that makes it suitable for profiling long-running programs. Based on `lsprof.` |
| [pstats](https://docs.python.org/3/library/profile.html#module-pstats) | Formats reports from profile and cProfile modules. |

### Quality Control

[Return to Index](#index)

| Module | Description |
|----|----|
| [doctest](https://docs.python.org/3/library/doctest.html#module-doctest) | Searches for pieces of text that look like interactive Python sessions, and then executes those sessions to verify that they work exactly as shown. Form of unit testing in docstrings |
| [unittest](https://docs.python.org/3/library/unittest.html#module-unittest) | Unit testing framework |

### System and Environment

[Return to Index](#index)

| Package | Description |
|----|----|
| [os](https://docs.python.org/3/library/os.html#module-os)\* | Provides a portable way of using operating system dependent functionality |
| [sys](https://docs.python.org/3/library/sys.html#module-sys)\* | Provides access to some variables used or maintained by the interpreter and to functions that interact strongly with the interpreter. |
| [shutil](https://docs.python.org/3/library/shutil.html#module-shutil)\* | Offers a number of high-level operations on files and collections of files. In particular, functions are provided which support file copying and removal. |
| [glob](https://docs.python.org/3/library/glob.html#module-glob)\* | Finds all the pathnames matching a specified pattern according to the rules used by the Unix shell |
| [pip](https://pip.pypa.io/en/stable/index.html) | Package installer for python |
| [pycairo](https://pycairo.readthedocs.io/en/latest/) | Python library to provide bindings for the cairo graphics library |
| [jupyter](https://docs.jupyter.org/en/latest/) | Interactive environment for computing |
| [python-dotenv](https://saurabh-kumar.com/python-dotenv/) | Rad key-value pairs from a `.env` file and can set them as environment variables |
| [pylint](https://www.pylint.org/) | Analyses your code without actually running it. It checks for errors, enforces a coding standard, looks for code smells, and can make suggestions about how the code could be refactored |
| [numba](https://numba.readthedocs.io/en/stable/index.html) | A compiler for Python array and numerical functions that gives you the power to speed up your applications with high performance functions written directly in Python. |

### Data Input and Output

[Return to Index](#index)

| Package | Description |
|----|----|
| [requests](https://requests.readthedocs.io/en/latest/) | an elegant and simple HTTP library for Python, built for human beings |
| [urllib.request](https://docs.python.org/3/library/urllib.request.html#module-urllib.request)\* | Defines functions and classes which help in opening URLs |
| [pyodbc](https://github.com/mkleehammer/pyodbc/wiki) | an open source Python module that makes accessing ODBC databases simple |
| [sqlalchemy](https://docs.sqlalchemy.org/en/20/) | Python SQL toolkit and Object Relational Mapper that gives application developers the full power and flexibility of SQL |
| [deltalake](https://delta-io.github.io/delta-rs/) | provides the capability to read, write, and manage [Delta Lake](https://delta.io/) tables |
| [pyarrow](https://arrow.apache.org/docs/python/index.html) | A cross-language development platform for in-memory analytics |
| [xlsxwriter](https://xlsxwriter.readthedocs.io/) | Module that can be used to write text, numbers, formulas and hyperlinks to multiple worksheets in an Excel 2007+ XLSX file. It supports features such as formatting and much more. |
| [openpyxl](https://openpyxl.readthedocs.io/en/stable/index.html) | Library to read/write Excel 2010 xlsx/xlsm/xltx/xltm files. |
| [json](https://docs.python.org/3/library/json.html#module-json)\* | manage JSON files |
| [faker](https://faker.readthedocs.io/en/master/#how-to-use-with-factory-boy) | Generates fake data |
| [holidays](https://python-holidays.readthedocs.io/en/latest/) | A fast, efficient Python library for generating country- and subdivision- (e.g. state or province) specific sets of government-designated holidays on the fly. |

### Data Munging and Validation

[Return to Index](#index)

| Package | Description |
|----|----|
| [polars\[all\]](https://docs.pola.rs/) - [🗒️](assets/Polars_cheat_sheet.pdf "Cheatsheet") | Embarassingly parallel data munging |
| [pandas](https://pandas.pydata.org/docs/) | data munging |
| [ibis](https://ibis-project.org/) | Defines a Python dataframe API that executes on any query engine – the frontend for any backend data platform, with 20+ backends today. |
| [duckdb](https://duckdb.org/docs/api/python/overview) | Fast in process analytical database. Integrates with polars and other arrow based packages. |
| [snowflake-snowpark-python](https://docs.snowflake.com/en/developer-guide/snowpark/python/index) | data munging in Snowflake |
| [pandera](https://pandera.readthedocs.io/en/latest/) | data validation |
| [miceforest](https://miceforest.readthedocs.io/en/latest/) | Impute missing values |

### Exploratory Data Analysis (EDA)

[Return to Index](#index)

| Package | Description |
|----|----|
| [pyskim](https://github.com/kpj/pyskim) | a package for EDA at the commandline |
| [sweetviz](https://github.com/fbdesignpro/sweetviz) | Open-source Python library that generates beautiful, high-density visualizations to kickstart EDA. |
| [missingno](https://github.com/ResidentMario/missingno) | A small toolset of flexible and easy-to-use missing data visualizations and utilities |

### Math, Statistics, ML, and Data Analytics

[Return to Index](#index)

| Module | Submodule | Description |
|----|----|----|
| [math](https://docs.python.org/3/library/math.html#module-math)\* |  | Provides access to the mathematical functions defined by the C standard. Part of the python standard library. |
| [sympy](https://docs.sympy.org/latest/index.html) |  | Library for symbolic mathematics |
| [statistics](https://docs.python.org/3/library/statistics.html#module-statistics)\* |  | Provides functions for calculating mathematical statistics of numeric real valued data. Part of the python standard library |
| [random](https://docs.python.org/3/library/random.html#module-random)\* |  | Implements pseudo-random number generators for various distributions. Part of the python standard library. |
| [statsmodels](https://www.statsmodels.org/stable/index.html) |  | Estimation of many different statistical models, as well as for conducting statistical tests, and statistical data exploration |
| [scipy](https://docs.scipy.org/doc/scipy/) |  | SciPy is a collection of mathematical algorithms and convenience functions |
|  | [scipy.stats](https://docs.scipy.org/doc/scipy/reference/stats.html#statsrefmanual) | This module contains a large number of probability distributions, summary and frequency statistics, correlation functions and statistical tests, masked statistics, kernel density estimation, quasi-Monte Carlo functionality, and more. This is a supplement to the base packages [statistics](https://docs.python.org/3/library/statistics.html#module-statistics). |
|  | [scipy.linalg](https://docs.scipy.org/doc/scipy/reference/linalg.html#module-scipy.linalg) | linear algebra library |
| [patsy](https://patsy.readthedocs.io/en/latest/) |  | Package for describing statistical models and building design matrices |
| [numpy](https://numpy.org/doc/) |  | NumPy is the fundamental package for scientific computing in Python |
| [sklearn](https://scikit-learn.org/stable/user_guide.html) |  | Simple and efficient tools for predictive data analysis, including ML |
|  | [sklearn.preprocessing](https://scikit-learn.org/stable/modules/preprocessing.html) | Provides several common utility functions and transformer classes to change raw feature vectors into a representation that is more suitable for the downstream estimators. |
|  | [sklearn.feature_selection](https://scikit-learn.org/stable/modules/feature_selection.html) | Used for feature selection/dimensionality reduction on sample sets, either to improve estimators’ accuracy scores or to boost their performance on very high-dimensional datasets |
| [nltk](https://www.nltk.org/) |  | A leading platform for building Python programs to work with human language data |
| [quantecon](https://quanteconpy.readthedocs.io/en/latest/) |  | Open source python library for economic modeling |
| [ruptures](https://centre-borelli.github.io/ruptures-docs/) |  | A Python library for off-line change point detection |
| [spectrum](https://pyspectrum.readthedocs.io/en/latest/#) |  | is a Python library that contains tools to estimate Power Spectral Densities based on Fourier transform, Parametric methods or eigenvalues analysis |

### Time Series

[Return to Index](#index)

| Module | Submodule | Descriptions |
|----|----|----|
| [sktime](https://www.sktime.net/en/latest/index.html) |  | A unified framework for machine learning with time series |
| [statsforecast](https://nixtlaverse.nixtla.io/statsforecast/index.html) |  | A collection of popular univariate time series forecasting models optimized for high performance and scalability |
| [mlforecast](https://nixtlaverse.nixtla.io/mlforecast/index.html) |  | Scalable machine learning for time series forecasting |

### General Visualization and Reporting

[Return to Index](#index)

| Module | Description |
|----|----|
| [altair](https://altair-viz.github.io/getting_started/overview.html) | A declarative statistical visualization library for Python, based on [Vega](http://vega.github.io/vega) and [Vega-Lite](http://vega.github.io/vega-lite). |
| [matplotlib](https://matplotlib.org/stable/index.html) | Comprehensive library for creating static, animated, and interactive visualizations |
| [seaborn](https://seaborn.pydata.org/) | Provides a high-level interface for drawing attractive and informative statistical graphics. |
| [plotnine](https://plotnine.org/) | An implementation of a *grammar of graphics* in Python based on [ggplot2](https://ggplot2.tidyverse.org/). |
| [holoviews](https://holoviews.org/) | makes data analysis an viualization seamless and simple. |
| [patchworklib](https://github.com/ponnhide/patchworklib) | A universal composer of matplotlib-related plots (simple matplotlib plots, Seaborn plots (both axis-level and figure-level), and plotnine plots). |
| [itables](https://mwouts.github.io/itables/quick_start.html#) | Display your tables as interactive html [DataTables](https://datatables.net/) that you can sort, paginate, scroll or filter. |
| [great_tables](https://posit-dev.github.io/great-tables/articles/intro.html) | absolutely delightful static table making in python |
| [quarto](https://quarto.org/) | An open-source scientific and technical publishing system |
| [datashader](https://datashader.org/index.html) | A graphics pipeline system for creating meaningful representations of large datasets quickly and flexibly. |
| [colorcet](https://colorcet.holoviz.org/) | A collection of perceptually accurate 256-color colormaps for use with Python plotting programs. |
| [wordcloud](https://github.com/amueller/word_cloud) | A little word cloud generator in Python. |
| [yellowbrick](https://www.scikit-yb.org/en/latest/index.html#) | Machine Learning Visualization: Extends the Scikit-Learn API to make model selection and hyperparameter tuning easier. Under the hood, it’s using Matplotlib. |

### Graph, Diagrams and Technical Drawing Analysis and Visualization

[Return to Index](#index)

| Modules | Description |
|----|----|
| [mermaid-py](https://github.com/ouhammmourachid/mermaid-py) | an interface for the famous [mermaid-js](https://mermaid.js.org/) library that uses scripts to create diagrams |
| [igraph](https://python.igraph.org/en/stable/) | A fast open source python library to analyze graphs/networks |
| [pyvis](https://pyvis.readthedocs.io/en/latest/index.html) | An python library wrapping the [VisJS](https://visjs.org/) javascript library for [network visualization](https://visjs.github.io/vis-network/examples/). |
| [networkx](https://networkx.org/documentation/stable/) | A python package for the creation, manipulation, and study of the structure, dynamics, and functions of complex networks. |
| [hiveplotlib](https://hiveplotlib.readthedocs.io/stable/index.html) | Generate well-defined figures, allowing for reliable, visual explorations of network data. It avoids “hairball” plots. |
| [graphviz](https://github.com/xflr6/graphviz) | Facilitates the creation and rendering of graph descriptions in the [DOT](https://www.graphviz.org/doc/info/lang.html) language of the [Graphviz](https://www.graphviz.org/) graph drawing software |
| [diagrams](https://diagrams.mingrammer.com/) | Draw the cloud system architecture in Python code. |

### Image and Video

[Return to Index](#index)

| Modules | Description |
|----|----|
| [pillow](https://pillow.readthedocs.io/en/stable/) | adds image processing capabilities to your Python interpreter. |
| [ffmpeg-python](https://kkroening.github.io/ffmpeg-python/) | Use ffmpeg from python. |

\* Part of the python standard library
