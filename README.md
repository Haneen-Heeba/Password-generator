# Password-generator
Security is one of the most crucial parts of our lives. The importance of security is increasing day by day as most things are going online. Passwords come into light as we talk about security.  

Password Generator 🔢 : The best thing about creating our own password generator is that we can customize it as we like. First, we will create a password generator that asks the length of the password and generates a random password containing digits, alphabets, and special characters. Next, we will improve it by asking the number of each type of character, like the number of digits, alphabets, and special characters.  

Steps for creating a password generator :  
1. Store all the characters as a list. We can use the string module of Python or type all of them. 
2. Ask the user to enter the length of the password. 
3. Shuffle the characters using the random.shuffle method. 
4.Initialize an empty list to store the password. 
5. Write a loop that iterates length times. 
6. Pick a random character from all the characters using the random.choice method. 
7. Append the random character to the password. 
8. Shuffle the resultant password list to make it more random. 
9. Convert the password list to string using the join method. 
10. Print the password.
