# Python

### Basic Concepts
- Exponentiations
```
>>> 2**5
32
>>> 9 ** (1/2)
3.0
```
- Quotient & Remainder
```
>>> 20 // 6   (floor division)
3
>>> 1.25 % 0.5
0.25
```
- Input
```
input("Enter something please: ")

float(input("Enter a number: ")) + float(input("Enter another number: "))
Enter a number: 40
Enter another number: 2
42.0

>>> foo = input("Enter a number: ")
Enter a number: 7
>>> print(foo)
7
```
- Strings
```
>>> print("spam" * 3)
spamspamspam

>>> 4 * '2'
'2222'
```
- If, Else
```
num = 7
if num == 5:
   print("Number is 5")
elif num == 11:
   print("Number is 11")
elif num == 7:
   print("Number is 7")
else:
   print("Number isn't 5, 11 or 7")
```
- logic
```
>>> 1 == 1 and 2 == 2
True
>>> 2 < 1 or 3 >  6
False
>>> not 1 == 1
False
```
- Loops
```
#while

i = 1
while i <=5:
   print(i)
   i = i + 1

print("Finished!")
```
### Structures
- Lists
```
#Lists are another type of object in Python. They are used to store an indexed list of items. 
#A list is created using square brackets with commas separating items.
#The certain item in the list can be accessed by using its index in square brackets.

words = ["Hello", "world", "!"]
print(words[0])
print(words[1])
print(words[2])

number = 3
things = ["string", 0, [1, 2, number], 4.56]
print(things[1])
print(things[2])
print(things[2][2])
>>>
0
[1, 2, 3]
3
>>>

#Lists can be added and multiplied in the same way as strings.

nums = [1, 2, 3]
print(nums + [4, 5, 6])
print(nums * 3)
>>>
[1, 2, 3, 4, 5, 6]
[1, 2, 3, 1, 2, 3, 1, 2, 3]
>>>

#To check if an item is in a list, the in operator can be used. It returns True if the item occurs one or more times in the #list, and False if it doesn't.

words = ["spam", "egg", "spam", "sausage"]
print("spam" in words)
print("egg" in words)
print("tomato" in words)
>>>
True
True
False
>>>

#To check if an item is not in a list, you can use the not operator in one of the following ways:

nums = [1, 2, 3]
print(not 4 in nums)
print(4 not in nums)
print(not 3 in nums)
print(3 not in nums)
>>>
True
True
False
False
>>>
```
