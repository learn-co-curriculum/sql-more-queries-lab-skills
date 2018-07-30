
# More SQL Queries

In this lab, we will write more `SELECT` statements to solidify our ability to query a SQL database.  We will also write more specific queries using the tools we learned in the previous lesson.

## Objectives

1. Solidify our ability to interact with SQL databases by writing more `SELECT` statements
2. Use `SELECT` with `ORDER BY` and `DESC`/`ASC` to order our results by the values of a specific column
3. Use `LIMIT` to select only a certain number of rows
4. Use `BETWEEN` to obtain results that fit between specified values

### Famous Dogs

We have a database full of famous dogs!  The `dogs` table is populated with the following data:

|name      |age    |gender |breed           |temperament|hungry |
|----------|-------|-------|----------------|-----------|-------|
|Snoopy    |3      |M      |beagle          |friendly   |1      |
|McGruff   |10     |M      |bloodhound      |aware      |0      |
|Scooby    |6      |M      |great dane      |hungry     |1      |
|Little Ann|5      |F      |coonhound       |loyal      |0      |
|Pickles   |13     |F      |black lab       |mischievous|1      |
|Clifford  |4      |M      |big red         |smiley     |1      |
|Lassie    |7      |F      |collie          |loving     |1      |
|Snowy     |8      |F      |fox terrier     |adventurous|0      |
|NULL      |4      |M      |golden retriever|playful    |1      |

## Queries

Write following SQL queries in the 'Execute SQL' tab in SQLite browser.  

* Return the name and breed for all female dogs

* Return the names of all dogs listed in alphabetical order.  Notice that SQL lists the nameless dog first.

* Return all information for any dog that doesn't have a name

* Return the name and breed of only the hungry dogs and lists them from youngest to oldest

* Return the oldest dog's name, age, and temperament

* Return the three youngest dogs

* Return the name and breed of only the dogs who are between five and ten years old

* Return the name, age, and hungry columns for hungry dogs between the ages of two and seven.  This query should also list these dogs in alphabetical order.

## Summary

Great work! In this lab we practiced writing more complex SQL statements to not only query specific information but also define the quantity of results and the order of our results. 
