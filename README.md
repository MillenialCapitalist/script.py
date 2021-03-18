# script.py
My early python codes
print "Hello, world!"

print "What's up mudafurkah"

print "is there a way you can edit this code to bring out what I want, or you're just being stubburn?"

my_name = "Dayo"
print ("Hello and welcome " + my_name + "!")

print "This is a good string"

print 'You can use single quotes or double quotes for a string'

print "This is " + "a good string"
print "Hello " + "Dayo" + ", how are you doing?"

print ("How do you make a hot dog stand?")
print ("You take away its chair!")

greeting_message = "Welcome to Codecademy!"
current_exercise = 5

todays_date = "20 January 2021"

mirthful_addition = 12381 + 91817
amazing_subtraction = 981 - 312
trippy_multiplication = 38 * 902
happy_division = 540 / 45
sassy_combinations = 129 * 1345 + 120 / 6 - 12
is_this_number_odd = 15 % 2
is_this_number_divisible_by_seven = 133 % 7
product = 27 * 45
remainder = 1398 % 11

jfish_in_clarks_pond = 50

print "Catching fish"

number_of_fish_caught = 10
fish_in_clarks_pond = fish_in_clarks_pond - number_of_fish_caught

money_in_wallet = 40
sandwich_price = 7.50
sales_tax = .08 * sandwich_price
print sales_tax

sandwich_price += sales_tax
money_in_wallet -= sandwich_price
print sandwich_price
print money_in_wallet

january_to_june_rainfall = 1.93 + 0.71 + 3.53 + 3.41 + 3.69 + 4.50
annual_rainfall = january_to_june_rainfall

july_rainfall = 1.05
annual_rainfall += july_rainfall

august_rainfall = 4.91
annual_rainfall += august_rainfall

september_rainfall = 5.16
october_rainfall = 7.20
november_rainfall = 5.06
december_rainfall = 4.06
september_to_december_rainfall = 5.16 + 7.20 + 5.06 + 4.06

annual_rainfall += september_to_december_rainfall
print annual_rainfall

city_name = "St. Potatosburg"

#number of potatoes in Potatosburg:
city_pop = 340000

cucumbers = 12
price_per_cucumber = 3.25
total_cost = cucumbers * price_per_cucumber
print total_cost

quotient = 6/2
# the value of quotient is now 3, which makes sense

quotient = 7/2
# the value of quotient is 3, even though the result of the division here is 3.5

quotient1 = 7./2
# the value of quotient1 is 3.5
quotient2 = 7/2.
# the value of quotient2 is 3.5
quotient3 = 7./2.
# the value of quotient3 is 3.5

quotient1 = float(7)/2
# the value of quotient1 is 3.5

cucumbers = 100
num_people = 6

whole_cucumbers_per_person = cucumbers/num_people
print whole_cucumbers_per_person

float_cucumbers_per_person = float (cucumbers)/num_people
print float_cucumbers_per_person

haiku = """The old pond,
A frog jumps in:
Plop!"""

print haiku

age_is_12 = 0

name_is_maria = True

number1 = "100"
number2 = "10"

string_addition = number1 + number2
#string_addition now has a value of "10010"
print string_addition

int_addition = int(number1) + int(number2)
#int_addition has a value of 110
print int_addition

string_num = 7.5
print int(string_num)
print float(string_num)

float_1 = 0.25
float_2 = 40.0

product = float_1 * float_2
print float (product)

big_string = "The product was " + str(product)
print big_string

skill_completed = "Python Syntax"

exercises_completed = 13

#The amount of points for each exercise may change, because points don't exist yet
points_per_exercise = 5

point_total = 100

point_total += exercises_completed * points_per_exercise

print "I got "+ str(point_total) + " points!"

# Assign your variables below, each on its own line!
caesar = "Graham"
praline = "John"
viking = "Teresa"




# Put your variables above this line

print caesar
print praline
print viking

