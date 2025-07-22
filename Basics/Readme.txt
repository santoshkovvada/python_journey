variables in Python! 🙌
Data types: int, float, str, bool.
Arithmetic operators: +, -, *, /.
The % modulo finds the remainder.
The ** exponentiation finds the exponent.
The input() function is used to get user input.
The int() function converts a value into an integer number.


**********************************************************
Control flow is the order in which the program's code executes.
if statement tests a condition for truth and executes the code if it's True.
elif clause can be added between if and else.
else executes the code if none of the above is True.
Relational operators are used to compare two values: ==, !=, >, >=, <, <=.
Logical operators are used to combine two or more conditions: and, or, not.

if review >= 4.5:
  print('Extraordinary')
elif review >= 4:
  print('Excellent')
elif review >= 3:
  print('Good')
else:
  print('Eh')
*********************************************************************
Data that could be stored in a list:

Temperatures in the past week.
pH level of the office plant in the past hour.
"Now playing" in the movie theater nearby.
temp = [86, 80, 82, 87, 79, 80, 82]
ph = [7.2, 7.1, 7.0, 7.0, 7.2, 7.1]
now_playing = ['Barbie', 'Oppenheimer', 'Talk to Me', 'Blue Beetle']

More facts about lists:

List items allow duplicate values.
Lists can have values with different data types.
There's no limit to how much data a list can hold.

Slicing
Is there a way to get more than just one individual item? Yep! It's called slicing.

Slicing is where we can access certain parts of a sequence.

Instead of accessing an item using a single index like name[index], we can get multiple items by specifying where to start and where to end the range like name[start : end].

For example:

vowels = ['a', 'e', 'i', 'o', 'u']

print(vowels[0 : 3])
print(vowels[1 : 3])

# Output:
# ['a', 'e', 'i']
# ['e', 'i']

It starts from the start index (inclusive) and ends before the end index (non-inclusive). So in the above example, print(vowels[1 : 3]) only returned items at indices 1 and 2, and didn't include index 3.


List Methods
Besides built-in functions, Python has a bunch of built-in list methods that are very handy.

Here are some of them:

.append() method adds an item to the end of the list.
.insert() method adds an item to a specific index.
.remove() method removes an item from a list based on the value.
.pop() method removes the item at a particular index.
Let's use DNA sequences as an example for this! 🧬

dna = ['AUG', 'AUC', 'UCG']

dna.append('UAA')     # ['AUG', 'AUC', 'UCG', 'UAA']
dna.insert(2, 'GAU')  # ['AUG', 'AUC', 'GAU', 'UCG', 'UAA']
dna.remove('AUC')     # ['AUG', 'GAU', 'UCG', 'UAA']
dna.pop(0)            # ['GAU', 'UCG', 'UAA']

The difference between built-in functions and methods on a list is that methods use the dot notation syntax on the list variable we create. Built-in functions can be called by themselves, but methods are always attached to a list variable from which they are being called.

Another notable difference is that while not all the built-in functions are defined to work with lists, the list methods only work with lists.

Here are all 11 list methods to save in your notes:

List Method	Description
.append()	Add an item to the end of the list
.clear()	Remove all items from the list
.copy()	Return a shallow copy of the list
.count()	Return the number of times the value appears in the list
.extend()	Appends another list to the current list by extending it
.index()	Returns the index of a value inside the list
.insert()	Insert an item at a specified position in the list
.pop()	Remove an item from a specified position in the list
.remove()	Remove an item from the list based on the value of the item
.reverse()	Reverses the list in place
.sort()	Sorts the list in place


Lists are used to store different items in a single variable.
An index is an item's position in a list. Python lists are 0-indexed.
Slicing can access certain parts of a list with name[start:end].
Python has built-in functions like len(), max(), min().
Lists have built-in methods like .append(), .insert(), .remove(), .pop().
We can iterate over a list using for-in.