T4 GPU, Python 3, load in with map_location='cpu', Dataset: https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset

Forward pass & back-prop through final layer, freezing prior layers (can repeat for 4th layer for more accurate training). Used for plant-disease-classifier. Actual model not included b/c of GitHub's file restrictions 😢 After getting Kaggle API KEY and uploading dataset + updating paths, run on GPU or create subset of data and lower batch size + epoch to run on CPU. Update learning_rate and epoch accordingly.
