# Worksheet for Lab 10\!

### Question 1: What happens when you swap the delimiter from commas to tabs? How does the preview change?

(Make sure "disable live preview is not checked if you don't see a change)
###When I switch the delimiter from commas to tabs, the preview collapses into a single column. The file is like comma separated, so openrefine finds no tab characters to split on. The header becomes one long text string and every row is placed entirely in one cell, with the commas still included.
### Question 2: Try sorting the scientificName facet by name and by count. What problems are there with the data?

Sorting by name shows near duplicate values side by side. The data has misspellings, extra whitespace , and garbled characters. Sorting by count shows these variants occur only once or a few times. The same species is split across several values, so the counts are unreliable.

### Question 3: Use faceting to figure out the following:

#### How many different years are represented in this file?
There are 16 different years represented
#### What year occurs the most times?
1978
#### What year occurs the least number of times?
1993
# Questions for Post-Lab Assignment 10\!

### Question 4: What happens when you make a numerical facet of column note1, then convert the column to numbers? Is something different about the facet compared to yr?

### Question 5: Click and drag on the scatterplot facet you made to highlight a rectangle. What happens to the data points being displayed?

### Question 6: After the last step, some columns are empty. (You can check by text faceting a column) Why? What do you think we can do to fix it?