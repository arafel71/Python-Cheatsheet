# Python-Cheatsheet


#Files
----------

Open - read mode :
-------------------
with open('D:\workspace\input.txt','r', encoding='utf-8') as f:
    myTextFile=f.read()


length of text file:
--------------------
len(myTextFile)

print('length of dataset in characters: ', len(myTextFile))

look at the first 1000 characters:
-----------------------------------
#look at the first 1000 characters
print(myTextFile[:1000])

Get file from Internet
-----------------------
!wget https://x.x/input.txt


#Data structure :
----------------

set
--------
set() method is used to convert any  iterable to a sequence of iterable elements with distinct elements , called Set
Examples :
list_numbers = [1, 2, 3, 4, 2, 5]
# create set from list
numbers_set = set(list_numbers)
print(numbers_set)
# Output: {1, 2, 3, 4, 5}
