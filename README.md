
# CAB-21

# DATA SCIENCE course at Code Academy Berlin

## This folder will contain documentation

### Week-1 (CW 25)

1. Variable types
	1. Integer (x = 100)
	1. Float (x = 10.50)
	1. String (x = ‘Hello’ or “Hello”)

1. Single line comments in python starts with '#'

1. Document string comments ''' comment line 1, comment line 2 ....'''

1. type() command is used to see defined variable type e.g int or string or float

1. Numbers and arithmetic (PEMDAS Parentheses, Exponents, Multiplication/Division, Addition/Subtraction)

1. Built-in functions for numbers (min, max, abs ...)

1. Functions
	1. Build-in
	1. User defined
		1. def name(arguments):<br />
			statement 1<br />
			statement 2<br />
			print/return<br />

1. List 
	1. Mutable (element can be changed)
	1. Ordered (unique index value)
	1. Heterogeneous (can contain different kind of elements in one list like string, integer, Boolean ...)
	1. Duplicates (multiple items with same value can be defined)
	1. Application : value of the item changed frequently

	1. Syntax
		i. List constructor ( my_list = list((1, ‘Tim’, 2)) )
		ii. Square brackets [ ] ( my_list = [1, ‘Tim’, 2] )

1. List Functions
	1. Number of items in a list: Length of a list ‘len(list_name)’

	1. Indexing: Individual element can be access via index (my_list[0])
	1. Sorting: Alphabetic sorting sorted(list_name)
	1. sum( ), max( )
 
1. List Methods
	1. list.append() : add item at the end
	1. list.pop() : remove last element
	1. list.index() : search specific element
1. Tuples
	1. Immutable (element cannot be modified)
	1. Syntax: round brackets ( )
		1. E.g. T = (1, 2, 3)

<br />

### Week-2 (CW 26)
<br/>
What is Module <br/>
<br/>
A module allows you to logically organize your Python code. Grouping related code into a module makes the code easier to understand. Therefore, module is similar to function that allow you to perform many actions without writing your own code. <br/>
<br/>
Library is a collection of modules. You can think of packages as the directories on a file system and modules as files within directories. For example, if you are working with data, numpy, scipy, pandas, etc. are the libraries you must know. <br/>
<br/>
For Numpy basics see 

[Numpy github link!](https://github.com/Daredeveil/CAB-21/blob/main/numpy_ex.ipynb) <br/>
<br/>
For Pandas basics and example see 

[Pandas github link!](https://github.com/Daredeveil/CAB-21/blob/main/Pandas_basic.ipynb) <br/>
<br/>

#### Basic Statistics
<br/>
There are two major branches of statistics: <br/>
<br/>
1. Descriptive Statistics <br/>
Offers methods to summarise data by transforming raw observations into meaningful information that is easy to interpret and share. <br/>
<br/>

The parameters of descriptive statistics can be classifies into **4 categories** :
<br/>

a. Frequency: A **frequency** is the number of times a value of the data occurs <br/>
<br/>

b. Measures of Central Tendency (Mean, Median, Mode):
[Mean value!](https://i0.wp.com/dsft.code-data-ai.com/wp-content/uploads/2019/12/1-stat-4.jpg?w=600&ssl=1)
<br/>

References: 
* [Reference-1](https://www.calculators.org/math/mean-median-mode.php)
* [Reference-2](http://statisticshelper.com/mean-median-mode-calculator#answer)
* [Reference-3](https://www.youtube.com/watch?v=zjHfAhcU6kE&ab_channel=TheOrganicChemistryTutor)
* [Reference-4](https://www.youtube.com/watch?v=GaEvFaVa6OU&ab_channel=WendymathsIsacsson)
<br/>

i. **Mean 'μ':**
<br/>

The average of all the data in a set. You find the **mean** by taking the sum of all the data values and dividing that sum by the total number of data values.
<br/>

ii. **Median:**
The value in a set which is most close to the middle of a range. The **median** of a data set is found by putting the data set in **Ascending** numerical order and identifying the **middle number**. If there are an *odd number* of data values in the data set, the **median** is a *single number*. If there are an *even number* of data values in the data set, the **median** is the *average of the two middle numbers*.
<br/>

iii. **Mode:**
The value which occures most frequently in a data set. The **mode** is the *number that appears most frequently*. A data set may have *multiple modes*. If it has *two modes*, the data set is called *bimodal*. If all the data values have the same frequency, all the data values are modes.
<br/>

c. Measures of Variation (Range, Variance, Standard Deviation): [CAB Link!](https://dsft.code-data-ai.com/stats-1/#:~:text=The-,parameters,-Variance%20and%20Standard)<br/>
<br/>

References: 
* [Reference-1](https://statisticsbyjim.com/basics/variability-range-interquartile-variance-standard-deviation/)
* [Reference-2](https://online.stat.psu.edu/stat500/lesson/1/1.5/1.5.3)
* [Reference-3](https://stattrek.com/descriptive-statistics/variability.aspx)
<br/>

i. **Range:**
<br/>
The difference between highest and lowest values.
<br/>

ii. **Variance:**
**Variance** is the *average squared difference* of the values from the *mean*. The **variance** includes all values in the calculation by comparing each value to the mean.
<br/>

iii. **Standard Deviation:**
The **standard deviation** is the standard or typical difference between each data point and the mean. When the values in a dataset are grouped closer together, you have a smaller standard deviation. On the other hand, when the values are spread out more, the standard deviation is larger because the standard distance is greater.
The **standard deviation** is just the *square root* of the *variance*.
<br/>

d. Measures of Relative Position (Percentile, Quartile): It describes how data points fall in relation to one another.<br/>
[CAB Link!](https://dsft.code-data-ai.com/stats-1/#:~:text=points%20fall%C2%A0in-,relation,-to%C2%A0one%20another)
<br/>
<br/>
2. Inferencial Statistics <br/>
Offers methods to study experiments done on small samples of data and chalk out the inferences to the entire population (entire domain).<br/>

[CAB link!](https://dsft.code-data-ai.com/stats-1/#:~:text=in%20overall%20distribution%20%3F-,Inferential%20Statistics,-Inferential%20statistics%20use)
