# CS239 Group Final Project

Authors: Turner Hayes, Adrien Amblard, Xamier Ferran

Spring 2025

*Motivation:* AI image generators are being used to generate images equivalent to an input image but in another style (e.g. Disney, Simpsons, Studio Ghibli…). But, they don’t always capture everything important in the input image, even beyond any changes that come from the shift in style. How do we quantify the loss of information from this generation?

## Running the code

The code is a Jupyter notebook, written in [Google Colab](https://colab.research.google.com/drive/1o0WpdaJCBYEB85jYOoJFTfVTzlL6UVOe?usp=sharing). To run it, you can import it into Google Colab. Note that it requires an OpenAI API key stored as a notebook secret under the key `OPENAI_KEY`.

The images are available in [this](https://drive.google.com/drive/folders/18bPXGChRSfrppotXZ1wL-yeueQQ6sOgF?usp=sharing) Google Drive (should be accessible within the Tufts organization). To allow the script to find the images, put them in your drive under the path `colab_data/cs239/styled_images`.
