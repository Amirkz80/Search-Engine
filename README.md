# Search-Engine

The purpose of this project is to build a search engine

A Search Engine which can INDEX documents and perform BOOLEAN search or RANKED retrieval.


## Description
- This program is written in Python and JavaScript

- The goal of this project is to build a search engine that finds the most relevant information to the query by using a web crawler and displays them in the order of the highest ranking.

**Code section :**

In this project, we have several sections of Python code to calculate and perform project operations and a JavaScript section for the UI part of the program.
And it includes a repo file in which there are ten text files that the program operates on.

The names of the different parts of the Python code are as follows: 
<search_engine, ranking_test, ranking_functions, index, boolean_tokenizer , boolean_parser , boolean_operators>

And there is a UI component built with JavaScript and the React library.

- Boolean_operators:

   This part of the code performs Boolean operations such as AND, OR, NOT and includes a Boolean search function to see which document a word is in.

- Boolean_tokenizer:

   Before parsing, we must first tokenize, in such a way that it recognizes and separates operators from words.
   We do this by using this part of the code.

- Boolean_parser:

   This part of code parses the user's Boolean query and determines what to do with the input query.

- Ranking_functions:

   This part of the code includes functions for ranking and tokenization (ranking tokenization is different from boolean tokenization) and tf-idf calculations.

- Index:

   By running this part of the code once, it inverted indexes the entire repository files, which means it shows which documents each word is in.

- Search_engine:

  This part of the code is the backend of the program and by running the program, it brings up the server so that we can access the program.
  (Flask framework is used in the backend part of this program.)

- Ranking_test:

  This part of code is for testing the correct working of the program.

### The result of the program:
 In the search box, the client enters the query and if there are Boolean symbols (AND, OR, NOT), the program detects and returns the Boolean result, and if there are no Boolean symbols, it returns the result as a ranking.

**Challenges :**
- One of the most important challenges we faced in this project is the speed of the program 
That we solved this challenge in the best way by using algorithms and correct coding method.

- Another challenge was how to test the program and ensure that the program is correct 
To solve this challenge, a test program has been written


**Program execution test :**

![2](https://user-images.githubusercontent.com/63232995/179480508-5392662a-84e6-4889-bbd5-b26fb1731994.jpeg)

We have written a test code in the image above to test the correct working of the program.
As you can see, we have determined the correct answer in advance and with this test we want to find out whether we get the same result or not.
By viewing the result in the terminal, we can see that the program is working correctly.


**In progress :**
- Parsing more complicated boolean queries
- Designing Ranked Retrieval system and implement it
- Building a crawler to search Wikipedia

**Lisense**

*Any copying of this project is not allowed unless the source is mentioned.*
