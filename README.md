### EX9 Preprocessing on Twitter Data using Rapidminer
### DATE: 
### AIM: To implement preprocessing technique on Twitter Data using Rapidminer
### Description: 
<div align = "justify">
RapidMiner provides data mining and machine learning procedures including: data loading and transformation (ETL), data preprocessing and visualization, 
predictive analytics and statistical modeling, evaluation, and deployment. RapidMiner is written in the Java programming language. 
RapidMiner provides a GUI to design and execute analytical workflows. Those workflows are called “Processes” in RapidMiner and they consist of multiple “Operators”. 
Each operator performs a single task within the process, and the output of each operator forms the input of the next one. Alternatively, the engine can be called from 
other programs or used as an API. Individual functions can be called from the command line. 
RapidMiner provides learning schemes, models and algorithms and can be extended using R and Python scripts.

### Procedure:
1) ***Import Twitter data:*** Import the Twitter data into RapidMiner. You can do this by selecting the appropriate
data source operator, such as "Read Excel" or "Read CSV," and specifying the location of your Twitter data
file.
2) ***Preprocess data:*** Preprocess the imported data to clean and prepare it for text processing. Use the following
operators for preprocessing:
    <p>a. Tokenize: Split the text into individual words or tokens.
    <p>b. Transform Cases: Convert the text to lowercase or uppercase to ensure consistency.
    <p>c. Remove Stopwords: Remove common words that do not provide much meaningful information.
    <p>d. Remove Special Characters: Eliminate special characters, such as punctuation marks or symbols.
    <p>e. Remove Numbers: Exclude numeric values from the text.
3) ***Stemming:*** Apply stemming to reduce words to their root forms. You can use operators like "Stem (Porter)"
for this purpose.


### Output:
<img width="1033" height="550" alt="364754429-5d340e5e-14c1-4626-8a18-a006f723da62" src="https://github.com/user-attachments/assets/b926500a-295b-407e-a691-140edce88ca8" />


<img width="1036" height="534" alt="364754469-c48bc18e-9f01-4020-8e30-8d130e1784ea" src="https://github.com/user-attachments/assets/6eec90f7-9883-4238-95ac-029449bdfe36" />


<img width="1035" height="536" alt="364754533-288926ef-0ae6-4012-8799-93ad678b8572" src="https://github.com/user-attachments/assets/ab03db2e-631e-4f03-b054-09618502a6df" />



### Result:
