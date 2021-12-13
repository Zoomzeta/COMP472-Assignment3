# COMP472-Assignment3
Mini-Project number 3 of COMP 472

It is relatively straightforward, first step is to open the text file, paste the first two lines of code, and paste them on python. Make sure to write the name of the model you wish to load from the list available before pressing enter. 

You can paste the rest and, using the similarity method, the program should return a floating value that respresents how similar a guess-word is to a question-word. Each question-word comes with 4 guess-words. The larger the floating value is, the most similar that word is to the question word. If an error pops, it just means either the question-word or any of the guess-words are not currently a part of the model.

All the results have been written in csv files, with each line containing the question-word, the correct-word, the guess-words, and a label that identifies if the the correct-word is either correct, wrong, or just a guess (i.e. if either the question-word or all 4 guess-words are not in the model).

An additional csv file shows an analysis of each model and their performances, including their vocabulary sizes, the number of correct words each got, the number of questions that have been answered without guessing, and their accuracy.

There are also graphs that compares the performances of each model, highlighting the results in the last 3 columns in the analysis file.
