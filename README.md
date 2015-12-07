#Midway Practice Exercises
## Fork and Clone
Fork the repo then make a local clone!  Make sure to test all your code and commit your work as you go.

##Types
*Do these exercises in a file called `01-types.py` in this repository.  Use comments to record which question you are answering, and for text answers.*

1. Print a string.
- print "print a string" 
2. Print an integer.
- print 6 
	1. Convert this integer to a float.
	- print float(6)
	2. Convert this integer to a string.
	- print str(6) 
3. Print a float.
- print 8.5 
	1. Convert this float to an integer.
	- print int(8.5) 
	2. Convert this float to a string.
	print str(8.5) 
4. Print a boolean.
- print bool(6) --> True 
	1. Convert this boolean to an integer.
	- print bool(True) --> 1 
	2. Convert this boolean to a string.
	- print str(bool(6)) --> True 
5. Create a variable called `my_name` and assign it to your name. 
- my_name = "vicky" 
	1. Use the `type()` function to figure out the type of your name.
	- string 
6. Create a variable called `my_height` and assign it to your height in inches.
- my_height = "60" 
	1. Use the `type()` function to figure out what type your height is.
	- string 
7. Print out the string `"[name] is [height] inches tall."`
e.g. “Rachel is 61.5 inches tall.”
	1. Using string concatenation (the + operator).
	- print my_name + " is " + my_height + " inches tall." 
	2. Using multiple arguments to the print statement.
	- print my_name, "is", my_height, "inches tall" 
	3. Using string formatting. (the `%` thing)
	- print "%s is %s inches tall." % (my_name, my height)

##Conditionals
*Do these exercises in a file called `02-conditionals.py` in this repository.  Use comments to record which question you are answering, and for text answers.*

1. Create a conditional that checks if a variable is greater than 50. If it is, print `"too high!"` And if it's not print `"too low!"`
	1. Modify this conditional to print "just right!" If the number is equal to 50. 
	- guess = 50
	if guess > 50:
		print "too high!"
	elif guess < 50: 
    		print "too low!"
	else:
		 print "just right."
2. Create a conditional that checks if an object is not a string. If it's not, turn it into a string. Otherwise, don't do anything. 
	- if type(obj) == str:
		print "it's a string!"
	else: 
		print type(obj) == str

##Loops
*Do these exercises in a file called `03-loops.py` in this repository.  Use comments to record which question you are answering, and for text answers.*

1. Create a loop that counts up to 100 (non-inclusive) by ones.
- i = 0
- for i in range(0,101):
	print i 
2. Create a loop that counts up to and including 1000 by increments of 100.
- i = 0
- for i in range(0,1001,100)
	print i 
3. Create a loop that counts down from 1000 to 100 by increments of 100.
- i = 0
- for i in range(1000,-100,-100)
	print i 
##Lists & Tuples
*Do these exercises in a file called `04-lists-tuples.py` in this repository.  Use comments to record which question you are answering, and for text answers.*

1. Create a tuple of the primary colors red, yellow, and blue.
- primary_colors = ("red", "yellow", "blue") 
	1. Access the color blue using two different methods.
	- print primary_colors[-1], print primary_colors[2]
	2. Create a tuple called `secondary_colors` with orange, green, and purple
	- secondary_colors = ("orange", "green", "purple" 
	3. Create a new tuple called `all_colors` that contains all the colors. Create this tuple by concatenating the `primary_colors` and `secondary_colors` tuples
	- all_colors = primary_colors + secondary_colors
	- print all_colors 
2. Create a tuple called `full_name` that contains your first name and last name. 
	1. Convert the `full_name` tuple to a list.
	- print list(full_name)
	2. Reverse the `full_name` list so that it is last name, first name.
	- full_name = ("vicky", "ho")
	r = reversed(full_name)
	print list(r)

##Functions
*Do these exercises in a file called `05-functions.py` in this repository.  Use comments to record which question you are answering, and for text answers.*

1. Create a function called `convert_to_seconds` that has parameters `hours`, `minutes`, and `seconds`, and returns the value in seconds.
- def convert_to_seconds(hours, minutes, seconds)
	return seconds 
2. Create a function called `convert_to_hours` that takes in a value, in seconds, and returns a tuple in the form `(hours, minutes, seconds)`.
	1. Create a function called `print_time` that takes in a tuple from `convert_to_hours` and prints the string `"Hours: [hours], Minutes: [minutes], Seconds: [seconds]"`
	e.g. `print_time((4, 12, 58))	⇒	"Hours: 4, Minutes: 12, Seconds: 58"`
3. Create a function called `convert_to_inches` that has parameters `feet` and `inches`, and returns the value in inches.
- def convert_to_inches(feet, inches)
	return inches 
4. Create a function called `convert_to_feet` that takes a parameter in inches and returns a tuple in the form (feet, inches). 
	1. Create a function called `print_feet` that takes in a tuple from convert_to_feet and prints the string `"Feet: [feet], Inches: [inches]"`
	e.g. `print_feet((5,1))	⇒	"Feet: 5, Inches: 1"`	
5. Create a function called `crazy_count_for` that uses a for loop to count from 0 to 10 by increments of 1 and then up to and including 100 by increments of 10.
	e.g. `crazy_count_for()  
⇒	0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 20, 30, 40, 50, 60, 70, 80, 90, 100`
- def crazy_count_for(count):
    for i in range(0,11):
        print i
crazy_count_for(10)
- def crazy_count_for(count):
    for i in range(0,101,10):
        print i
crazy_count_for(100)

6. Create a function called `crazy_count_while` that uses a while loop to count from 0 to 10 by increments of 1 and then up to and including 100 by increments of 10.
- def crazy_count_while(count):
    index = 0
    while (index < 11):
        print index 
        index += 1
crazy_count_while(10)
- def crazy_count_while(count):
    index = 0
    while (index < 101):
        print index 
        index += 10
crazy_count_while(100)

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
