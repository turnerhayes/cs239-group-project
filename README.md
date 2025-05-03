# CS239 Group Final Project

Authors: Turner Hayes, Adrien Amblard, Xamier Ferran

Spring 2025

*Motivation:* AI image generators are being used to generate images equivalent to an input image but in another style (e.g. Disney, Simpsons, Studio Ghibli…). But, they don’t always capture everything important in the input image, even beyond any changes that come from the shift in style. How do we quantify the loss of information from this generation?

*Project Overview:* This project investigates how artistic restyling of generative AI alters the original image content, particularly in human-centered contexts. Ten images across five categories were restyled in the styles of Studio Ghibli and The Simpsons using ChatGPT, and compared to the originals using KL divergence, a CNN-based cosine similarity, and GPT-4 as a judging LLM. The study explores both the creative possibilities and ethical concerns of AI-generated image transformations.

## Running the code

The code is a Jupyter notebook, written in [Google Colab](https://colab.research.google.com/drive/1o0WpdaJCBYEB85jYOoJFTfVTzlL6UVOe?usp=sharing). To run it, you can import it into Google Colab. Note that it requires an OpenAI API key stored as a notebook secret under the key `OPENAI_KEY`.

The images are available in [this](https://drive.google.com/drive/folders/18bPXGChRSfrppotXZ1wL-yeueQQ6sOgF?usp=sharing) Google Drive (should be accessible within the Tufts organization). To allow the script to find the images, put them in your drive under the path `colab_data/cs239/styled_images`.