# Assign your variables below, each on its own line!
caesar = "Graham"
praline = "John"
viking = "Teresa"




# Put your variables above this line

print caesar
print praline
print viking

# The string below is broken. Fix it using the escape backslash!

'This isn\'t flying, this is falling with style!'

"""
The string "PYTHON" has six characters,
numbered 0 to 5, as shown below:

+---+---+---+---+---+---+
| P | Y | T | H | O | N |
+---+---+---+---+---+---+
  0   1   2   3   4   5

So if you wanted "Y", you could just type
"PYTHON"[1] (always start counting from 0!)
"""
fifth_letter = "MONTY"[4]

print fifth_letter

parrot = "Norwegian Blue"
print len(parrot)

parrot = "Norwegian Blue"

print parrot.lower()

parrot = "norwegian blue"

print parrot.upper()

"""Declare and assign your variable on line 4,
then call your method on line 5!"""

pi = 3.14
print str(pi)

ministry = "The Ministry of Silly Walks"

print len (ministry)
print ministry.upper()

"""Tell Python to print "Monty Python"
to the console on line 4!"""

print "Monty Python"

"""Assign the string "Ping!" to
the variable the_machine_goes on
line 5, then print it out on line 6!"""

the_machine_goes = "Ping!"
print the_machine_goes

# Turn 3.14 into a string on line 3!

print "The value of pi is around " + str(3.14)

# Turn 3.14 into a string on line 3!

print "The value of pi is around " + str(3.14)

day = 6
print "03 - %s - 2019" %  (day)
# 03 - 6 - 2019
print "03 - %02d - 2019" % (day)
# 03 - 06 - 2019

string_1 = "Camelot"
string_2 = "place"

print "Let's not go to %s. 'Tis a silly %s." % (string_1, string_2)

name = "Alex"
quest = "Teaching Python"
color = "Blue"

print "Ah, so your name is %s, your quest is %s, " \
"and your favorite color is %s." % (name, quest, color)

# Write your code below, starting on line 3!

my_string = "Dayo hates day-trading"
print len(my_string)
print my_string.upper()

'Alpha'
"Bravo"
str(3)
len("Charlie")
"Delta".upper()
"Echo".lower()
print "Foxtrot"
g = "Golf"
h = "Hotel"
print "%s, %s" % (g, h)

from datetime import datetime

now = datetime.now()
print now

from datetime import datetime

now = datetime.now()
print now

current_year = now.year
current_month = now.month
current_day = now.day

print now.year
print now.month
print now.day

from datetime import datetime
now = datetime.now()

print "%02d/%02d/%04d" % (now.month, now.day, now.year)

from datetime import datetime
now = datetime.now()

print '%s:%s:%s' % (now.hour, now.minute, now.second)

from datetime import datetime
now = datetime.now()

print "%02d/%02d/%02d %02d:%02d:%04d" % (now.month, now.day, now.year, now.hour, now.minute, now.second)

def clinic():
    print "You've just entered the clinic!"
    print "Do you take the door on the left or the right?"
    answer = raw_input("Type left or right and hit 'Enter'.").lower()
    if answer == "left" or answer == "l":
        print "This is the Verbal Abuse Room, you heap of parrot droppings!"
    elif answer == "right" or answer == "r":
        print "Of course this is the Argument Room, I've told you that already!"
    else:
        print "You didn't pick left or right! Try again."
        clinic()

clinic()

# Assign True or False as appropriate on the lines below!

# Set this to True if 17 < 328 or to False if it is not.
bool_one = True   # We did this one for you!

# Set this to True if 100 == (2 * 50) or to False otherwise.
bool_two = True

# Set this to True if 19 <= 19 or to False if it is not.
bool_three = True

# Set this to True if -22 >= -18 or to False if it is not.
bool_four = False

# Set this to True if 99 != (98 + 1) or to False otherwise.
bool_five = False

# Assign True or False as appropriate on the lines below!

# (20 - 10) > 15
bool_one = False    # We did this one for you!

