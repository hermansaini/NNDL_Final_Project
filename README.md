# NNDL_Final_Project

This project is a deep learning solution for multi-label image classification with novelty detection. The main notebook, `NNDL_Final_Proj.ipynb`, uses a ResNet-50 backbone to classify images into both superclasses and subclasses, and is designed to run efficiently on Google Colab.

## Dataset Setup for Colab
To use this notebook in Google Colab, you must:
- Add the `Released_Data_NNDL_2025` folder as a shortcut to your Google Drive's "My Drive".
- The notebook expects the data at: `/content/drive/MyDrive/Released_Data_NNDL_2025`

## Usage
1. Open `NNDL_Final_Proj.ipynb` in Google Colab.
2. Ensure the dataset folder is correctly linked as described above.
3. Run the notebook cells to train and evaluate the model.

The project includes data loading, training, validation, and test prediction steps, and saves submission files for evaluation.