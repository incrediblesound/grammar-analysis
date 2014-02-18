grammar-analysis
================

A set of js functions for analyzing the grammar of a text

gramAnalysis
------------

This function takes a string, ideally a passage of text such as an essay, article, story or poem, and returns two objects. 
The first object is called 'grammarSchema'. GrammarSchema is an array of the lines of the argument string with everything
but punctuation and common grammar words converted to dashes. This allows the user to clearly see the grammatical structres 
used in the argument string. The second object is called 'grammarEval' and contains the average content words, commas, and common
grammatical particles per line.
