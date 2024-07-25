This chatbox will provide the information about focusing on your goal and help to manage stress.
Focus on your goals❤️🕊️
A knowledgeable etiquette chatbot powered by Mypdf.

Introduction
This project demonstrates a Retrieval-Augmented Generation (RAG) chatbot using Hugging Face's Inference API, Gradio, and FAISS for efficient similarity search. The chatbot, named "Focus on your goals❤️🕊️" is designed to provide help regarding focusing on your goals and help to manage stress.

Features
Uses the Zephyr-7b-beta model from Hugging Face for natural language processing
Implements RAG to provide context-aware responses
Utilizes FAISS for efficient similarity search in the knowledge base
Provides example prompts to demonstrate the chatbot's capabilities
Offers a user-friendly interface powered by Gradio
Prerequisites
Before you start, make sure you have the following:

Python 3.6 or higher
A Hugging Face account (sign up at huggingface.co)
Installation
Clone this repository:

git clone https://github.com/Gaganjotkaur4368955/Customized-LLM-APP.git

Install the required packages:

pip install -r requirements.txt
Download the PDF of real estate investing and place it in the project directory with the filename Mypdf.pdf.

Usage
To run the chatbot locally:

Open a terminal and navigate to the project directory.
Run the following command:
python app.py
Open your web browser and go to the URL displayed in the terminal (usually http://127.0.0.1:7860).
How It Works
The chatbot loads the PDF of Mypdf and processes it into a vector database.
When a user asks a question, the system searches for relevant passages in the etiquette guide.
The retrieved context is then passed to the LLM along with the user's query.
The LLM generates a response based on the provided context and its training.
Customization
You can customize the chatbot by modifying the following in app.py:

Knowledge base: Replace Mypdf.pdf with another PDF to change the chatbot's knowledge domain.
System message: Edit the system_message variable to adjust the chatbot's behavior and tone.
Model: Change the InferenceClient to use a different model from Hugging Face.
Examples: Modify the examples list to showcase different interactions.
Deployment
This project can be deployed on Hugging Face Spaces:

Fork this repository to your GitHub account.
Go to huggingface.co/spaces and click "Create new Space".
Choose "Gradio" as the SDK.
Link your forked GitHub repository.
Add your Mypdf.pdf file to the Space's files.
Deploy and enjoy your etiquette chatbot!
Disclaimer
This chatbot is based on  stress management and help you with studies  and help to focus on your goals.

Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

Acknowledgements
Hugging Face for providing the Inference API
Gradio for the user interface framework
FAISS for efficient similarity search
Contact
For any questions or feedback, please reach out to ga4368965@alphacollege.me.
