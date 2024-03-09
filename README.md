## APIs for AI Model Interaction

This repository contains scripts and examples for interacting with various AI models through APIs. Below are explanations of the different APIs and their functionalities:

### 1. Hugging Face API

**Description**:
- The Hugging Face API allows access to a range of open-source models.
- We can query models like "Mistral-7B" to generate text based on input prompts.

**Usage**:
- The script sets up the API URL and headers with an API token.
- It demonstrates sending a question prompt to the "Mistral-7B" model and receiving a response, such as information about the capital of India.

### 2. OpenAI GPT API

**Description**:
- The OpenAI GPT API provides access to advanced language models.
- Here, we use the OpenAI Python package to interact with the GPT-3.5 model.

**Usage**:
- The script initializes the OpenAI client with an API key.
- It showcases generating responses to user prompts, like composing a poem or creating a thumbnail for a YouTube video.

### 3. Google GenerativeAI (Gemini) API

**Description**:
- The Google GenerativeAI API (Gemini) offers models for text and image generation.
- We utilize the "gemini-1.0-pro" model for text generation and "gemini-1.0-pro-vision-latest" for image generation.

**Usage**:
- The script configures the API key and demonstrates using the "gemini-1.0-pro" model to generate detailed text responses, such as providing the history of the capital of India.
- It also shows how to generate content for images using the "gemini-1.0-pro-vision-latest" model, creating creative thumbnails based on input prompts.

### How to Use

1. **Getting Started**:
   - Ensure the necessary API tokens (`HUGGINGFACE_API_KEY`, `OPENAI_API_KEY`, `GOOGLE_API_KEY`) are stored securely.
   
2. **API Integration**:
   - The scripts demonstrate how to set up API calls with authentication tokens.
   - Each API interaction is showcased with a specific model and example prompt.

3. **Model Interaction**:
   - Users can refer to these examples to understand how to query models for text or image generation.
   - Explore different AI models' capabilities by modifying input prompts and models.

### Note:
- These scripts are illustrative examples and require valid API keys and configurations to run.
- Make sure to have the necessary permissions and understanding of rate limits for each API.
- Detailed documentation for each API and model can be found in their respective official documentation.