# (10 + 17) == 3**16
# Remember that ** can be read as 'to the power of'. 3**16 is about 43 million.
bool_two = False

# 1**2 <= -1
bool_three = False

# 40 * 4 >= -4
bool_four = True

# 100 != 10**2
bool_five = False

# Create comparative statements as appropriate on the lines below!

# Make me true!
bool_one = 3 < 5  # We already did this one for you!

# Make me false!
bool_two = 4 <3

# Make me true!
bool_three = 3==3

# Make me false!
bool_four = 18 > 19

# Make me true!
bool_five = 3==3

# Use boolean expressions as appropriate on the lines below!

# Make me false!
bool_one = (2 <= 2) and "Alpha" == "Bravo"  # We did this one for you!

# Make me true!
bool_two =

# Make me false!
bool_three =

# Make me true!
bool_four =

# Make me true!
bool_five =

# Use boolean expressions as appropriate on the lines below!

# Make me false!
bool_one = (2 <= 2) and "Alpha" == "Bravo"  # We did this one for you!

# Make me true!
bool_two = 23 % 10 == 6 / 2 and not False

# Make me false!
bool_three = 15 ** 2 + 30 <= 16 ** 2 and False or not True

# Make me true!
bool_four = True or False or 45 / 9 == 25 ** 0.5

# Make me true!
bool_five = (False or True) and not False or 2 / 2 >= 100 ** 0

response = 'Y'

answer = "Left"
if answer == "Left":
    print "This is the Verbal Abuse Room, you heap of parrot droppings!"

# Will the above print statement print to the console?
# Set response to 'Y' if you think so, and 'N' if you think not.

def using_control_once():
    if 16 == 4 ** 2:
        return "Success #1"

def using_control_again():
    if 16 ** 0.5 == 2.5 + 1.5:
        return "Success #2"

print using_control_once()
print using_control_again()

answer = "'Tis but a scratch!"

def black_knight():
    if answer == "'Tis but a scratch!":
        return True
    else:
        return False   # Make sure this returns False

def french_soldier():
    if answer == "Go away, or I shall taunt you a second time!":
        return True
    else:
        return False   # Make sure this returns False

def greater_less_equal_5(answer):
    if answer > 5 :
        return 1
    elif answer < 5 :
        return -1
    else:
        return 0

print greater_less_equal_5(4)
print greater_less_equal_5(5)
print greater_less_equal_5(6)

# Complete the if and elif statements!
def grade_converter(grade):
    if grade >= 90:
        return "A"
    elif grade >= 80:
        return "B"
    elif grade >= 70:
        return "C"
    elif grade >= 65:
        return "D"
    else:
        return "F"

# This should print an "A"
print grade_converter(92)

# This should print a "C"
print grade_converter(70)

# This should print an "F"
print grade_converter(61)

print 'Welcome to the Pig Latin Translator!'

# Start coding here!
original = raw_input("Enter a word:")
if len(original) > 0 and original.isalpha():
  #statement checks if statement is greater than zero and in lowercase
  print original
  #confirms if statement is True
else:
  print "empty"
  #confirms if statement is False

pyg = 'ay'

original = raw_input('Enter a word:')

if len(original) > 0 and original.isalpha():
  #returns Boolean True if written word satisfies both conditions
  word = original.lower()
  #sets the lowercase version of "original" to a new variable "word"
  first = word[0]
  #returns the first letter (0th character) in first
  new_word = word + first + pyg
  #concatenates variables word, first and pyg into new variable "new_word"
  new_word = new_word[1:len(new_word)]
  #returns all letters in new_word from the 1st character.
  print new_word
else:
    print 'empty'

def tax(bill):
  """Adds 8% tax to a restaurant bill."""
  bill *= 1.08
  print "With tax: %f" % bill
  return bill

def tip(bill):
  """Adds 15% tip to a restaurant bill."""
  bill *= 1.15
  print "With tip: %f" % bill
  return bill
  
