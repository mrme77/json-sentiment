# Project Title

Python Requests, JSON, and basic NLP with spaCy

## Description

This project is part of the Web Mining and Applied NLP (44-620) course, student's name is Pasquale Salomone. The notebook aims at reviewing some python functionalities like requestes, JSON, and basic NLP with spaCy. Here is the link to the Github repository: [Github Repo](https://github.com/mrme77/json-sentiment/blob/master/README.md).

## Table of contents

### Question 1 
The following code accesses the lyricsgenius API since the lyrics.ovh public api is no longer available; it searches for the lyrics of a song, and stores it in a dictionary object. Write the resulting json to a file (either a JSON file or a pickle file; you choose). You will read in the contents of this file for future questions so we do not need to frequently access the API.

### Question 2 
Read in the contents of your file. Print the lyrics of the song (not the entire dictionary!) and use spaCyTextBlob to perform sentiment analysis on the lyrics. Print the polarity score of the sentiment analysis. Given that the range of the polarity score is [-1.0,1.0] which corresponds to how positive or negative the text in question is, do you think the lyrics have a more positive or negative connotaion? Answer this question in a comment in your code cell.

### Question 3 
Write a function that takes an artist, song, and filename, accesses the lyrics.ovh api to get the song lyrics, and writes the results to the specified filename. Test this function by getting the lyrics to any four songs of your choice and storing them in different files.

### Question 4 
Write a function that takes the name of a file that contains song lyrics, loads the file, performs sentiment analysis, and returns the polarity score. Use this function to print the polarity scores (with the name of the song) of the three files you created in question 3. Does the reported polarity match your understanding of the song's lyrics? Why or why not do you think that might be? Answer the questions in either a comment in the code cell or a markdown cell under the code cell.

## Installation

To use this project, make sure you have Python 3.8 installed on your system. Do not install modules like math and statistics. You can check your Python version by running the following command in your terminal:

```shell
python --version
```

### Modules

The following modules are required for the installation of this project:

| Module Name | Version |
|---|---|---|
| json| 2.0.9| 
| spacy|3.6.0|
| requests|2.28.1|
| lyricsgenius|3.0.1|
| configparser|5.3.0|
| re          |2.2.1|

## Acknowledgments

I would like to acknowledge the following resources that were instrumental in the development of this project:

- ChatGPT by OpenAI: We used ChatGPT, a powerful language model, to assist in generating responses and providing guidance during the development process. ChatGPT played a crucial role in enhancing the functionality and accuracy of our project.

- Stack Overflow: We would like to express our gratitude to the vibrant community of developers on Stack Overflow. Their valuable insights, code snippets, and solutions to various programming challenges have been immensely helpful in solving problems encountered during the development of this project.

