
LIVE IN: https://09cf85aa05a949d1cd.gradio.live

# Image Captioning with Vision Encoder-Decoder Model
An interactive Gradio application that generates captions for images using a pre-trained Vision Encoder-Decoder model (ViT-GPT2).

## Features

- 🖼️ Generate captions for uploaded images or image URLs
- ⚡ Optimized for both CPU and GPU (automatically detects available hardware)
- ⚙️ Adjustable generation parameters (max length, number of beams)
- 🌐 Works with local images and web URLs

## Technical Details

**Model Architecture**:  
- **Encoder**: Vision Transformer (ViT)
- **Decoder**: GPT-2 language model

**Pretrained Model**: (https://huggingface.co/nlpconnect/vit-gpt2-image-captioning)

## Installation



git clone https://github.com/yourusername/image-captioning-app.git
cd image-captioning-app



The application will launch a local web interface accessible at http://127.0.0.1:7860


How to Use

Upload an image or paste an image URL
Adjust generation parameters if needed (in Advanced Settings)
View the generated caption
Try different images to see various results

