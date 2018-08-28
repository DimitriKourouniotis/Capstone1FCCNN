## Dimitri Kourouniotis Data Science Enthusiast

# Analysing FCC Net Neutrality Comments using Machine Learning and NLP

Supervised Machine Learning using NLP
by Dimitri Kourouniotis
In the winter of 2017 there were numerous articles about quantity of fake comments submitted regarding the repeal of Net Neutrality laws by the FCC.

A blog post published by Jeff Kao caught my attention and I followed up with him on his analysis of the text. He provided me with the unedited 22 million filings available. I analyzed a sample of 3 million of them to see what I could find to develop my own features based around the text of faked comments.
![Image of Jeff Kao Article](https://github.com/DimitriKourouniotis/Capstone1FCCNN/blob/master/images/SplashMoreThanaMillion.jpg)
<hr>

<a href="https://github.com/DimitriKourouniotis/Capstone1FCCNN/blob/master/Capstone%201%20Report%20FCC%20Net%20Neutrality%20Submissions.pdf">Capstone Report (pdf)</a>

<a href="https://github.com/DimitriKourouniotis/Capstone1FCCNN/blob/master/Capstone%201%20Slidedeck%20FCC%20NLP%20NN%20Kourouniotis.pdf">Capstone Summary Slidedeck (pdf)</a>

<a href="https://github.com/DimitriKourouniotis/Capstone1FCCNN/blob/master/00%20Summary%20and%20Table%20of%20Contents%20and%20Acknowledgements.ipynb">00 Summary and Table of Contents</a>

<a href="https://github.com/DimitriKourouniotis/Capstone1FCCNN/blob/master/01%20Importing%203m%20FCC%20records%20from%20SQL%20.ipynb">01 Importing 3 million FCC records from SQL</a>

<a href="https://github.com/DimitriKourouniotis/Capstone1FCCNN/blob/master/02%20Capstone%201%20Email%20domains.ipynb">02 Email domains</a>
![Emails from fake domains or fake accounts](https://github.com/DimitriKourouniotis/Capstone1FCCNN/blob/master/images/Domains.png)

<a href="https://github.com/DimitriKourouniotis/Capstone1FCCNN/blob/master/03%20WordCloud.ipynb">03 WordCloud</a>
![Wordcloud of comments](https://github.com/DimitriKourouniotis/Capstone1FCCNN/blob/master/images/wc.png)

<a href="https://github.com/DimitriKourouniotis/Capstone1FCCNN/blob/master/04%20Capstone%201%20FCC%20Submissions%20Frequency.ipynb">04 Submission Frequency</a>
![Suspcious submission timing](https://github.com/DimitriKourouniotis/Capstone1FCCNN/blob/master/images/SubmissionsPerMinute.png)

<a href="https://github.com/DimitriKourouniotis/Capstone1FCCNN/blob/master/05%20Capstone%20State%20Pop%20estimates%202016%20and%20Comments%20percentages.ipynb">05 State Population Estimates 2016 and Comment Percentages</a>
![Comments by state variations from population](https://github.com/DimitriKourouniotis/Capstone1FCCNN/blob/master/images/Stemplot_differences.png)

<a href="https://github.com/DimitriKourouniotis/Capstone1FCCNN/blob/master/06%20Capstone%201%20plotting%20differences%20from%20average.ipynb">06 Plotting Differences from Average</a>
![Comments by state variations from Normal](https://github.com/DimitriKourouniotis/Capstone1FCCNN/blob/master/images/DistributionOfDifferencesNorm.png)

<a href="https://github.com/DimitriKourouniotis/Capstone1FCCNN/blob/master/07%20Capstone%201%20Choropleth%20Map%20USA%20.ipynb">07 Choropleth grid Map of US</a>
![Variations mapped](https://github.com/DimitriKourouniotis/Capstone1FCCNN/blob/master/images/chorogridVariationsFromState.jpg)

<a href="https://github.com/DimitriKourouniotis/Capstone1FCCNN/blob/master/08%20Capstone%201%20Stats%20Proportions%20by%20State%20relative%20to%20Population.ipynb">08 Statistics Proportions by State Relative to Population</a>

<a href="https://github.com/DimitriKourouniotis/Capstone1FCCNN/blob/master/09%20Classifiers%20and%20Feature%20Selections.ipynb">09 Classifiers and Feature Selection</a>
<hr>


## Acknowledgements


Many thanks to my mentor, Rajiv Shah!

### Thanks to the following for the data and code help for this capstone:<br>
Data: Jeff Kao<br>
More than a million pro-repeal net neutrality comments were likely faked<br>
https://hackernoon.com/more-than-a-million-pro-repeal-net-neutrality-comments-were-likely-faked-e9f0e3ed36a6

Word Cloud: Nikhil Kumar Singh<br>
wordcloud example<br>
https://github.com/nikhilkumarsingh/wordcloud-example/blob/7a77e97c4da135b67ad924be96269d6bb68a0fe6/mywc.py

Chorogrid Plot: lavinben88<br>
chorogrid tutorial part 2<br>
https://plot.ly/~lavinben88/116/chorogrid-tutorial-part-2-chorogri/

Classifier Iterator: Evgeny Volkov<br>
SMS spam detection with various classifiers<br>
https://www.kaggle.com/muzzzdy/sms-spam-detection-with-various-classifiers
