# Project-1-Star-Wars-Sentiment-analysis

This is a sentiment analysis of the original Star Wars Trilogy. We studied the dialogue from the first three Star Wars movies to determine if there were any differences in the emotions conveyed. We verified this using a Chi-Squared test for both the proportional use of emotional words and the raw counts of emotional words.


## Section 1
### software and platform selection
For this sentiment analysis, we chose to use R Studio. This gave us all the features needed to fully analyze these scripts. We used a number of packages in R that enhance the environment, allowing for sentiment analysis, numerical analysis, and data visualization. The first and most important package is the Sentiment Analysis package in R. This package allows for sentiment analysis to be done on text data. The second package was the tidyverse package in R. This contains a whole lot of packages in the tidyverse, making R much more capable programming software. The third package used was the TM and corpus packages. These two packages are similar in nature and allow for preprocessing of text data so it can be fully analyzed in the Sentiment Analysis. Finally, ggplot and dplyr were also installed to allow us to fully visualize the data and make the syntax in R Studio easier. Other packages that were attached for single function use were: ggplotwordcloud, and textdata. All of this was done on the Mac operating system.


## Section 2
###D ocumentation of the Project
This GitHub repository contains several folders that organize different components of the project. The first folder, named DATA, comprises two subfolders: Preliminary Data and Final Data. The Preliminary Data folder contains original text files that underwent preprocessing to generate the final text files. In the Final Data folder, there are two types of data: processed text files containing the scripts, and a CSV file containing the dataframe derived from these text files, which was used for sentiment analysis.

The Scripts folder contains two subfolders as well. The Preprocessing folder consists of R markdown files detailing the process of converting the original text files into the updated versions. The Analysis folder houses scripts responsible for converting the updated text files into dataframes and performing the required sentiment analysis.

Lastly, the Output folder contains graphs, word clouds, and a CSV file with the values obtained from the Chi-squared test.


## Section 3
### Instructions for Use
To conduct the sentiment analysis yourself, you'll need the R markdown file and the original text files. First, download the appropriate text files from the DATA/preliminary data folder(they are the only ones in there). Once downloaded to a known location, obtain the R markdown files from the Scripts/preprocessing folder(they are the only ones in there). There should be three R markdown files, one for each movie. Open each R markdown file and ensure that your working directory is set to the location of the text files. You can set the working directory at the top of each preprocessing R markdown file.

After running the preprocessing files, three new text files will be saved wherever your working directory is set. Note that this step can be somewhat finicky due to differing encodings on different hardware. If you encounter issues with producing the new workable text files, you can use the provided ones from the DATA/Final data folder. There are three of them one for each movie.

Once the new text files are generated, run the R markdown files in the analysis folder, ensuring that the working directory is set to the location of the new text files. After the analysis completes, all tables, graphs, and analysis will be ready. You can download the visualizations and review the final Chi-squared values inside the R markdown file.
