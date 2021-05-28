# Geoparsing with Python

This weeks lab focused on geoparsing text to extract city names from a .txt file. Once the names were extracted, the code turns the 
data into points with latitude and longitude and then plots a histogram and a map of the frequencies. 


### Questions
A link to your Github repo with your response to the Coding Challenge at the end. The repo must contain your Python code (either as script in `.py` or a notebook in `.ipynb` format). The `README` of your repo should introduce your code and answers some questions about the code used in this tutorial.

I purposely chose a book that didn't have many real places in it because I wanted to see how the code would plot the data. The .txt file that I used is called, "Gulliver's Travels" and was published in 1726 as a fictional account of a man's journey around a fictional world. There are real places mentioned (for example, Oxford) but there are also fictional locations (like "Laputa"). What was surprising to me about the output is that most common "Location" was the word, "of" which is not a location. Also, it seems that all of the locations in England were plotted incorrectly. Oxford was plotted in Pennsylvania, USA instead of in the U.K. 


Mapping this data could be better displayed if there was maybe a different basemap. I think that removing duplicates would be best for the data in this book because it normally references where people are from and it doesn't represent repeat travel or frequency. 


