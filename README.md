# pythontuesdayhw

## Exercise 1 <br>
# <p>Given a list as a parameter,write a function that returns a list of numbers that are less than ten</b></i></p><br>
# <p> For example: Say your input parameter to the function is [1,11,14,5,8,9]...Your output should [1,5,8,9]</p>

# Use the following list - [1,11,14,5,8,9]
integers_list = [1,11,14,5,8,9]

smallerThan = lambda x,y: [i for i in x if i<y]

print (smallerThan(integers_list, 10))

[1, 5, 8, 9]



## Exercise 2 <br>
# <p>Write a function that takes in two lists and returns the two lists merged together and sorted<br>
# <b><i>Hint: You can use the .sort() method</i></b></p>

list1 = ["hey", "their", "man"]
list2 = ["goodbye", "take", "care"]
print
