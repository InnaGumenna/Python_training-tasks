# Python_training-tasks_1
Several training exercises


# 1 Create a new string made of the first three characters of each input string
str_1 = 'python'
str_2 = 'libraries'

print(str_1[0:3]+str_2[0:3])
--> pytlib


# 2 Remove special symbols/punctuation from a string
s = "%welcome to @BE@projec<t!!"
mylist=['%','@','<','!']

for i in mylist:
    s=s.replace(i,"")   
print(s.lower())
--> welcome to beproject


# 3 Arrange string characters such that lowercase letters should come first
s = 'pRocESSinG'

str_lower=""
str_upper=""
for i in s:
    if i.islower():
        str_lower+=i
    else:
        str_upper+=i
y=str_lower+str_upper
print(y)
--> pocinRESSG

# 4 Removal all characters from a string except integers
s = '1 data55analysis 10'

for i in s:
    if not i.isdigit():
        s=s.replace(i,"")
print(s)
--> 15510

# 5 Remove empty strings from a list of strings:
lst = ['data', 'science', ' ', 'data', 'analysis']

lst =[x for x in lst if x.strip()]
print (lst)
--> ['data', 'science', 'data', 'analysis']

# 6 Convert 2 lists into one dictionary:
keys = ['New', 'Saint', 'San']
values = ['York', 'Petersburg', 'Francisco']

mydict= dict(zip(keys,values))
print(mydict)
--> {'New': 'York', 'Saint': 'Petersburg', 'San': 'Francisco'}

        
