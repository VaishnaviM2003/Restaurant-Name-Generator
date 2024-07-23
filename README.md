# Restaurant-Name-Generator
A web application using Python, LangChain, and Cohere to generate creative restaurant names and menu items based on selected cuisine types. Implemented a user-friendly interface with Streamlit, enabling users to explore various cuisine options and receive tailored restaurant names and menu suggestions.

## Features

- `Cuisine-Based Restaurant Naming:` Suggests a unique and fancy name for a restaurant based on the selected cuisine type.
- `Menu Item Generation:` Provides a list of menu items tailored to the generated restaurant name.
- `Streamlit Interface:` An interactive web app that allows users to select a cuisine type and view generated results.

## Technologies Used
- `LangChain:` A framework for creating language models with chains and prompts.
- `Cohere:` A language model API used to generate text.
- `Streamlit:` A framework for building interactive web applications with Python.

## Getting Started
### Prerequisites
Ensure you have the following installed:

- Python 3.x
- pip (Python package installer)
  
### Installation
1. Clone the Repository
   
   `git clone https://github.com/VaishnaviM2003/Restaurant-Name-Generator.git`
   
   `cd Restaurant-Name-Generator`

3. Install Dependencies
   
   `python -m venv env`
   
   `source env/scripts/activate`
   
   `pip install -r requirements.txt`

5. Add Your Cohere API Key
   Update secret_key.py with your Cohere API key:
   `cohereapi_key = "your-cohere-api-key"`

### Usage
1. Run the Streamlit App
   
   `streamlit run main.py`

3. Interact with the Application
   Open the provided URL in your web browser. Use the sidebar to select a cuisine type. The app will display a suggested restaurant name and a list of menu items.

## File Descriptions
- `langchain_helper.py:` Contains functions for generating restaurant names and menu items using LangChain and Cohere.
- `llm.py:` Defines the language model instance and the function for generating restaurant names and menu items. (This file is similar to langchain_helper.py but with hardcoded API key.)
- `main.py:` The Streamlit application script that provides the user interface.
- `secret_key.py:` Stores the API key for Cohere.

## Ouput

![Screenshot (291)](https://github.com/user-attachments/assets/19c1dde4-abcf-4165-b7ae-0c6f0e5c1926)

