# VBA Homework: The VBA of Wall Street

## Scope of Project

Presented with a very large data file of daily stock fluctuation over the span of three years, the scope of work was defined as:

  * Examine the yearly change from opening price at the beginning of a given year to the closing price at the end of that year, determining if the stock had experienced either a positive or a negative change.

  * Calculate percent change from opening price at the beginning of a given year to the closing price at the end of that year.

  * Determine the total stock volume of the stock.


## At first glance

1. The file contained a consistent number of variables across each worksheet, with data stored in contiguous rows by a 3-digit stock ticker ID

2. A quick filtering of each sheet clarified that there were no "zero" values for any of the stocks.  When building code to calculate numerical functions (ie. division), this would need to be accounted for, so as not to generate errors in the outcome (would be an interesting challenge to go back to this project later and automate this process).

3. The initial filter also confirmed that there were no blank cells in the relevant columns.  This could have implications for writing the VBA code (would be an interesting challenge to go back to this project later and automate this process). 

4. When defining variables, it is important to take the size of the data (ie. number of rows of data) into account.  This may have implications for defining variables (ie. integer vs. long) 

## Observations during coding

  * Beyond having no prior experience, it was important to map out steps and using the data set, imagine how each step would play out in the data.  For example, to extract the opening stock value and closing stock value, it was important to consider how when designing an iterative "For Loop" I could write code that indicated where it could be found as it was running the loop (when the ticker in the row you are in is different to the ticker in the next row, grab the closing stock value from the row you are in).  Though the syntax and structure are not intuitive (and that took time) it helped to contextualize it in plain English.  I found that actually drawing a small schematic at times helped to resolve errors that were simply a result of putting things in the wrong order.

  * Though I spent a lot of time online looking for answers, I found the best resource was returning to the classes.  Starting out as a complete neophyte to analytics, I got bogged down in trying to overcomplicate things (with only limited time to learn something that most people spend weeks learning).  Keeping it simple and working from the basics not only made the task easier, but also helped me see how the knowledge from classes applied in this context. And it gave me a chance to understand what I was doing.  A valuable lesson moving forward.  
  
  * I found that adding a lot of notes into the code allowed me to document my understanding and progress.  It will provide a useful resource with further VBA self-study/practice.
  
  * Building and runnung code in sections allowed me to test different elements and work out the bugs (eg. building code to format cells as percentages to two decimal places to match the image on the assignment page).
  
  * Attention to detail is key...I spent a lot of time backtracking through errors that were simply a result of a missing character or closing of a statement.


## Other Considerations

In looking at further opportunities to expand the coding for this data set, I would like to apply other functionality to make it more informative.  This might include using standard deviation, graphs of the stock performance over time (by month, by quarter), perhaps looking at how the stock performs by month, maybe corelate it other financial data that might influence how the stocks perform over time (ie. a period of recession).


## Resources used
Textbook, Google, LinkedIn, SkillShare, YouTube.
