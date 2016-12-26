# Hello, Python! 

----


## Day 1 - Summary
1. Installation 
    1. Plain Python  - [The Official Python Installation](https://www.python.org/downloads/)
    2. [**Anaconda Python Distribution**](https://www.continuum.io/downloads)     [*Recommended*]  as it contains most of the required modules
    3. [Intel Distribution](https://software.intel.com/en-us/intel-distribution-for-python) - A super set of Anaconda with various optimization for Intel Architecture


2. Syntax
   1. No semicolons for line separation!!
   2. No parenthesis for blocks!!! 
   3. **`Indentation`** 
   

3. Variables and types
   1. Numeric - `Integers, Long, Float , Complex `
   2. Boolean - `True , False`
   3. Strings and operations on strings
   4. Conversion from one type to another - `int(), float() , str() , bool() `

4. Keywords

5. Sequences 
   1. Lists 
   2. Tuples
   3. Sets
   4. Dictionaries
   
5. Control flow 
    1. if elif else
    2. NO switch!! - [either use if elif else  OR  use dictionary mappings](https://www.pydanny.com/why-doesnt-python-have-switch-case.html) 
    
6. Loops - for , while ; break , continue 

7. Functions 

8. Files 

9. Modules - os , subprocess , random , sys

-----


## Day2 - Summary 
1. Files - reading and writing

2. Using the with keyword - context managers 

3. Operations on dictionaries , looping through contents of a dictionary

4. json - reading and writing json documents 

5. Exception Handling - `try  except  finally raise`

6. Classes  
    1. Creating a `class`
    2. Object creation
    3. `__init__` method - to initialize attributes
    4. Dunders methods to be uploaded for operator overloading   ex : `__str__`    (Dunders is short form for Double Underscores)

7. **datetime**  module to deal with date,time,datetime objects

8. **requests** module to make HTTP Requests

9. Connecting to a database and querying - using pyodbc/pypyodbc

10. Creating our own modules and packages.

11. Revisiting functions
    1. Lambdas
    2. Functions in python as first class citizens - can be passed , returned as any other objects.
    3. Decorators - To do some pre-work before a function is called. Using the @ construct for decorating 
    4. Functional programming constructs  - `map(),reduce(),filter()  and the operator module` 
    5. [Functional Programming With Python](http://kachayev.github.io/talks/uapycon2012/)

12. Mini project - **py_shell** - Implementing our own mini shell using the module os 


------


### Installing packages 
* Using pip 
  
     pip install [pkg_name]
   
     pip --proxy [proxy_url] install [pkg_name]
   
     example : `pip --proxy <proxy_url> install requests`


* Using conda  
     conda install [pkg_name] 


----


### Must Reads
1.   [PEP-8](https://www.python.org/dev/peps/pep-0008/) Python Style Guide - 
2.  [Doing things the Pythonic way](http://python.net/~goodger/projects/pycon/2007/idiomatic/handout.html)  -**Idiomatic Python**
3.  [Standard Library Functions for Python2.x](https://docs.python.org/2/library/functions.html)
4.  [Standard Library Functions for Python3.x](https://docs.python.org/3/library/functions.html)
5.  [LearnPython](http://www.learnpython.org/) - A good online code playground to learn the language. 
6.  [Learn Python the Hard Way](https://learnpythonthehardway.org/book/) 
7.  [**The Hitchhiker’s Guide to Python!**](http://docs.python-guide.org/en/latest/) - A fully comprehensive site on most of the things required on the journey to be an awesome Python developer
8. [Python for you and me](http://pymbook.readthedocs.io/en/latest/index.html) - Great content to get started with python development 
9. [Python_syntax_and_semantics](https://en.wikipedia.org/wiki/Python_syntax_and_semantics)


### References 
1. [PEP - Python Enhancement Proposals](https://www.python.org/dev/peps/)
2. [Python Course.eu](http://www.python-course.eu/) - Very good collection on basic and advanced topics.
3. [IntoPython](https://intopython.com/)  - CPython Code Walkthrough 
4. [2 vs 3](http://python3porting.com/differences.html)  -  Difference between Python 2 and 3
5. [datetime](http://strftime.org/) -  Datetime formating 
5. [conda](http://conda.pydata.org/docs/_downloads/conda-cheatsheet.pdf) - Conda cheatsheet
6. [Anandalogy Python Practice book](http://anandology.com/python-practice-book/) - A good resource to refresh your knowledge.Also has a good content related to functional programming. 
7. [DiveIntoPython](http://www.diveintopython3.net/)


### Advanced and/or interesting 
1. Call by Reference or value - [Neither](https://jeffknupp.com/blog/2012/11/13/is-python-callbyvalue-or-callbyreference-neither/)
2. [Decorators](https://wiki.python.org/moin/PythonDecorators)


-------
### Additional Resources 

#### Resources for Data Science 
1. [Awesomestats.in](http://www.awesomestats.in/python/)  - Concise jupyter notebook examples to do data science
2.  [Analytics Vidhya Python Learning Path](https://www.analyticsvidhya.com/learning-paths-data-science-business-analytics-business-intelligence-big-data/learning-path-data-science-python/)

#### Automation 
* [Automate The Boring Stuff](https://automatetheboringstuff.com/)


#### Miscellaneous packages which could be useful 
* For creating GUI Applications 
    * Tkinter - The standard module for GUI's
    * PyQt - Python bindings to the popular Qt Framework 
    * Kivy  - A cross platform UI framework 
* For doing backend web development
    * flask
    * Django
    * CheeryPy
* For web scrapping 
    * Beautiful Soup
    * Scarpy
* [Testing frameworks](https://wiki.python.org/moin/PythonTestingToolsTaxonomy)
    * unittest 
    * doctest
    * nose
* For Machine Learning and Data Science
    * numpy, scipy
    * scikit-learn
    * pandas
* For visulization
    * matplotlib
    * bokeh
    * seaborn
* For text analysis and NLP
    * nltk
    * gensim
    * pyparsing

-----


--  Umesh N Rao 