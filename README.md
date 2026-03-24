1. List Operations in Python: Sum of List Items
   
🎯 Aim:

To write a Python program that calculates the sum of all elements in a list.

🧠 Algorithm:

Define a list of numbers.
Use Python’s built-in sum() function to calculate the total.
Print the result.

🧾 Program:

items=[153,147,124,102]
print(sum(items))

Output:

<img width="585" height="196" alt="image" src="https://github.com/user-attachments/assets/a685de35-56fa-43f0-b514-b062eafa1249" />


Result:

Thus, the program was executed successfully.



2. Regex in Python: Filter Words Without the Letter 'e'

   
🎯 Aim:

To write a Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex).

🧠 Algorithm:

Import the re module.
Initialize an empty list l1 to store results.
Define a list of words:
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
Iterate through each word in the list:
Use re.search(r"e", i) to check if the word contains 'e'.
If not, append the word to l1.
Print the final filtered list.

🧾 Program:

import re
l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items:
    if not re.search(r"e", i):
        l1.append(i)
print("Words without 'e':", l1)

Output:

<img width="580" height="181" alt="image" src="https://github.com/user-attachments/assets/0c1af93c-54a2-4ca5-a429-63d52dd8b72f" />


Result:

Thus, the program was executed successfully.


3. Strings-Remove Nth Index Character from a String
   
🎯 Aim:

To write a Python program that accepts a string and removes the character at a specified index.

🧠 Algorithm:

Define a function named remove that takes the input string as an argument.
Read the index n from the user input.
Initialize an empty string a to store the new string.
Iterate over each index of the string using a for loop.
Check if the current index i is not equal to n.
If i != n, append the character at index i to string a.
After the loop, return the modified string a.
Print the final result.

💻 Program:

n=int(input())
def remove(a):
    for i in range(0,len(a)):
        if(i!=n):
            print(a[i],end='')
            
Output:

<img width="863" height="269" alt="image" src="https://github.com/user-attachments/assets/492e5a91-51a5-44e3-958c-385eb03070ad" />



Result:

Thus, the program was executed successfully.



4. Strings-Palindrome Check in Python (Without Built-in Functions)
   
🎯 Aim:

To write a Python program to check whether the string "google" is a palindrome or not, without using built-in palindrome checking functions.

🧠 Algorithm:

Assign the string "google" to a variable.
Reverse the string manually using slicing ([::-1]).
Compare the original string with the reversed string.
If they are equal, print that the string is a palindrome.
Otherwise, print that it is not a palindrome.
Execute the program.

🧾 Program:

a=input()
s=a[::-1]
if a==s:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
    
Output:

<img width="992" height="155" alt="image" src="https://github.com/user-attachments/assets/7f8c05d6-02d9-44e2-a9c8-e95f48e104f3" />


Result:

Thus, the program was executed successfully.



5. Tuple in Python: Check Element Existence
   
🎯 Aim: 

To write a Python program that checks if the element 'n' and the element 8 exist within a given tuple.

🧠 Algorithm:

Define a tuple x with some letters and numbers.
Use the in operator to check if the string 'n' exists within the tuple.
Use the in operator to check if the integer 8 exists within the tuple.
Print the results.


🧾 Program:

tuplex = input()
print("n" in tuplex)
print("8" in tuplex)

Output:

<img width="967" height="302" alt="image" src="https://github.com/user-attachments/assets/f34b0fa8-1299-47d9-9197-863607cd0599" />


Result

Thus, the program was executed successfully.