meal_cost = 100
meal_with_tax = tax(meal_cost)
meal_with_tip = tip(meal_with_tax)

# Define your spam function starting on line 5. You
# can leave the code on line 10 alone for now--we'll
# explain it soon!

def spam():
  """Prints the string 'Eggs!' to the console"""
  print "Eggs!"
  return spam()


# Define the spam function above this line.

def square(n):
  """Returns the square of a number."""
  squared = n ** 2
  print "%d squared is %d." % (n, squared)
  return squared
  
# Call the square function on line 10! Make sure to
# include the number 10 between the parentheses.

square(10)

def triple(n):
  """triples the value of a number."""
  triple = n * 3
  print triple(13)
  
def power(base, exponent):  # Add your parameters here!
  result = base ** exponent
  print "%d to the power of %d is %d." % (base, exponent, result)

power(37, 4)  # Add your arguments here!

def one_good_turn(n):
  return n + 1
    
def deserves_another(n):
  return one_good_turn(n) + 2
  
def cube(number):
  return number ** 3

def by_three(number):
  if number % 3 == 0:
    return cube(number)
  else:
    return False

#Loops and iterations
n = 5
while n > 0:
  print(n)
  n = n - 1
print("Blastoff!")
print(n)

n = 0
while n > 0:
  print("Lather")
  print("Rinse")
print("Dry off!!")

# Definite loops
numbers = [0, 254, 2, -1, 3]

for num in numbers:
  if (num < 0):
    print("Negative number detected")
    break
  print(num)


for i in [5, 4, 3, 2, 1]:
  print(i)
print("Blastoff")

#A Definite Loop with Strings
friends = ["Joseph", "Glenn", "Sally"]
for friend in friends:
  print("Happy New Year:", friend)
print("Done!")

#The "is" and "is not" Operators
#Python has an "is" operator 
#that can be used in logical experessions
#Implies "is the same as"
#Similar to, but stronger than ==
#"is not also" is a logical operator
smallest = None
print("Before")
for value in [3, 41, 12, 9, 74, 15]:

#Finding the smallest value
#We still have a variable that is the smallest so far.
#The first time through the loop smallest is None, so
#we take the first value to be the smallest

smallest = None
print("Before")
for value in (9, 41, 12, 3, 74, 15):
    if smallest is None:
        smallest = value
    elif value < smallest:
        smallest = value
    print(smallest, value)
print("After", smallest)

#The "is" and "is not" Operators
#Python has an "is" operator
#that can be used in logical experessions
#Implies "is the same as" or equal values and types
#Similar to, but stronger than ==
#"is not also" is a logical operator


#use "is" on Booleans only, advisably.

#String Data Type 
#A string is  a sequence of characters
#A string literal uses quotes "Hello" or 'Hello'
#For strings, + means concatenate
#When a string contains numbers, it is still a big_string
#We can convert numbers in a string into a number using int()

string_1 = "Hello"
string_2 = "there"
bob = string_1 + string_2 
print(bob)

 
string_3 = "123"
x = int(string_3) + 1
print(x)

apple = input("Enter:")
x = int(apple) - 10

#Looking Inside Strings 

#We can get at any single character in a string
#using an index specified in square brackets

#The index value must be an integer and starts at zero

#The index value can be an expression that is computed

b a n a n a 
0 1 2 3 4 5

fruit = "banana"
letter = fruit(1)
print(letter)

x = 3
w = fruit[x - 1]
print(w)

#A Character Too far

#You will get a python error if you attempt to index 
#beyond the end of a string

#So be careful when constructing index values and slices

zot = "abc"
print(zot[5])

#A Character Too far

#You will get a python error if you attempt to index 
#beyond the end of a string

#So be careful when constructing index values and slices



#Looping Through Strings
#Using a while statement and an iteration 
#variable, and the "len" function, we can
#construct a loop to look at each of the
#letters in a string individually

