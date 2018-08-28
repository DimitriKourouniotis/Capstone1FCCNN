## Dimitri Kourouniotis Data Scientist

Analysing FCC Net Neutrality Comments using Machine Learning and NLP

Supervised Machine Learning using NLP
by Dimitri Kourouniotis
In the winter of 2017 there were numerous articles about quantity of fake comments submitted regarding the repeal of Net Neutrality laws by the FCC.

A blog post published by Jeff Kao caught my attention and I followed up with him on his analysis of the text. He provided me with the unedited 22 million filings available. I analyzed a sample of 3 million of them to see what I could find to develop my own features based around the text of faked comments.

00 Summary and Table of Contents

01 Importing 3 million FCC records from SQL

02 Email domains

03 WordCloud

04 Submission Frequency

05 State Population Estimates 2016 and Comment Percentages

06 Plotting Differences from Average

07 Chorogrid Map of US

08 Statistics Proportions by State Relative to Population

09 Classifiers and Feature Selection

Acknowledgements
Many thanks to my mentor, Rajiv Shah!
Thanks to the following for the data and code help for this capstone:
Data: Jeff Kao
More than a million pro-repeal net neutrality comments were likely faked
https://hackernoon.com/more-than-a-million-pro-repeal-net-neutrality-comments-were-likely-faked-e9f0e3ed36a6

Word Cloud: Nikhil Kumar Singh
wordcloud example
https://github.com/nikhilkumarsingh/wordcloud-example/blob/7a77e97c4da135b67ad924be96269d6bb68a0fe6/mywc.py

Chorogrid Plot: lavinben88
chorogrid tutorial part 2
https://plot.ly/~lavinben88/116/chorogrid-tutorial-part-2-chorogri/

Classifier Iterator: Evgeny Volkov
SMS spam detection with various classifiers
https://www.kaggle.com/muzzzdy/sms-spam-detection-with-various-classifiers
