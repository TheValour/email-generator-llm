# Email Draft Generator  ✉️

## Overview ➡️
This project is a web application built with Streamlit for generating email drafts using a language model called Llama-2-7B-Chat-GGML. Users can input details such as the email topic, sender name, recipient name, and select a writing style, and the application generates an email draft based on these inputs.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/TheValour/email-draft-generator.git
    ```

2. Navigate to the project directory:
    ```bash
    cd email-draft-generator
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Run the Streamlit application:
    ```bash
    streamlit run app.py
    ```

2. Access the application in your web browser at the provided URL.

3. Enter the email topic, sender name, recipient name, and select a writing style from the dropdown menu.

4. Click the "Generate" button to generate the email draft based on the provided inputs.

## Project Structure
- `app.py`: Contains the main code for the Streamlit web application.
- `langchain/`: Directory containing modules for language model prompts and LLMS (Language Model Serving) integration.
  - `prompts.py`: Module for defining prompt templates.
  - `llms.py`: Module for integrating with CTransformers for language model inference.
- `models/`: Directory containing the pre-trained language model file (`llama-2-7b-chat.ggmlv3.q8_0.bin`).

## Dependencies
- Streamlit
- Langchain
- CTransformers

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

