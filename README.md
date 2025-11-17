# Cats vs Dogs Binary Classifier (MobileNetV2 transfer learning)

## Quick setup
1. Install dependencies:
   pip install -r requirements.txt
2. Prepare dataset:
   - Option A: Use TensorFlow Datasets `cats_vs_dogs` (automatically downloaded in notebook).
   - Option B: Download Kaggle "Dogs vs Cats" dataset and unzip into `data/train`.
3. Run `notebook.ipynb` in Colab or Jupyter. See cells for instructions to copy 5 images into `inference_images/` for inference.

## Running in Colab
- Upload notebook, run cells. GPU recommended.

## Files
- notebook.ipynb
- requirements.txt
- Dockerfile
- final_model.h5 (or instructions to reproduce training)

Dataset link:
- Kaggle Dogs vs Cats: https://www.kaggle.com/c/dogs-vs-cats
- TensorFlow Datasets: `tfds.load('cats_vs_dogs')`

Project requirements reference: see uploaded spec. :contentReference[oaicite:2]{index=2}
