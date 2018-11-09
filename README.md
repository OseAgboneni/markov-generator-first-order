# markov-generator-first-order
Python implementation of a first-order Markov Text Generator

This is a simple Markov chain text generator that reads in a text file and recreates a passage in the same literary style as the input file.

TO RUN:

First, make sure you have a few text files in the same directory as this python file. Run the Markov Text Generator file in the shell. Once in the shell, call the create_dictionary(filename) function, where filename is a string containing the name of the text file you want to read (don't forget to add the '.txt' at the end of the file's name!). If you just call the function like this, you'll end up displaying the dictionary on the shell which can look messy, so instead save it to a variable (e.g. type "dict = create_dictionary("myFile.txt")" in the shell). Once you've saved the dictionary to a variable, call the second function generate_text(word_dict, num_words), where word_dict is the dictionary you just created with the first function call and num_words is the number of words you want generated. A healthy-looking passage would have 75 to 100 words.

