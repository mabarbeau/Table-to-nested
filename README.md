# Sample PHP problem

## Please provide your own custom working solution to the following problem:

We want to be able to output a multi-level nested list of items in HTML. A simple SQL table would have the following data elements: itemID – int, item – varchar, subItemOfID – int, where subItemOfID contains the itemID of the parent item. A sample of the data would look something like this:


| itemID  |     item    | subItemOfID  |
|:-------:|:-----------:|:------------:|
|    1    |   'Item1'   |       0      |  
|    2    |  'Item2'    |       0      |  
|    3    |   'Item3'   |       0      |  
|    4    |   'Item10'  |       1      |  
|    5    |   'Item11'  |       1      |  
|    6    |   'Item12'  |       1      |  
|    7    |  'Item100'  |       4      |  
|    8    |  'Item101'  |       4      |  
|    9    |  'Item102'  |       4      |  
|    10   |   'Item30'  |       3      |  
|    11   |   'Item31'  |       3      |  
|    12   |   'Item32'  |       3      |


The HTML output would need to look something like this (nested lists sorted by item):
* Item1
  * Item10
    * Item100
    * Item101
    * Item102
  * Item11
  * Item12
* Item2
* Item3
  * Item30
  * Item31
  * Item32

