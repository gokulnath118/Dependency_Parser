# Dependency Parser

The code for a straightforward Python dependency parser that makes use of SpaCy is available in this repository. Users can input words into the parser, which then uses SpaCy's dependency parser to parse them and view the dependency trees that are parsed.

## Features

- Use the dependency parser provided by SpaCy to parse phrases.
- Visualize the parsed dependency trees.

## Requirements

- Python 3
- django
- Create a virtual environment using Python-django and install the requirements.txt file using the command pip install -r requirements.txt

## Procedure to run the program

1. Clone the repository:

    ```Terminal
    git clone https://github.com/gokulnath118/Dependency_Parser.git

2. Create a Virtual Environment:

    ```Terminal
    python -m venv <venv_name>

3. Activate the Virtual Environment
    ```Terminal
    <venv_name>\Scripts\activate

4. Install the packages using requirements.txt:

    ```Terminal
    pip install -r requirements.txt

5. Run the streamlit app locally:

    ```Terminal
    streamlit run app.py

6. get the app:

    Access the app in your web browser at `http://localhost:8501`.

