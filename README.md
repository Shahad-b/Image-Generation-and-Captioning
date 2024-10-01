# Image Generation and Captioning Project 🌐

## Overview ✨

This project leverages state-of-the-art models from Hugging Face and Gradio to build an application that performs three key tasks:

1. **Image Captioning**: Automatically generating captions for uploaded images🖼️.
2. **Image Generation**: Creating new images based on the generated captions
3. **Caption Translation**: Translating the English captions into Arabic🌍.

The project aims to enhance creativity by using deep learning models to provide a seamless workflow for image captioning, generation, and translation, with a special focus on supporting the Arabic language.

## Expected Outputs 📊

- When an image is uploaded, the application generates a caption for the image 📝.
- The English caption is then translated into Arabic.
- New images are generated based on the English caption using the Stable Diffusion model.
- The user can select the number of images to generate, and the outputs include the generated images, the English caption, and the translated Arabic caption📸.

## Model Choices with Links to Hugging Face Models 🔗

### Image Captioning Model:
- **Model Used**: [Salesforce/blip-image-captioning-large](https://huggingface.co/Salesforce/blip-image-captioning-large)
- **Justification**: This model is designed for high-quality image captioning, providing detailed and contextually rich descriptions based on the visual content of images.

### Image Generation Model:
- **Model Used**: [runwayml/stable-diffusion-v1-5](https://huggingface.co/runwayml/stable-diffusion-v1-5)
- **Justification**: Stable Diffusion is a leading model for generating high-quality images from textual prompts, making it ideal for creating images based on the captions generated.

### Translation Model:
- **Model Used**: [facebook/nllb-200-distilled-600M](https://huggingface.co/facebook/nllb-200-distilled-600M)
- **Justification**: This model supports translation from English to Arabic and is designed to handle various languages effectively, ensuring accurate and fluent translations.

## Pipeline Explanation 🔄

1. **Image Upload**: Users upload an image via the Gradio interface📤.
2. **Caption Generation**: The image is processed through the image captioning model to generate an caption💬.
3. **Translation**: The generated caption is then translated into Arabic using the translation model🔄.
4. **Image Generation**: The English caption serves as a prompt for the Stable Diffusion model to create new images.
5. **Output Display**: The application displays the generated images along with the captions in both English and Arabic📺.

## Conclusion 🌟

This project combines advanced machine learning techniques to facilitate image captioning, translation, and image generation. It aims to provide an intuitive interface for users to interact with these technologies, promoting accessibility and creativity in the realm of visual content. 

**Access the Project**: 
- Click on the following link to access the running Gradio interface: [Access the Project](https://huggingface.co/spaces/shahad-b/Image_Generation_and_Captioning)
- Click on the following link to access the code with examples : [Access the Code](https://colab.research.google.com/drive/1UelrETyxr2OtHyMlcY_qaedILr0imh_k#scrollTo=FZcf8yMGk6fs)

## 🎥 Explainer Video

You can view the video here: [Project Video](https://drive.google.com/file/d/1-In2QtjtPRVksFkC-0r78vLc-Z3P3hi_/view?usp=drivesdk)
     
