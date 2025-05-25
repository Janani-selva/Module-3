## List Operations in Python: Sum of List Items
## AIM
 To write a Python program that calculates the sum of all elements in a list.
## ALGORITHM
 1. Define a list of numbers.
 2. Use Python’s built-in sum() function to calculate the total.
 3. Print the result.
## PROGRAM
```
 items=[1,2,-8]
 s=0
 for i in items:
    s+=i
 print(s)
```
## OUTPUT
![Screenshot 2025-05-25 114418](https://github.com/user-attachments/assets/f0137f27-bfda-44b6-9665-8316a801e4b0)

## RESULT
 Thus the program that calculates the sum of all elements in a list has been executed successfully.
 
## Regex in Python: Filter Words Without the Letter 'e'
## AIM
 To write a Python program that filters out and returns all elements from a list that do not contain the letter
 'e', using regular expressions (regex).
## ALGORITHM
 1. Import the re module.
 2. Initialize an empty list l1 to store results.
 3. Define a list of words:
 items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
 4. Iterate through each word in the list:
 Use re.search(r"e", i) to check if the word contains 'e' .
 If not, append the word to l1 .
 5. Print the final filtered list.
## PROGRAM
```
 items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
 l1,l2=[],[]
 for i in items:
    for x in i:
        if x=="e":
            l1.append(i)
            break
 for a in items:
    if a not in l1:
        l2.append(a)
 print(l2)
```
## OUTPUT
![Screenshot 2025-05-25 114427](https://github.com/user-attachments/assets/4f87fef1-ef86-4348-ad06-42e5f842ab1c)

## RESULT
 Thus the program that filters out and returns all elements from a list that do not contain the letter 'e' , using
 regular expressions (regex) has been executed successfully.

## Strings-Remove Nth Index Character from a String
## AIM
To write a Python program that accepts a string and removes the character at a specified index.
## Algorithm
 1. Define a function named remove that takes a string s as an input argument.
 2. Initialize an empty string a to build the modified version of the input string.
 3. Use a for loop to iterate over each index i of the input string.
 4. In each iteration, check if the current index i is not equal to 3.
 5. If i != 3, append the character at index i to the string a.
 6. If i == 3, skip appending (effectively removing the 3rd index character).
 7. After the loop ends, return the new string a.
 8. Call the function and print the result.
 ## Program
 ```
 def remove(s):
 new_string = s[:3] +s[4:]
 print(new_string)
```
## OUTPUT
![Screenshot 2025-05-25 114438](https://github.com/user-attachments/assets/9187bf04-fd1b-47db-84b1-0c69f6d03d4d)

## RESULT
 Thus the program that accepts a string and removes the character at a specified index has been executed
 successfully.
 
## Strings-Palindrome Check in Python (Without Built-in Functions)
## AIM
To write a Python program to check whether the string "google" is a palindrome or not, without using built
in palindrome checking functions.
## ALGORITHM
 1. Assign the string "google" to a variable.
 2. Reverse the string manually using slicing ([::-1]).
 3. Compare the original string with the reversed string.
 If they are equal, print that the string is a palindrome.
 Otherwise, print that it is not a palindrome.
 4. Execute the program.
## PROGRAM
```
def palindrome(a):
    l=[]
    for i in a:
        l.append(i)
    l2=l[::-1]
    if l==l2:
        print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
 s=input()
 palindrome(s)
```
## OUTPUT
![Screenshot 2025-05-25 114450](https://github.com/user-attachments/assets/ad56afb3-dd9e-4f8f-ab2e-877847785d79)

## RESULT
 Thus the program to check whether the string "google" is a palindrome or not, without using built-in
 palindrome checking functions has been executed successfully.

## Tuple in Python: Check Element Existence
## AIM
 To write a Python program that checks if the element 'n' and the element 8 exist within a given tuple.
## ALGORITHM
 1. Define a tuple x with some letters and numbers.
 2. Use the in operator to check if the string 'n' exists within the tuple.
 3. Use the in operator to check if the integer 8 exists within the tuple.
 4. Print the results.
## PROGRAM
```
 t = ("s", 8, "a", "v", "n", "g", "u", "r", "c", "e")
 print(8 in t)
 print('n' in t)
```
## OUTPUT
![Screenshot 2025-05-25 114459](https://github.com/user-attachments/assets/50ef578d-7671-4e74-8221-cb6b7dcafa1e)

## RESULT
Thus, the program executed successfully.
 
 
