README
==============================================================================
## Leveraging VGG To Create Art With Blended Styles ##
COMSW4995: Applied Deep Learning - Final Project  

Dani Dassum  
dd3007@columbia.edu  

==============================================================================

This project demonstrates how to use a neural style transfer model to blend multiple artistic styles and apply them to a content image. Inspired by the work of Gatys et al. (2015), this implementation utilizes VGG-19 for feature extraction and introduces a method to combine two artistic styles by assigning weights to each. The result is a unique hybrid visual that preserves the structure of the content image while blending multiple styles harmoniously.

==============================================================================

## How It Works ##

The notebook:  
- Loads a content image and style images (sample input images are included).  
- Extracts features from these images using a pre-trained VGG-19 model.  
- Combines two styles using weight balancing (you can try different values as long as they sum up to 1).  
- Outputs images showing single-style and blended-style transfers.  

## Running the Notebook ##

1. Clone the repository or download the notebook file, using:

git clone https://github.com/dd3007/adl-final-paper.git

3. Open the notebook in your preferred environment (e.g., Jupyter Notebook or Google Colab).  
4. Run the cells step by step:  
   - An installation block is included to install all necessary packages (`torch`, `torchvision`, `matplotlib`, etc.).  
5. Use the provided content and style images or upload your own artistic styles and content images to experiment.  
6. Adjust the style blending weights in the notebook to explore different combinations.  

## Experimentation ##

Feel free to try:  
- **Different artistic styles**: Upload your own style images to see how they blend with the content image.  
- **Weight balancing**: Experiment with different weights (e.g., `0.3, 0.7`, or `0.6, 0.4`) to influence the contribution of each style.  

## References ##

- Original implementation inspired by [Gatys et al. (2015)](https://arxiv.org/abs/1508.06576).  
- This notebook builds upon ideas and techniques from [this GitHub repository](https://github.com/tjwhitaker/a-neural-algorithm-of-artistic-style/tree/master).  

## Notes ##

- Sample input images are included in the repository, but you are encouraged to upload your own images to fully explore the potential of this model.  
- Outputs will vary based on style image choices, blending weights, and artistic preferences. Experiment to discover unique results!  
