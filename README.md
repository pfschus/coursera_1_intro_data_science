# coursera_1_intro_data_science
My work from Coursera's Introduction to Data Science course, the first course in the data science specialization through UM. The course is hosted here: <https://www.coursera.org/specializations/data-science-python>

NOTE: I have included my uploaded assignments here. If you are enrolling in the course, you may not access the completed assignments. They are provided here for my personal reference and for teaching examples to my students. 

# Author info  
Patricia Schuster  
February 2017  
University of Michigan

# Week 1: [Python](https://www.python.org/) fundamentals

* [Basics of python variables and functions](week_1/basic_python_functions.ipynb)
  * Basics of how to structure a function
  * Required, optional, labeled input parameters
  * `help()` function
* [Types and sequences](week_1/types_and_sequences.ipynb)
  * `type()` function
  * Tuples, lists, strings, dictionaries, sequences
* [More on strings and formatting](week_1/more_on_strings_formatting.ipynb)
  * Using placeholders `{}` and formatting with `.format()`
  * Formatting number of digits or characters: integers, floats, strings
* [Dates and times](week_1/dates_and_times.ipynb)
  * Time since the epoch
  * Work in real time
* [Reading and writing `.csv` files](week_1/reading_writing_csv.ipynb)
  * Reading `.csv` files
  * Select by column or row
  * Sorting, grouping entries
* [Advanced python objects](week_1/advanced_python_objects_map_lambda.ipynb)
  * The `map()` function
  * `lambda` and list comprehensions
* [Numpy](week_1/numpy.ipynb)
  * Numpy arrays
  * Operations
  * Indexing / slicing
  * Iterating over arrays
  
# Week 2: Basic data processing with [pandas](http://pandas.pydata.org/)

* [The series data structure](week_2/series_data_structure.ipynb)
  * A pandas series is a cross between a list and a dictionary
  * Pass in anything array-like
  * Handling missing data, adding entries
  * Querying a series
  * Vectorizing, broadcasting data
* [The dataframe data structure](week_2/dataframe_data_structure.ipynb)
  * The heart of the pandas library, a 2-d series objects
  * Creating a dataframe
  * Indexing, slicing
  * Dropping, adding data
  * Modifying, copying data
* [DataFrame loading, querying, indexing](week_2/dataframe_loading_querying_indexing.ipynb)
  * Loading data from `.csv` files
  * Querying a DataFrame
  * Indexing and multi-indexing DataFrames
  * Handling missing values
* [Assignment 2- Pandas Introduction](week_2/Assignment_2.ipynb)
  * Work with data from Olympic medals and US census
  * Apply simple pandas methods including rename, slicing, return maximum, etc.
  
# Week 3: Advanced Python [pandas](http://pandas.pydata.org/)

* [Merging dataframes](week_3/merging_dataframes.ipynb)
  * Adding new columns
  * Merging two large dataframes
* [Pandas idioms](week_3/idiomatic_pandas.ipynb)
  * Method chaining
  * Map 
* [Group by](week_3/groupby.ipynb)
  * Provide a function to `groupby`
  * `groupby` objects
* [Scales](week_3/scales.ipynb)
  * Ratio, interval, ordinal, nominal scales
  * Collapsing ratio data into categorical data
* [Pivot tables](week_3/pivot_tables.ipynb)
* [Date functionality](week_3/date_functionality.ipynb)
  * Timestamp, period, datetimeindex, periodindex
  * Converting to datetime
  * Timedeltas
  * Working with dates in a DataFrame
* [Assignment 3- More Pandas](week_3/Assignment_3.ipynb)
  * Work with data on energy supply be country
  * Merge three dataframes and analyze resulting data

# Week 4: Statistical Analysis in Python and Project

* [Distributions](week_4/distributions.ipynb)
  * Binomial distribution
  * Continuous distribution
* [Hypothesis testing](week_4/hypothesis_testing.ipynb)
  * t-test
  * p-value
* [Assignment 4- Hypothesis Testing](week_4/Assignment_4.ipynb)
  * Work with data on US housing prices over time
  * Answer the research question: Are university towns more resistant to economic recessions?
  * Apply `ttest`
  
Course completed 1/2/2018