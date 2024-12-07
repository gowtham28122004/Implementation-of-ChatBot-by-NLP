# ChatBot Implementation Using NLP

This project implements a simple chatbot using Natural Language Processing (NLP) techniques. It employs `nltk` for text preprocessing, `scikit-learn` for machine learning, and `streamlit` for building an interactive web interface. The chatbot recognizes user input and responds based on pre-defined intents using a logistic regression model.

## Features

- **Text Preprocessing**: Tokenization and text normalization using `nltk`.
- **Machine Learning Model**: A Logistic Regression model trained on TF-IDF features for intent classification.
- **Interactive Web Interface**: Built using `streamlit` to allow users to interact with the chatbot.
- **Customizable Intents**: Easily extendable to add more intents and responses.

## Technologies Used

- Python 3.x
- Natural Language Toolkit (`nltk`)
- scikit-learn (for machine learning models)
- Streamlit (for interactive web interface)
- JSON (for intent data)
- CSV (for storing chat logs)
  
## Project Setup

### Prerequisites

Before setting up the project, make sure you have the following installed:

- Python 3.x
- `pip` (Python package installer)
- Git (optional for cloning the repository)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/gowtham28122004/Implementation-of-ChatBot-by-NLP.git
    ```

2. Navigate to the project directory:

    ```bash
    cd P4-Implementation-of-ChatBot-by-NLP
    ```

3. Create a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    ```

4. Activate the virtual environment:
   
   - For **Windows**:
   
     ```bash
     venv\Scripts\activate
     ```
   - For **macOS/Linux**:
   
     ```bash
     source venv/bin/activate
     ```

5. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

### Dependencies

The required dependencies are listed in `requirements.txt`:

- `nltk`: Natural Language Toolkit, used for text preprocessing.
- `streamlit`: For creating an interactive user interface.
- `scikit-learn`: Used for machine learning, including the TF-IDF vectorizer and logistic regression model.
- `json`: For handling intent data.
- `csv`: For storing conversation logs.
  
Run the following command to install the dependencies:

```bash
pip install -r requirements.txt
