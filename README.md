# Tools for Text Analysis
A variety of tools to facilitate analysis of text.

I initially developed these tools to facilitate analysis of reports written by carers about patients whom they were looking after.

Due to patient confidentiality, I cannot upload the full sample of reports. I have uploaded a small artificial sample ('Reports.csv') to demonstrate the nature and structure of the reports.

Due to Intellectual Property restrictions, I cannot upload all of the tools developed.



## Sentence Splitter.ipynb
This script will take unstructured free text data within the chosen column of a csv file and return a dataframe with one row for each sentence.

This can be used to facilitate sentence-by-sentence analysis, as may be beneficial in certain types of machine learning analysis.



## Keyword Analysis.ipynb
This script enables a user to search a set of keywords and receive a table detailing the number of reports containing those particular keywords.


## CSV_to_TXT.ipynb
This script takes every cell in the column of a CSV file, concatenates their contents and outputs a single TXT file.

The original purpose was to facilitate the development of a carer report language model using Keras, by feeding in a continuous TXT file.

