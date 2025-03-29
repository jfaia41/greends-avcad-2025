## Answers for the exercise 1

### 1. How many variables are used to create the word cloud?
The word cloud you created uses three main variables. First, the text, the words that are bwing used to generate the cloud (the full text). 
Second, there are stopwords, like "o", "e", or "para", that i didn't want to show up in the word cloud. 
Lastly, the word cloud is defined by a mask, an image that the words are bounded by.

### 2. What type is each variable in the word cloud?
The types of these three variables are as follows:

The Text is a string variable because it is made up of words.
The Stopwords are a set of words.
The Mask is a array that has value 255 and 0 in order to determine the box in which the words should arranged in.