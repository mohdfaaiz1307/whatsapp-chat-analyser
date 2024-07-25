WhatsApp Chat Analyser
Overview

The WhatsApp Chat Analyser is a Python-based application designed to analyze WhatsApp chat data. The application offers two modes of analysis: individual person analysis and group-level analysis. It provides comprehensive statistics and visualizations to help users gain insights into their chat data.

Features :

    - Upload Chat Data: Allows users to upload their WhatsApp chat files.
    - Individual/Group Analysis: Choose between analyzing individual chat or group chat.
    - Top Statistics: Displays key statistics including:
        Total messages
        Total words
        Media shared
        Links shared
    - Activity Timeline: Visualizes chat activity with:
        Most busy day
        Most busy month
        Weekly, monthly, and daily activity maps
    - User Analysis:
        Most active users
    - Text Analysis:
        Most common words
        Emoji analysis
        Sentiment analysis

Libraries Used :

    - nltk for natural language processing
    - wordcloud for generating word clouds
    - urlextract for extracting URLs
    - emoji for analyzing emojis
    - streamlit for creating the web application
    - numpy for numerical operations
    - pandas for data manipulation
    - matplotlib and seaborn for data visualization

Installation

    1. Clone the repository:

git clone https://github.com/yourusername/whatsapp-chat-analyser.git

2. Navigate to the project directory:

cd whatsapp-chat-analyser

3. Install the required libraries:

    pip install -r requirements.txt

Usage

    1. Run the Streamlit application:

    streamlit run app.py

    2. Open the application in your web browser (typically at http://localhost:8501).

    3. Upload your WhatsApp chat file.

    4. Choose the type of analysis (individual or group).

    5. Click on the "Show Analysis" button to view the results.

Example

Upload a chat file and select the analysis type to see visualizations and statistics such as the total number of messages, activity maps, and sentiment analysis.
Contributing

If you want to contribute to this project, please follow these steps:

    1. Fork the repository.
    2. Create a new branch (git checkout -b feature/your-feature).
    3. Commit your changes (git commit -am 'Add new feature').
    4. Push to the branch (git push origin feature/your-feature).
    5. Create a new Pull Request.
