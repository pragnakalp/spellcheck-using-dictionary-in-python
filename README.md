
# Dictionary based spell checking in Python
SpellCheck is a spelling checking and correction module in Python built using Fuzzywuzzy string matching module.

### Steps to get started

 1. Create your own dictionary of word
 2. Import the spellcheck module in your script  
	`from spellcheck import SpellCheck`
	
 3. Initialize the spellcheck object in your code  
	`spell_check =  SpellCheck('words.txt')`
	
 4. Set the string to be checked  
	`string_to_be_checked =  "Gujrt Delh Vodadra"`  
	`spell_check.check(string_to_be_checked)`
	
 5. Use the object to get suggested words or corrected string  
	`print(spell_check.suggestions())`  
	`print(spell_check.correct())`

Change the fuzzy matching percentage in the spellcheck.py file to suite your need.

Do suggest for any improvement. 

> Developed by the members of [Pragnakalp](https://www.pragnakalp.com/)

