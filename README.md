# GENERATIVE-TEXT-MODEL
**Company**: CODTECH IT SOLUTIONS PVT.LTD

**Name**: Ankur Datta

**Intern ID**: CT08JSJ

**Domain**: Artificial Intelligence

**Batch Duration**: January 5th, 2025 to February 5th, 2025

**Mentor Name**: Neela Santhosh 

# Text Generation with GPT

This project demonstrates how to use a pre-trained GPT model from Hugging Face's Transformers library to generate coherent paragraphs of text based on user prompts. The notebook is designed to guide users through loading a GPT model, defining a text generation function, and generating text on various topics.

## Features

- **Pre-trained GPT Model**: Utilizes OpenAI's GPT-2, a powerful language model capable of generating human-like text.
- **Customizable Parameters**: Adjust text generation parameters such as:
  - **`max_length`**: Limit the length of the generated text.
  - **`temperature`**: Control randomness in text generation.
  - **`top_k`**: Enable top-k sampling for more focused outputs.
- **Easy-to-Use Interface**: The notebook is structured for beginners and experienced users alike, providing clear instructions and examples.

## Project Highlights

1. **Libraries Used**: 
   - `transformers`: For model and tokenizer loading.
   - `torch`: For tensor operations and model execution.

2. **Core Functionality**:
   - Encode user prompts into input tokens.
   - Generate text using the GPT model with configurable parameters.
   - Decode and display the generated text.

3. **Interactive Example**:
   - Input prompt: `"Artificial intelligence is transforming the world by"`
   - Output: A continuation of the input prompt in a coherent paragraph.

## Requirements

- Python 3.8 or later
- Libraries:
  - `transformers`
  - `torch`

## Usage

1. **Install Dependencies**:
   ```
   pip install transformers torch
   ```

2. **Run the Notebook**:
   - Open `Text_Generation_with_GPT.ipynb` in Jupyter Notebook.
   - Follow the instructions to load the model and generate text.

3. **Customize Text Generation**:
   - Modify the input prompt and parameters in the `generate_text` function to explore different outputs.

## Example Output

**Prompt**:  
`"The future of technology lies in"`

**Generated Text**:  
`"The future of technology lies in the seamless integration of artificial intelligence, robotics, and advanced data analytics to revolutionize industries, improve lives, and drive global progress."`
