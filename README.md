#Dictionary Program
This is a Python-based dictionary program that allows users to look up the definition of a word from a JSON file. The program uses the difflib library to provide suggestions for close matches if the entered word is not found.

Features
Search for a word and get its definition.
If a word is not found, the program suggests the closest matches.
The user can confirm if they meant a suggested word or exit.
Requirements
Python 3.x
Setup

#Clone the repository:
bash
Copy
Edit
git clone https://github.com/Ga6i/Dictionary.git

#Navigate to the project directory:
bash
Copy
Edit
cd Dictionary
Ensure that you have Python installed on your machine. 

#You can verify this by running:
bash
Copy
Edit
python --version
If you don't have Python installed, download and install it from here.



Usage
Open the Dictionary.py file.

Run the script:
bash
Copy
Edit
python Dictionary.py
The program will prompt you to enter a word.

It will display the definition of the word if it's found. If the word is not found, it will suggest close matches and ask if you meant one of those.

Example
bash
Copy
Edit
Enter a word you would like to search: jovial
Did you mean jovial instead? Enter Y if yes, otherwise N to exit: Y
cheerful and good-humored
Vocab.json
The Vocab.json file contains the words and their definitions used by the dictionary program. You can modify this file to add more words and definitions to expand the dictionary.

