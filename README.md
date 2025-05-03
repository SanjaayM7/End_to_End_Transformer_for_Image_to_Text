# 🧠 Multimodal AI Playgorund

This repository contains a **Multimodal AI Application** built with **Gradio**, **Hugging Face Transformers**, and **Cohere**. It provides an intuitive interface for exploring a variety of AI capabilities including natural language generation, image synthesis, audio transcription, and computer vision tasks.

## ✨ Features

- **Text Generation**  
  Generate creative text based on user prompts using **Cohere's language model**.

- **Image Generation**  
  Create visually stunning images from text descriptions using **Stable Diffusion XL**.

- **Speech-to-Text**  
  Transcribe audio files into text using **OpenAI’s Whisper** model.

- **Object Detection**  
  Identify and label objects in images with **YOLOS**.

- **Image Captioning**  
  Automatically generate descriptive captions for images using **BLIP**.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone [https://github.com/your-username/your-repository-name.git]
cd your-repository-name
```

### 2. Install Dependencies

Install the required Python packages:

```bash
pip install gradio transformers cohere torch torchvision pydub ffmpeg-python
```

Install system dependencies:

```bash
apt-get install ffmpeg
```

For image generation support (Stable Diffusion XL):

```bash
pip install torch torchvision diffusers transformers accelerate gradio
```

### 3. Set Up API Keys

Obtain your API keys for:

- [Hugging Face](https://huggingface.co/)
- [Cohere](https://cohere.ai/)

Create a file named `api_keys.py` and add the following:

```python
HF_TOKEN = "YOUR_HUGGING_FACE_TOKEN"
COHERE_API_KEY = "YOUR_COHERE_API_KEY"
```

### 4. Run the App

```bash
python app.py
```

---
