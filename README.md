### EX9 Preprocessing on Twitter Data using Rapidminer
### DATE: 29.08.2024
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
![Screenshot 2024-08-29 210931](https://github.com/user-attachments/assets/8bcc9258-2afc-4742-9c0a-83858152ca66)
![Screenshot 2024-08-29 210908](https://github.com/user-attachments/assets/2b93d79a-88e6-4441-9468-411e55784c1a)
![Screenshot 2024-08-29 203335](https://github.com/user-attachments/assets/4a44eb62-29b9-46ca-ad01-edba722c339c)
![Screenshot 2024-08-29 210853](https://github.com/user-attachments/assets/4015134b-5430-4b7c-b354-de241fc22b20)
![Screenshot 2024-08-29 204527](https://github.com/user-attachments/assets/bcedfb22-0733-4292-a9c5-8dbe1150e678)
![Screenshot 2024-08-29 205652](https://github.com/user-attachments/assets/5f78945e-de77-474b-aa67-5c94e1af1abb)
![Screenshot 2024-08-29 210607](https://github.com/user-attachments/assets/01bf68cf-d110-4e79-83f7-23e99e502fde)
![Screenshot 2024-08-29 210752](https://github.com/user-attachments/assets/4d31e038-284b-47e4-b13f-afa03d02744f)

### Result:
Thus the implement preprocessing technique on Twitter Data using Rapidminer is executed successfully.
