# Chatbot-Using-Cosine-Similarity
# 📜Overview
This project is a simple chatbot designed to provide answers to user queries by leveraging cosine similarity for question matching. The chatbot processes user input by performing tokenization and removing stopwords to focus on the core meaning of the query. It then compares the processed input against a pre-defined list of questions using cosine similarity to identify the most relevant match. If a match is found, the chatbot returns the corresponding answer. Otherwise, it responds with a fallback message: "We can't answer this." This lightweight and efficient approach ensures accurate question matching and offers a customizable foundation for building advanced chatbot systems.

# ⚙️How it Works
The chatbot identifies the best match for user input using cosine similarity. It operates on a pre-defined list of questions and answers stored in the test.csv file, which is loaded at the start of the program. When a user enters a query, the following steps are executed:

Tokenization: The input is broken down into individual words or tokens for processing.

Stopword Removal: Common words like "is," "the," and "a" that add little value to understanding are filtered out to minimize noise.

Cosine Similarity Calculation: The similarity between the user's input and each stored question is computed. The question with the highest score is selected as the best match.

Response Generation: If a match is found, the corresponding answer is displayed. Otherwise, the chatbot responds with, "We can't answer this."

🔄![image](https://github.com/user-attachments/assets/cc205817-9ab8-45b3-83db-c20605805b2e)
