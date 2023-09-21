# NLP-Project-
NLP Project, Sentiment towards Dual Share Class Policy in Hong Kong

Due to the Confidentiality of the data and insights as the project is still a work in progress, my code can only be uploaded with no output provided. 

Each Row contains the text and published_date
Here is a run through of the code in segments:

1) I preprocess text in pdfs to an array and concatenated them into a dataframe
2) Small Data Cleaning using Pandas
3) NLP Process:
   - Remove Stopwords and lemmatize words so that the I can just count 1 of each type of word (EG. Counting to count), as both have the same meaning but different form, we do not double count
   - Remove Chinese and English names as the Text has alot of them
   - CountVectorizer to count the number of words appearing on each text and convert to a sparse matrix
   - TF-IDF to also analyse the relative importance of each word amongst all words for each text. (Note this part was added initially, but was taken out later to suit organisational needs)
