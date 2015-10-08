# week-3
ISD lab sheet week 3 
For the practical part of this lab please save the Python programs that you create and take screenshots of the execution (evaluation) of your programs. Commit (upload) all source code you create to your code repository. 
1.	Which of the following conditions are true, if a is 13 and b is 14?
a)	a + 1 <= b    True
b)	a + 1 >= b    True
c)	a + 1 != b     False

2.	What is the error in this statement?
if scoreA = scoreB :   It must be two ==
        print("Tie")

3.	Supply a condition in this if statement to test whether the user entered a Y:
userInput = input("Enter Y to quit.")
if userInput == ‘Y’:
print("Goodbye")

4.	Find the errors in the following if statements.  Make corrections.
a)if x > 0 then : without then
       print(x)
b)if (1 + x) >( x ** sqrt(2) ):
         y = y + x
c)if x = 1 :  it must be two ==
      y += 1
d)	letterGrade = "F"  it need space
if grade >= 90 :
 letterGrade = "A"
  if grade >= 80 :
   letterGrade = "B"
    if grade >= 70 :
     letterGrade = "C"
      if grade >= 60 :
       letterGrade = "D"

5.	Write a program that sets a password as ‘changeme’ and asks the user to enter the password and keeps asking until the correct password is entered and then says ‘Accepted’. 
The program should count how many attempts the user has taken and tell them after they have been accepted. 
Extra Challenge: 
If the user takes more than 5 attempts the program should say, ‘Access denied, please press enter to exit and contact security to reset your password’

y = 'changeme'
i = 0
while i <= 5:
    x = input("Enter the password")
    if x == y:
        print("Accepted")
        break
    else:
        print("Try again")
        i += 1
    if i == 5:
        print("Access denied")
        break`


6. Using the flow chart below, construct the if..elif..else control structure.
Complete your program to describe the earthquake by asking the user to enter a magnitude on the Richter scale.
 


r=float(input("enter a magnitude"))
if r >= 8:
    print("Most structures fall")
elif r >= 7 and r < 8:
    print("Many buildings destroyed")
elif r >= 6 and r < 7:
    print("Many buildings considerably damaged,some colapse")
elif r >= 4.5 and r < 6:
    print("Damage to poorly constructed buildings")
elif r < 4.5:
    print("No destruction of buildings")



7. What do the following nested loops display?  Hand trace. 

for i in range(3) :
      for j in range(1, 4) :
           print(i + j, end="")
print()
It will show 1 2 3 4 2 3 4 3 4 5 	

8. Write a program that will generate a table to print powers of the first 5 numbers.  Your output should be similar to the sample given below. 
  
print("              x**1  x**2  x**3")
for num in range(1,6):
    print("The number",num,"  ",num**1,"  ",num**2,"  ",num**3)
