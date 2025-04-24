SDSS MLP Classifier

This project uses data from the Sloan Digital Sky Survey (SDSS) to classify celestial objects into three categories:
- Star
- Galaxy
- QSO (Quasar)

The classification is done using a Multi-Layer Perceptron (MLP) trained on both original and augmented data.

Folder structure:
- SDSS_DR18.csv: Original dataset
- augmented_SDSS.csv: Dataset after augmentation
- wrong_predictions.csv: Outputs where the model failed
- Preprocessing.ipynb: Prepares the dataset (cleaning, scaling, splitting)
- data_augmentation.ipynb: Adds synthetic or modified examples
- Multi-Layer Perceptron.ipynb: Trains the model and evaluates performance

Requirements:
- pandas
- scikit-learn
- matplotlib
- seaborn
- torch

You can install them with:
pip install pandas scikit-learn matplotlib seaborn torch

To run the model, open Multi-Layer Perceptron.ipynb and run all cells.
