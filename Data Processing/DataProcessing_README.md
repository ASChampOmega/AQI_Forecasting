# Data Processing

Here:
1. Tabular engineering file processes the raw data into a large table. The code from AirDelhi was referenced and heavily adapted here.
2. Deep Engineering file processes the large table into all the different formats as needed, including data imputation. It converts it into a regular dataset and also a extended testing dataset. The IDW model is implemented here for data imputation.
3. Load satellite images has the code to download images. Images are first loaded, then the correct region is screenshotted automatically via Chromium, and then broken into smaller images manually. To ensure higher image quality, the overall area of interest is broken into many large images which are loaded from Esri. Then they are broken into smaller images in python and stored at the desired resolution. This is quite efficient and obtains all 900 satellite images fast
