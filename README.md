# NLP Project - Wikipedia Data Extraction and Classification
<h1>Overview</h1>
<h2>This project involves extracting information from Wikipedia for a predefined list of topics and creating a labeled dataset for natural language processing (NLP) tasks. The extracted data is preprocessed, and a dataset is generated with the intention of classifying topics into "Medical" and "Non-Medical" categories.</h2>
<h3>The goal of this project is to fetch data from Wikipedia for a list of predefined topics, preprocess the extracted text, and create a labeled dataset for NLP tasks. The project includes data extraction, preprocessing, dataset creation, and a basic NLP classification model. <br><br> The code fetch get data from wikipedia based on the given topics which are separeted as medical and non medical. Then after fetching the dataset is saved as nlp_dataset.csv then after it tokenize and lemataize. The next step is using the Naive Bayes approch implemented.</h3>
<h2>The following steps are applied to implement the code</h2>
<h4>1. Imports necessary libraries:
      <h5>Example: necessary nltk library files</h5> </h4>
<h4>2. Defines a list of topics (titles):
      <h5>These topics are related to both medical and non-medical fields.</h5></h4>
<h4>3. Fetches data for each topic and preprocesses it:
      <h5>Iterates through each topic, fetches data using the fetch_data function, extracts the first 500 characters of the Wikipedia extract, and adds it to the DataFrame.</h5></h4>
<h4>4. It prints the dataset after completing all those steps</h4>
<h4>5. Finally implements the Naive Bays algorithm for the project</h4>
