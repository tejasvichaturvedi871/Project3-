# Program 3: WAP to create a pyramid of the character '*' and a reverse pyramid.
code= n = int(input("enter the no of rows"))
for i in range(n):
for j in range(n-i-1):
print(" ",end = " ")
for j in range(2i+1):
print("",end = " ")
print()
for i in range (n):
for j in range (i+1):
print(" ",end = " ")
for j in range(2n-2i-3):
print("*",end = " ")
print()
![Screenshot_20241227-003344_Chrome](https://github.com/user-attachments/assets/c8308575-4ec7-4484-a432-4c19e58df5e7)
