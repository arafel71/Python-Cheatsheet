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



String
----------
Concaténation élément d'une liste / concat of list member to a string
-----------------------------------------------------------------------
''.join([itos[i] for i in l]
print(''.join(chars))

with lambda :
decode = lambda l: ''.join([itos[i] for i in l]) #decoder : take a list of integer, output a string


Numpy vstack
----------------
Stack arrays in sequence vertically (row wise).
This is equivalent to concatenation along the first axis after 1-D arrays of shape (N,) have been reshaped to (1,N). Rebuilds arrays divided by vsplit.

a = np.array([1, 2, 3])
b = np.array([4, 5, 6])
np.vstack((a,b))
array([[1, 2, 3],
       [4, 5, 6]])

a = np.array([[1], [2], [3]])
b = np.array([[4], [5], [6]])
np.vstack((a,b))
array([[1],
       [2],
       [3],
       [4],
       [5],
       [6]])

       


Enumération d'une liste de caractères avec index :
--------------------------------------------------
stoi = {ch:i for i,ch in enumerate(chars)}
itos = {i:ch for i,ch in enumerate(chars)}
