# Multimodal-Calorie-Predictor

Tech Stack used - Python, PyTorch, Transformer
## Project Summary
•	Built a multimodal deep learning model to predict calorie intake using three data types: time-series CGM data, meal images (breakfast and lunch), and patient demographic and gut microbiome data.
•	Preprocessed each modality independently and designed three parallel networks: a Transformer encoder for CGM data, CNN for meal images, and a deep neural network for demographic and PCA-reduced gut features.
•	Fused outputs through dense layers to generate final predictions, achieving an RMSRE of 0.3374.
