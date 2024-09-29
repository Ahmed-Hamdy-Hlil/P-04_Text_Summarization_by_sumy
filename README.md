# Text Summarization Application
This is a Text Summarization Application built using Streamlit and Sumy library. 
The application allows users to input a text and select a summarization type to generate a summary of the text.

## Features
- **Text input area** for users to input the text to be summarized
- **Select box** for users to choose the summarization type (LSA, LUHN, LEX, TEXT)
- **Slider** to select the number of sentences in the summary
- **Button** to generate the summary
- **Display area** to show the generated summary

## Requirements
- **Python 3.x**
- **Streamlit library**
- **Sumy library**
- **NLTK library**
- **Langdetect library**
- **Pyngrok library (for ngrok tunnel)**

## Installation
1. Clone the repository:
    ```using
    git clone https://github.com/yourusername/text-summarization-app.git
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Streamlit application:
    ```bash
    streamlit run _Project_4_Text_Summarization_by_sumy.ipynb
    ```

## Usage
1. **Open the application in your web browser**
2. **Input the text to be summarized in the text area**
3. **Select the summarization type using the select box**
4. **Adjust the number of sentences in the summary using the slider**
5. **Click the "Summarize Text" button to generate the summary**
6. **View the generated summary in the display area**

## Ngrok Tunnel
To access the application from outside the local network, you can use ngrok to create a tunnel. Follow these steps:

- **Install ngrok using pip install pyngrok**
- **Run the application using streamlit run Text_Summarization.py**
- **Open a new terminal and run ngrok http 8501 to create a tunnel**
- **Copy the ngrok URL and access the application from outside the local network**

## Contributing
Contributions are welcome! If you have any ideas or suggestions, please open an issue or submit a pull request.

## Acknowledgments
- Streamlit library for building the web application
- Sumy library for text summarization
- NLTK library for natural language processing
- Langdetect library for language detection
- Pyngrok library for ngrok tunnel
# Note: Replace your-username with your actual GitHub username.
