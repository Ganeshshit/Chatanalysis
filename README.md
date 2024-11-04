# WhatsApp Chat Analysis

This project provides an interactive analysis of WhatsApp chat data, enabling users to gain insights into key metrics and patterns within their chat history. Using data visualization and analytics, the tool presents statistics such as total messages, words, media, and links shared, along with activity maps, sentiment, and emoji analysis.

## Features

- Total message and word counts
- Media and link analysis
- Activity maps and charts
- Sentiment and emoji analysis
- Interactive visualizations

## Prerequisites

The following Python libraries are required to run this project:

- Streamlit
- Matplotlib
- Seaborn
- Urlextract
- Wordcloud
- Pandas
- Emoji

## Installation

### Step 1: Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/Ganeshshit/Chatanalysis.git
cd Chatanalysis
```
### Step 1: Clone the Repository
##### Install the necessary packages using pip. Ensure that you have Python and pip installed.
```bash
pip install -r requirements.txt
```
#### Alternatively, you can install each package individually if requirements.txt is unavailable:
``` bash
pip install streamlit
pip install matplotlib
pip install seaborn
pip install urlextract
pip install wordcloud
pip install pandas
pip install emoji
```
### Step 3: Run the Application
#### Use the following command to start the Streamlit app locally:
 ``` bash
streamlit run app.py
```
##### Once the command is executed, Streamlit will open a new tab in your default web browser displaying the app.

# Usage

- Export your WhatsApp chat history and save it as a .txt file.
- Upload the file in the app to analyze chat patterns, visualize data, and explore insights.
