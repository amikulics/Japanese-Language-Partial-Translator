# Japanese Language Partial Translator
 
This program can translate Japanese input strings. The input strings are written in english such as: "watashi wa sensei desu ." then the program can check that each word is a valid Japanese word and if the order of the words is syntactically correct. Lists of these input strigns can be found in the tests folder and these can be used to test the program. 

The following DFA was used to confirm the validity of a word:
![group19DFA - Copy](https://user-images.githubusercontent.com/61123082/122986934-e190aa00-d354-11eb-9124-0464db05c8a1.PNG)

Then, a LL1 parser was used to check the grammar and syntax. Once the words were confirmed as valid then the program checks if the Japanese word was one of the unique words that is stored in the lexicon. This program can also be expanded a lot very easily by adding more words to the lexicon. 
