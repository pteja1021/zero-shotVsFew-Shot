### Description
This project compares the performance of zero-shot vs few-shot learning capabilities of Open AI GPT-4 and Gemini 1.5 pro
The models were tested on SST-2 dataset and Twitter dataset from Kaggle

### Software Requirements
Python 3.9 or above
Jupyter Notebook

### Library Requirements
These can be found in requirements.txt. Install using ```pip install -r requirements.txt```

### Datasets
The SST-2 dataset is loaded from datasets library of Python. 
Twitter dataset is downloaded from Kaggle. Link found here: https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis

### Understanding & Running the project
1. Downlaod the required libraries and datasets from mentioned places.
2. Create a .env file in each folder, place your open ai key with key as OPENAI_API_KEY and gemini using 
3. Inside the twitter folder, place only the twitter dataset csv file. You will find twitter_llm file. This file is targeted towards testing the performance on twitter dataset and print classification matrices
4. Inside the sst-2 folder, You will find sst_llm file. This file is targeted towards testing the performance on sst-2 dataset from python datasets module and print classification matrices to compare performance