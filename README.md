# Image_similarity
Calculate the similarity score between two product images.

# Files:
**image_similarity.ipynb**: jupyter notebook with project code <br />

** all product images used in the notebook for comparisons are uploaded to the repository.

# Project Description:
This notebook uses three methods to calculate the similarity score between two product images. I compared real vs fake gucci images and real vs real images to try to find 
an image similarity method that calculates a lower similarity score between real vs fake gucci than the real vs real comparison. I tested photos of gucci logos, 
hardware, patterns, and labels.

**Image similarity methods:**<br/>
1. **Histogram-based approach:** captures the distribution of pixel values within the product images and compares the distributions to measure similarity.<br/>
2. **Structural Similarity Index (SSIM) approach:** considers luminance, contrast, and structure in the product images and assigns a score between -1 and 1 (identical).<br/>
3. **CLIP (Contrastive Language-Image Pre-Training) approach:** pre-trained model from openAI. CLIP is a multimodal image classifier that applies the recent advancements in large-scale transformers like GPT-3 to image similarity.<br/>

# Recommendations:
Since I was unsuccessful in finding a method that produces lower scores for real vs fake images than real vs real, I recommend retrying the methods after refining the product images. Test out similarity 
comparisons after removing image background noise and isolating the main object in the photo using OpenCV. 
