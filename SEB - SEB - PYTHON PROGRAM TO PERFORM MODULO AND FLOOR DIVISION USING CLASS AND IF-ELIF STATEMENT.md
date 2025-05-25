# Exp.No:20  
## SEB - PYTHON PROGRAM TO PERFORM MODULO AND FLOOR DIVISION USING CLASS AND IF-ELIF STATEMENT

---

### AIM  
To write a Python program using a class to perform modulo and floor division operations based on user choice using if-elif conditional statements.
---

### ALGORITHM

Start the program.

Define a class named SEC.

Inside the class:

Define a method setvalues() to take two integer inputs a and b.

Define a method rem() to perform modulo operation.

Define a method div() to perform floor division.

Create an object of the class.

Call setvalues() method using the object to set the values.

Use a loop to:

Ask for the user's choice.

If choice is 1, call the rem() method.

If choice is 2, call the div() method.

If choice is 0, print “Exiting!” and break the loop.

For any other choice, print “Invalid choice”.

End the program.

---

### PROGRAM

class sec:
    def __init__(self):
    
   self.a=int(input())
   
   self.b=int(input())
      
   def show(self):
    
   c=int(input())
   
   if c==1:
        
 print("Result:  {}".format(self.a%self.b))
 
   elif c==2:
   
   print("Result:  {}".format(self.a//self.b))
   
 print("Exiting!")
                
x=sec()

x.show()



### OUTPUT
![image](https://github.com/user-attachments/assets/eb5899d0-304d-457f-b90a-286941537c48)

### RESULT
Thus the pyhton program was implemented and executed successfully
