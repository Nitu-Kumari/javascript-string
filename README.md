# STRING
~~~
JavaScript strings are used for storing and manipulating text.
~~~

# Example 
~~~
var x = "John Doe";
~~~

#
Strings have lots of operations
~~~
.replace 
.slice 
.indexOf 

replace method
The replace() method returns a new string with some or all matches of a pattern replaced by a replacement.
Syntax
str.replace(regexp|substr, newSubstr|function)

*  .slice 
The slice() method extracts a section of a string and returns it as a new string, without modifying the original string.
Syntax
str.slice(beginIndex[, endIndex])

.indexOf
The indexOf() method returns the position of the first occurrence of a specified value in a string. This method returns -1 if the value to search for never occurs.
 Note: The indexOf() method is case sensitive.
 Syntax
 str.indexOf(searchValue[, fromIndex])

 ~~~

 #
 UTF (Unicode Transformation Format)  is known as a Character Encoding.
# QUESTion
Given a string, write a function called simpleEncrypt that performs a complex, reversible operation on a string that isn't a single operation (not just + or - or * or / alone, use more than one step). Then write a function called simpleDecrypt that reverses it.
~~~
ANS
function simpleEncrypt(input){

}
function simpleDecrypt(input){

}

~~~


#Question
One of the most common things you'll have to write a quick function for is parsing a query string. Every web developer should know how to do this. Given a string that's formatted like so: ?first_name=Grace&last_name=Hopper Output an object formatted like so:

{
  "first_name" : "Grace",
  "last_name" : "Hopper"
}


~~~
ANS
function parsingQueryString(qs){
     "first_name" : "Grace",
  "last_name" : "Hopper"

}
parsingQueryString();

~~~~

# QUESTION
One of the final tasks a master string-parser can do is parse a common format called Comma Separated Values, or CSV files. Any spreadsheet can be exported to CSV, so it's a popular format for transferring data between people who use spreadsheets and people who use databases.

Given a (possibly very long) string formatted like the example below, return an object. The keys of the object should be the values from first line of the string. You'll find a line break character (/n) in between lines. The values should be all the data from the column the first row is aligned with.

id, Product, Price, Markup, Quantity
1, "Red T-Shirt", 10, 20, 5
2, "Blue T-Shirt", 10, 20, 8
3, "Green T-Shirt", 10, 15, 15
4, "Yellow T-Shirt", 10, 20, 3

ANS
~~~
function stringParse(){
    "id":[1,2,3,4,];
    "product":["ed T-Shirt","Blue T-Shirt","Green T-Shirt","Yellow T-Shirt"];
    
    "price"[20,20,15,20];
    "markup":[10,10,10,10];
    "Quantity":[5,8,15,3]
}

~~~
# QUESTION
Template Strings
Template Strings are a way we can write a string that has lots of variables, without lots of ugly string concatenation.

Syntax
`string text`
Template literals are enclosed by the back-tick (` `)  
