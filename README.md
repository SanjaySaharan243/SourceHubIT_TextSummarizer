### Text Summarizer (Using Transformers)

This project is a Text Summarization Web App built using Hugging Face Transformers and Gradio.
It allows users to input a long piece of text, and the app will automatically generate a concise summary using a pre-trained NLP model.

## Features

Accepts any long text as input.

Uses Hugging Face pre-trained summarization models (like facebook/bart-large-cnn).

Runs on TensorFlow backend for efficient deep learning computations.

Provides an interactive web UI using Gradio.

No need for manual training or dataset preparation — ready to use out of the box!

## How It Works

User Input:
You type or paste a long paragraph into the text box.

Model Processing:

The app uses Hugging Face’s pipeline("summarization") to load a pre-trained summarization model.

This model processes the text and generates a condensed version while preserving the meaning.

Output:
The summary is displayed in a separate text box on the Gradio interface.


## Libraries Used

Transformers: Provides the summarization model & tokenizer.

TensorFlow: Backend for deep learning model computations.

Gradio: Creates an interactive UI for easy user interaction.

## Result 

<img width="1467" height="723" alt="Screenshot 2025-09-17 at 3 27 39 PM" src="https://github.com/user-attachments/assets/7218ccdb-fdfb-485a-8811-61fe7870c025" />

<img width="1470" height="747" alt="Screenshot 2025-09-17 at 3 27 57 PM" src="https://github.com/user-attachments/assets/70f6d514-a57b-4f93-bd32-a755bc0e8fc5" />

<img width="1469" height="729" alt="Screenshot 2025-09-17 at 3 29 35 PM" src="https://github.com/user-attachments/assets/1f2ab580-3e29-40be-9e31-e162070a433e" />

<img width="1470" height="743" alt="Screenshot 2025-09-17 at 3 31 38 PM" src="https://github.com/user-attachments/assets/5e8426fe-41be-41b3-9e32-e6b0ba863347" />
