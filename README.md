# Project of week 1. Encrypting & decrypting text

## Description
The program is intended to allow the user to input a text and choose if he wants to encrypt it or decrypt it. I would like to create a translation table, to be used for the encryption (option 1. using just english alphabet 2. maybe using full ASCII, if making life hard for myself - could give the user a choice of encryption method adding as caesar cypher as well). 

### Tasks(for one encryption option only)

1. Create the lists for original alphabet and encrypted alphabet (alternatively use ASCII)
2. Create translation table (using maketrans())
3. Create the function for user to choose if they want to 1)encrypt or 2)decrypt the text
4. Create the function for user input 
5. If user  picks 1) run str.translate(translation table)
6. if user picks 2) run str.translate(reverse translation table)
   (5&6 would work if using a specific language alphabet, not sure yet how to do it with ASCII)
7. Return the message
