## Overview
This project demonstrates how to fine-tune and deploy a T5 model from Hugging Face for translation and summarization tasks. The trained model is integrated into a web application that allows users to input text and receive translations or summaries or translation of summaries directly from a user-friendly interface.

## Features
- Fine-tuned T5 model for translation and summarization.
- Interactive webpage for user input and result display.
- Backend powered by Flask for handling requests and model inference.
- Frontend designed with HTML and styled with CSS.
- JavaScript for seamless interaction between the user interface and the server.

### Frontend
- **HTML**: Used to create the user interface, including input forms for text and output display areas.
- **CSS**: Styled the HTML components to create a clean and responsive design.
- **JavaScript**: Established communication between the client-side UI and the Flask backend through AJAX requests.

### Backend
- **Flask**: Handles HTTP requests and processes user inputs by interacting with the T5 model for translation and summarization.
- **Python**: Used for loading the fine-tuned T5 model and performing inference.

## Usage
1. Enter text in the input field on the webpage.
2. Select the desired operation: Translation or Summarization or Translation of Summarization.
3. Click the submit button to send the request.
## Acknowledgments
- Hugging Face for providing the T5 model and Transformers library.
- Flask documentation and community for backend development support.
- Open-source CSS and JavaScript resources used for UI/UX design.

