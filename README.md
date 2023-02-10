# Text_analysis

In this text analysis procedure we scrapped some articles and preceded some analysis on it, which inculdes the following:

##Sentimental Analysis
Sentimental analysis is the process of determining whether a piece of writing is positive, negative, or neutral. The below Algorithm is designed for use in Financial Texts.

##Average Number of Words Per Sentence
The formula for calculating is:
Average Number of Words Per Sentence = the total number of words / the total number of sentences

##Complex Word Count
Complex words are words in the text that contain more than two syllables.

##Word Count
We count the total cleaned words present in the text by 
removing the stop words (using stopwords class of nltk package).
removing any punctuations like ? ! , . from the word before counting.

##Syllable Count Per Word
We count the number of Syllables in each word of the text by counting the vowels present in each word. We also handle some exceptions like words ending with "es","ed" by not counting them as a syllable

##Personal Pronouns
To calculate Personal Pronouns mentioned in the text, we use regex to find the counts of the words - “I,” “we,” “my,” “ours,” and “us”. Special care is taken so that the country name US is not included in the list.

##Average Word Length
Average Word Length is calculated by the formula:
Sum of the total number of characters in each word/Total number of words


