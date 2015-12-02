#Midway Practice Exercises
## Fork and Clone
Fork the repo then make a local clone!  Make sure to test all your code and commit your work as you go.

##Types
*Do these exercises in a file called `01-types.py` in this repository.  Use comments to record which question you are answering, and for text answers.*

1. Print a string.
2. Print an integer.
	1. Convert this integer to a float.
	2. Convert this integer to a string.
3. Print a float.
	1. Convert this float to an integer.
	2. Convert this float to a string.
4. Print a boolean.
	1. Convert this boolean to an integer.
	2. Convert this boolean to a string.
5. Create a variable called `my_name` and assign it to your name. 
	1. Use the `type()` function to figure out the type of your name.
6. Create a variable called `my_height` and assign it to your height in inches.
	1. Use the `type()` function to figure out what type your height is.
7. Print out the string `"[name] is [height] inches tall."`
e.g. “Rachel is 61.5 inches tall.”
	1. Using string concatenation (the + operator).
	2. Using multiple arguments to the print statement.
	3. Using string formatting. (the `%` thing)


##Conditionals
*Do these exercises in a file called `02-conditionals.py` in this repository.  Use comments to record which question you are answering, and for text answers.*

1. Create a conditional that checks if a variable is greater than 50. If it is, print `"too high!"` And if it's not print `"too low!"`
	1. Modify this conditional to print "just right!" If the number is equal to 50. 
2. Create a conditional that checks if an object is not a string. If it's not, turn it into a string. Otherwise, don't do anything. 

##Loops
*Do these exercises in a file called `03-loops.py` in this repository.  Use comments to record which question you are answering, and for text answers.*

1. Create a loop that counts up to 100 (non-inclusive) by ones.
2. Create a loop that counts up to and including 1000 by increments of 100.
3. Create a loop that counts down from 1000 to 100 by increments of 100.

##Lists & Tuples
*Do these exercises in a file called `04-lists-tuples.py` in this repository.  Use comments to record which question you are answering, and for text answers.*

1. Create a tuple of the primary colors red, yellow, and blue.
	1. Access the color blue using two different methods.
	2. Create a tuple called `secondary_colors` with orange, green, and purple
	3. Create a new tuple called `all_colors` that contains all the colors. Create this tuple by concatenating the `primary_colors` and `secondary_colors` tuples
2. Create a tuple called `full_name` that contains your first name and last name. 
	1. Convert the `full_name` tuple to a list.
	2. Reverse the `full_name` list so that it is last name, first name.

##Functions
*Do these exercises in a file called `05-functions.py` in this repository.  Use comments to record which question you are answering, and for text answers.*

1. Create a function called `convert_to_seconds` that has parameters `hours`, `minutes`, and `seconds`, and returns the value in seconds.
2. Create a function called `convert_to_hours` that takes in a value, in seconds, and returns a tuple in the form `(hours, minutes, seconds)`.
	1. Create a function called `print_time` that takes in a tuple from `convert_to_hours` and prints the string `"Hours: [hours], Minutes: [minutes], Seconds: [seconds]"`
	e.g. `print_time((4, 12, 58))	⇒	"Hours: 4, Minutes: 12, Seconds: 58"`
3. Create a function called `convert_to_inches` that has parameters `feet` and `inches`, and returns the value in inches.
4. Create a function called `convert_to_feet` that takes a parameter in inches and returns a tuple in the form (feet, inches). 
	1. Create a function called `print_feet` that takes in a tuple from convert_to_feet and prints the string `"Feet: [feet], Inches: [inches]"`
	e.g. `print_feet((5,1))	⇒	"Feet: 5, Inches: 1"`	
5. Create a function called `crazy_count_for` that uses a for loop to count from 0 to 10 by increments of 1 and then up to and including 100 by increments of 10.
	e.g. `crazy_count_for()  
⇒	0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 20, 30, 40, 50, 60, 70, 80, 90, 100`
6. Create a function called `crazy_count_while` that uses a while loop to count from 0 to 10 by increments of 1 and then up to and including 100 by increments of 10.
7. Create a function that counts and returns the number of unique letters in your full name. It should take in your first and last name as arguments and return an integer.

##Dictionaries
*Do these exercises in a file called `06-dictionaries.py` in this repository.  Use comments to record which question you are answering, and for text answers.*

1. Write a function called `parse_groceries` that takes in a string of the form `"item:apples,quantity:4,price:1.50"` and returns a dictionary of the form `{ 'item':'apples', 'quantity':4, 'price':1.50 }`.
2. Write another function called `calculate_itemized` that takes in a list of dictionary of the form above and prints out the total for each item, and then the total of all the items at the end.

e.g.

```
grocery_bill = [
	{ 'item':'apples', 'quantity':4, 'price':1.50 }, 
	{ 'item':'bananas', 'quantity':3, 'price':4 }
]
calculate_itemized(grocery_bill)
```

should print

```
apples: $6
bananas: $12
total: $18
```

## Push your work
Push everything back up to the fork (make sure you've committed everything!).  If you'd like feedback on your work, send Sarah an email with the link to your fork.
