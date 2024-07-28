# Image-Classification
COVID 19 CT LUNG &amp; INFECTION DETECTION

Image Preprocessing: The code uses the ImageDataGenerator from Keras for image preprocessing tasks such as rescaling, shear, zoom, and flip transformations.

Dataset Management: Functions like define_paths, define_df, and split_data handle the organization and splitting of the dataset into training, validation, and test sets.

Image Classification: trains a Convolutional Neural Network (CNN) model for classifying images. It includes defining the model, using data generators for feeding data into the model, and fitting the model using training data.

Model Evaluation: includes evaluation of the trained model on the test dataset, providing accuracy metrics.
