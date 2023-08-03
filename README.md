# Reverse Image Search - GitHub Repository

Welcome to the Reverse Image Search GitHub repository! This project allows you to perform reverse image search using a pre-trained ResNet50 model and Nearest Neighbors algorithm. It helps you find similar images to the one you upload.

## Description

This project is built with Python using Streamlit, Tensorflow, PIL, NumPy, and Scikit-learn libraries. It utilizes the power of deep learning for feature extraction and then leverages the Nearest Neighbors algorithm to find similar images based on the extracted features.

## Requirements

Before running the code, please ensure you have the following dependencies installed:

* streamlit
* PIL (Python Imaging Library)
* numpy
* pickle
* tensorflow
* scikit-learn
  
### You can install these requirements using pip:

* pip install streamlit pillow numpy scikit-learn tensorflow

## How to Run

### Clone the repository to your local machine:

git clone <repository_url>
cd <repository_name>

Make sure you have the necessary image data and embeddings files:

* Place the image files you want to search in the "uploads" folder.
* Ensure you have the "embeddings.pkl" file containing the pre-extracted embeddings.
* Make sure you have the "filenames.pkl" file containing the corresponding filenames for the embeddings.
  
Execute the Streamlit app:

* streamlit run app.py
  
Access the app in your browser by following the URL shown in the terminal.

## How it Works

1 When you run the app, it will prompt you to upload an image.

2 After you upload the image, it will display the uploaded image and extract its features using the pre-trained ResNet50 model.

3 The app will then use the Nearest Neighbors algorithm to find the top 5 images in the dataset that are most similar to the uploaded image based on the extracted features.

4 The app will display the top 5 similar images next to the uploaded image.

## Note

* Please ensure that the "uploads" folder is writable so that the app can save the uploaded images temporarily for processing.
  
## Disclaimer

This project is provided as-is and may not be suitable for production environments. Use it responsibly and at your own risk.

## Acknowledgments

This project uses the power of deep learning and open-source libraries to demonstrate the concept of reverse image search. Special thanks to the developers of Streamlit, Tensorflow, PIL, NumPy, and Scikit-learn for their contributions to the open-source community.

If you find this project useful or have any suggestions for improvement, feel free to contribute or leave feedback.

Happy image searching! 