fruit = "banana"
index = 0
while index < len(fruit):
  letter = fruit[index]
  print(index, letter)
  index = index + 1

#A definite loop using a for statement is much more elegant
#The iteration variable is completely taken care of 
#by the for loop 

fruit = "banana"
for letter in fruit:
    print(letter)

index = 0
while index < len(fruit):
    letter = fruit[index]
    print(letter)
    index = index + 1

#Looping and Counting 
#This is a simple loop that loops through each letter
#in a string and counts the number of times the loop 
#encounters the "a" character 

word = "banana"
count = 0
for letter in word:
    if letter == "a":
        count = count + 1
    print(count) 

#Looking deeper into in 

#The iteration variable "iterates" through the sequence (ordered set)
#The block(body) of code is executed once for each value in the sequence
#The iteration variable moves through all of the values in the sequence

for letter in "banana":
    print(letter)

#Slicing Strings 

#We can also look at any continuous section of a string
#using a colon operator

#The second number is one beyong the end of the slice -
#"up to but not including"

#if the second number is beyond the end of the string,
#it stops at the end.

# M  O  N  T  Y     P  Y  T  H  O  N 
# 0  1  2  3  4  5  6  7  8  9  10 11

s = "Monty Python"
print(s[0:4])
print(s[6:7])
print(s[6:20])

#if we leave off the first number or the last number of
#the slice, it is assumed to be the beginning or end of 
#the string respectively
s = "Monty Python"
print(s[:2])
print(s[8:])
print(s[:])

#When the + operator is applied to strings,
#it means "concatenation"

a = "Hello"
b= a + "There"
print(b)
c = a + " " + "There"
print(c)

#Using in as a Logical Operator

#The in keyword can also be used to check to see if one 
#string is "in" another string

#The in expression is a logical expression that returns
#True or False and can be used in an if statement

fruit = "banana"
"n" in fruit
"m" in fruit
"nan" in fruit
if "a" in fruit:
  print("Found it!")

# M  O  N  T  Y     P  Y  T  H  O  N
# 0  1  2  3  4  5  6  7  8  9  10 11

s = "Monty Python"
print(s[0:4])
print(s[6:7])
print(s[6:20])

#if we leave off the first number or the last number of
#the slice, it is assumed to be the beginning or end of
#the string respectively
s = "Monty Python"
print(s[:2])
print(s[8:])
print(s[:])

#When the + operator is applied to strings,
#it means "concatenation"

a = "Hello"
b= a + "There"
print(b)
c = a + " " + "There"
print(c)

#Using in as a Logical Operator

#The in keyword can also be used to check to see if one
#string is "in" another string

#The in expression is a logical expression that returns
#True or False and can be used in an if statement

fruit = "banana"
"n" in fruit
"m" in fruit
"nan" in fruit
if "a" in fruit:
  print("Found it!")


#String Comparison

if word == "banana":
  print("All right, bananas.")

if word < "banana":
  print("Your word," + word + ", comes before banana.")
elif word > "banana":
  print("Your word," + word + ", comes after banana.")
else:
  print("All right, bananas.")

#Using in as a Logical Operator

#The in keyword can also be used to check to see if one
#string is "in" another string

#The in expression is a logical expression that returns
#True or False and can be used in an if statement

fruit = "banana"
"n" in fruit
"m" in fruit
"nan" in fruit
if "a" in fruit:
  print("Found it!")


# String Library

#Python has a number of string functions which are in
#the string library

#These functions are already built into every string -
#we invoke them by appending the function to the string
#variable

#These functions do not modify the original string,
#instead they return a new string that has been altered

stuff = "Hello world"
type(stuff)
dir(stuff)

#Search and Replace

#The replace() function is like a "search and replace"
#operation in a word processor

#It replaces all occurrences of the search string with
#the replacement string

greet = "Hello Bob"
nstr = greet.replace("Bob", "Jane")
print(nstr)
nstr = greet.replace("o", "x")
print(nstr)
