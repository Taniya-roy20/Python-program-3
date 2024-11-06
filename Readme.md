# Program 3: WAP to create a pyramid of the character '*' and a reverse pyramid.
code= n = int(input("enter the no of rows"))
<br>
for i in range(n):
<br>
    for j in range(n-i-1):
    <br>
        print(" ",end = " ")
        <br>
    for j in range(2*i+1):
    <br>
        print("*",end = " ")
        <br>
    print()
    <br>
for i in range (n):
<br>
    for j in range (i+1):
    <br>
        print(" ",end = " ")
        <br>
    for j in range(2*n-2*i-3):
    <br>
        print("*",end = " ")
        <br>
    print()
![program 3](https://github.com/user-attachments/assets/f0c537cd-5ccd-4de7-9a51-cc73c64a3678)
