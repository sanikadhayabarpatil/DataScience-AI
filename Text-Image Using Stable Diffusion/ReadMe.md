# Text-to-Image Generation with Stable Diffusion

## Project Overview
This project implements **text-to-image generation** using **Stable Diffusion** via **Keras CV**. It allows users to generate high-quality **AI-generated images** based on text prompts.

## Features
- **Stable Diffusion Model**: Uses **Keras CV's pre-trained Stable Diffusion model**.
- **High-Resolution Outputs**: Generates **512x512 pixel images**.
- **Batch Processing**: Supports multiple image generations in a single request.
- **Visualization**: Displays generated images using **Matplotlib**.

## Installation
Ensure you have the required dependencies installed before running the notebook:

```bash
pip install tensorflow keras_cv matplotlib
```

## How to Run
1. Clone this repository and navigate to the project folder:
    ```bash
    git clone <repository_url>
    cd <project_folder>
    ```
2. Open the Jupyter Notebook and run the cells sequentially:
    ```bash
    jupyter notebook TextToImage_StableDiffusion.ipynb
    ```

## Implementation Details
- **Text Prompt Input**: Users can enter a description to generate an image.
- **Batch Processing**: Generates multiple images simultaneously (`batch_size=3`).
- **Visualization**: Uses **Matplotlib** to display generated images.

## Example Usage
```python
import keras_cv
from tensorflow import keras
import matplotlib.pyplot as plt

model = keras_cv.models.StableDiffusion(img_width=512, img_height=512)
images = model.text_to_image("Huskies on the roof of a building, dancing tango", batch_size=3)

# Plot images
def plot_images(images):
    plt.figure(figsize=(20, 20))
    for i in range(len(images)):
        ax = plt.subplot(1, len(images), i + 1)
        plt.imshow(images[i])
        plt.axis("off")

plot_images(images)
```

## Results
The generated images showcase the power of **Stable Diffusion** for realistic and creative image synthesis based on **natural language descriptions**.

## Author
- **Sanika Dhayabar Patil**
