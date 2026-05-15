# Gen AI Image Caption Generator

An AI-powered web app that generates descriptive captions for uploaded images using the BLIP model with Hugging Face Transformers and Gradio.

## Features
- Upload an image and get an AI-generated caption
- Simple and interactive web UI
- Powered by a pre-trained vision-language model
- Lightweight and beginner-friendly project

## Tech Stack
- Python
- Gradio
- Hugging Face Transformers
- BLIP
- PyTorch
- Pillow

## Model Used
- `Salesforce/blip-image-captioning-base`

## How It Works
1. User uploads an image.
2. The image is processed using the BLIP processor.
3. The model generates a caption.
4. The caption is displayed in the UI.

## Installation
```bash
pip install gradio numpy pandas pillow tensorflow torch torchvision transformers
```

## Run the App
```bash
python app.py
```

## Future Improvements
- Add multi-caption support
- Improve caption quality with fine-tuned models
- Add image analysis and object detection
- Deploy on a cloud platform













