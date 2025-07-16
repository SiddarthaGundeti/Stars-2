# Stars-2

write a program that reads a word and prints the word in the given format.

Explanation:

This Python program is designed to read a word and then print it in a specific format. The key requirement is to surround the word with a number of asterisks (*) that matches the length of the word. The stars are to be placed both before and after the word, separated by a space.

Logical Approach:

Read Input:
Read the word from user input.

Calculate Word Length:
Determine the length of the word using the len() function. This length will dictate the number of stars to be placed around the word.

Format and Print the Word:
Use string concatenation to create the desired format.
Multiply the string "*" by the length of the word to create a string of stars equal to the word's length.
Place the word in between these strings of stars, separated by spaces.
Print the final formatted string.

Example for Clarity:

If the input word is Code:
The length of Code is 4.
Create a string of 4 stars, then the word Code, then another string of 4 stars, separated by spaces.
The formatted output is **** Code ****.
