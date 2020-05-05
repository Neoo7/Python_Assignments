# Python_Assignments
PythonRepo



Hi There,

Hope you doing well.

My name is kiran kumar mourya. I am a Java + Mulesoft developer.
Many Thanks to teach me python. Please find the completed assignment you given.

Wish you a grate day ahead.

Thanks 


2. Write a program which will find all such numbers which are divisible by 7 but are not a multiple
of 5, between 2000 and 3200 (both included). The numbers obtained should be printed in a
comma-separated sequence on a single line.
Sol-1

my_list = []
for i in list(range(2000, 3200)):
    if(i%7 == 0 and i%5 != 0):
        my_list += [i]
print(my_list)	

Sol-2

for i in list(range(2000, 3200)):
    if(i%7 == 0 and i%5 != 0):
        print(i, end=' ')	

3. Write a Python program to accept the user's first and last name and then getting them printed in
the the reverse order with a space between first name and last name.

str = input("Enter The String: ")
my_str = ""
splStr = str.split()
i = len(splStr)
while (i != 0):
    my_str += ' ' + splStr[i-1]
    i -= 1
print(my_str)

4. Write a Python program to find the volume of a sphere with diameter 12 cm.

pi = 3.1415926535897931
r = 12/2
V = 4/3*pi*r**3
print('The volume of sphere is: ',V)		

5. Create the below pattern using nested for loop in Python.

def inpt(n):
    for i in range(0, n):
        for j in range(0, i+1):
            print('* ', end='')
        print('\r')
    for k in range(n, 0, -1):
        for j in range(0, k-1):
            print('* ', end='')
        print('\r')
n = 5
inpt(n)		



6. Write a Python program to reverse a word after accepting the input from the user.

 str = input('Please Enter The String : ')
    print(str[::-1])

7. Write a Python Program to print the given string in the format specified in the below ​ sample output.

WE, THE PEOPLE OF INDIA, having solemnly resolved to constitute India into a
SOVEREIGN, SOCIALIST, SECULAR, DEMOCRATIC REPUBLIC and to secure to all
its citizens

str1 = 'WE, THE PEOPLE OF INDIA,'
str2 = ('having solemnly resolved to constitute India into a SOVEREIGN,{0}'.format('!')).center(75)
str3 = 'SOCIALIST, SECULAR, DEMOCRATIC REPUBLIC'.center(64)
str4 = 'and to secure to all its citizens'.center(59)

print('\n'.join([str1,str2,str3,str4]))			



 
