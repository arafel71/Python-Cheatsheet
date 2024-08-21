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

