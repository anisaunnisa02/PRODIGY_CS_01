Caesar Cipher Program

This is a simple Python program that implements the Caesar Cipher for encrypting and decrypting messages. 

The program consists of two main functions: caesar_cipher_encrypt and caesar_cipher_decrypt, along with a main function that provides a user interface for encrypting and decrypting messages.

Functions

i) caesar_cipher_encrypt(text, shift)

   Encrypts a given text using the Caesar Cipher method.

   Parameters:
   
   a) text (str): The input text to be encrypted.
   b) shift (int): The number of positions each letter in the text is shifted.

   Returns:
   
   str: The encrypted text.

   Example:
   
   caesar_cipher_decrypt("Khoor, Zruog!", 3)
   # Output: "Hello, World!"

ii) caesar_cipher_decrypt(text, shift)

    Decrypts a given text using the Caesar Cipher method.

    Parameters:
    
 a) text (str): The input text to be decrypted.
 b) shift (int): The number of positions each letter in the text was shifted.
 
    Returns:
    
    str: The decrypted text.
    
    Example:
    
  caesar_cipher_decrypt("Khoor, Zruog!", 3)
  # Output: "Hello, World!"
  
Main Function
 main():
 
Provides a user interface for the Caesar Cipher program. It allows the user to choose between encryption and decryption, input the message, and specify the shift value.

User Interaction:

a) The user is prompted to choose whether they want to encrypt or decrypt a message.
b) The user is then asked to input the message and the shift value.
c) Based on the user's choice, the program outputs either the encrypted or decrypted message.

Example Usage:

Welcome to the Caesar Cipher program!
Do you want to (e)ncrypt or (d)ecrypt a message? e
Enter your message: Hello, World!
Enter the shift value: 3
Encrypted message: Khoor, Zruog!






