### SMS Spam Classifier

#### Introduction
This project involves the development of a web application designed to classify SMS messages as either "Spam" or "Not Spam." By utilizing text preprocessing, TF-IDF vectorization, and a trained machine learning model, the application provides users with an efficient and interactive way to filter unwanted messages. The user interface is built with Streamlit, ensuring ease of use and accessibility.

#### Libraries and Tools
The project relies on several key libraries and tools:
- **Streamlit**: Powers the web application interface, enabling user interaction.
- **Pickle**: Facilitates loading of pre-trained models and vectorizers.
- **NLTK (Natural Language Toolkit)**: Handles natural language processing tasks, including tokenization, stopword removal, and stemming.
- **Scikit-learn**: Provides machine learning functionalities, particularly for model training.
- **Python**: The core programming language used for developing the project.

#### Methodology

##### Data Preprocessing
The text messages undergo a series of preprocessing steps to prepare them for analysis:
1. **Lowercasing**: Converts all text to lowercase to maintain uniformity.
2. **Tokenization**: Splits the text into individual words for detailed analysis.
3. **Removing Non-Alphanumeric Characters**: Filters out non-alphanumeric characters to reduce noise.
4. **Removing Stopwords and Punctuation**: Eliminates common words and punctuation that do not contribute significant meaning.
5. **Stemming**: Reduces words to their root forms, aiding in the handling of different word variations.

These steps ensure the text data is clean and suitable for subsequent vectorization and classification processes.

##### Vectorization
The preprocessed text is transformed into numerical vectors using TF-IDF. This technique assigns weights to words based on their frequency in a document relative to their frequency in the entire corpus, highlighting important words in the text. The resulting vectors are crucial for the machine learning model to process and analyze the text data effectively.

##### Classification
The project employs a pre-trained machine learning model to classify the vectorized text as either "Spam" or "Not Spam." Trained on a labeled dataset of SMS messages, the model leverages learned patterns and features to predict the class of new messages accurately.

#### Implementation
Using Streamlit, the application offers a straightforward and interactive user interface. Users can input an SMS message into a text area and click the "Predict" button. The application then preprocesses the text, vectorizes it, and applies the trained model to classify the message. The result is displayed as "Spam" or "Not Spam."

#### Usage
To use the application:
1. Launch the Streamlit application.
2. Enter an SMS message into the provided text area.
3. Click the "Predict" button to classify the message.
4. View the result displayed as either "Spam" or "Not Spam."

#### Conclusion
The SMS Spam Classifier project showcases the power of natural language processing and machine learning in filtering unwanted messages. Streamlit's user-friendly interface makes the application accessible to a broad audience, enhancing its practical utility.

### HOW THE OUTPUT LOOKS LIKE

![spam1](https://github.com/user-attachments/assets/38a59292-9715-4706-b771-6d44be9e9ce5)
![spam2](https://github.com/user-attachments/assets/028314fb-98b6-4cda-98da-313f15b057d9)
![spam3](https://github.com/user-attachments/assets/a8115336-8b4f-4b25-9215-da59fd04fe5b)
