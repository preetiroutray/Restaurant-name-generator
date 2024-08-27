# Restaurant Name Generator

Restaurant Name Generator is a data-driven tool that leverages **LangChain** and the **Gemini API** to generate unique and creative restaurant names. The tool analyzes patterns in restaurant naming conventions and uses these insights to suggest innovative and relevant names. Designed with a user-friendly interface built in **Streamlit**, this tool is perfect for data scientists, business owners, and marketers looking to explore naming trends or brainstorm new ideas.

## Features

- **Data-Driven Name Generation:** Utilizes LangChain's integration with the Gemini API to analyze data and generate creative restaurant names based on specific keywords or themes.
- **Streamlit Interface:** Offers an intuitive, easy-to-use interface for entering keywords and viewing generated names.
- **Data Science Application:** Analyzes patterns and trends in existing restaurant names to inspire new ideas.
- **Customizable Inputs:** Allows users to input specific keywords, themes, or cuisines to tailor the name generation process.

## Files in the Repository

- **`api_key.py`:** Stores the Gemini API key required for accessing the name generation service.
- **`langchain_helper.py`:** Contains helper functions to interact with LangChain and process the data for name generation.
- **`main.py`:** The main Streamlit app that ties everything together, providing the user interface and calling the necessary functions to generate restaurant names.
- **`ss_of_working.jpg`:** Screenshot of the working Streamlit app, showcasing the generated restaurant names.

## Example Usage

1. Input a keyword or theme, such as "Italian" or "Sushi."
2. The tool processes this input using LangChain and generates several creative restaurant names.
3. View the results in the Streamlit interface, and iterate with different keywords to explore more options.
