# Bracket-Checker
Balanced paranthesis (round, curly and square) checker implemended in C++ for a first year project


Spell CorrectorSpell correctors can work in various ways.  In our version of a spell corrector, 
the program will read atext file to be checked and produce another file with the correctly spelled text in it.  
Any given wordin file can either be correctly spelled or incorrectly spelled.
To do:

1.Dictionary:  Program should read the provided dictionarydict.txtfrom file, and insert it intoappropriate data structure.

2.Spell Checker:  After loading the dictionary,spellCheckerwill read the file input and each of its words will be checked with help 
of dictionary if the word is found its considered correctlyspelled, and written incorrectfile.

3.Spell Corrector:  What is a spell checker if it cant give you the alternate options for wrong spellings.  
For spell corrector, after finding words that arn’t correct, find the correct alternatesand ask the user which one they prefer 
and write that incorrectfile.

4.  To increase the hit rate of spellCheck its advisable that words should be reduced to their rootsas most dictionaries only have root
words.This will require some preprocessing on the word tobe checked according to the language rules governing this process.
Preprocessing
•Convert the word into lowercase
•If the word ends in -ing, remove the -ing
•If the word ends in -s, remove the -s
•If the word ends in -es, -ly, or -ed, remove the -es, -ly, or -ed
•If the word ends in -ing, remove the -ing and add -e
•If the word ends in -ies, remove the -ies, and add -y
•If the word ends in -es or -ed, remove the –s or –d
