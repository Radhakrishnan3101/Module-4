# Exp.No:17  
## EXCEPTION HANDLING

---

### AIM  
To create a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers.

---

### ALGORITHM

1. Begin the program.  
2. Read a string `input_str` from the user using `input()`.  
3. Split the input string using commas (`,`) to create a list of grades.  
4. Use a `try` block to attempt converting each item in the grades list to an integer and store the result in `l1`.  
5. If the conversion is successful, print the list `l1` containing the integer values.  
6. If an error occurs during conversion (for example, if the input is not a valid number), catch the exception and print an error message: `"The grades you entered were in an invalid format."` along with the original grades list.  
7. Terminate the program.

---

### PROGRAM


a=input()

b=[]

c=a.split(",")

try:

  for i in c:
  
  b.append(int(i))

  print(list(b))
  
except:

  print("The grades you entered were in an invalid format.")
  
  print(c)



### OUTPUT
![image](https://github.com/user-attachments/assets/b2d52acf-9084-4739-8956-4357c811a794)

### RESULT
Thus the python program was initiated and executed successfully
