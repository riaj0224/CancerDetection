# Histopathologic Cancer Detection

:computer: Image Classification: Detecting Cancer Metastases on Pathology Images

This repository is dedicated to a project revolving around the early detection of metastatic tissue in histopathologic scans of lymph node sections. This is paramount for cancer prognosis and the determination of treatment methods.

## :wrench: Overview

The project encompasses the following steps:

1. :computer: **Data Preprocessing**: Cleaning and preprocessing the dataset for optimal performance in the subsequent modeling steps.
2. :computer: **Data Augmentation**: Leveraging techniques to synthetically enlarge the dataset, ensuring a robust model training.
3. :computer: **Model Building**: Setting up different model architectures, including a basic CNN model and a model inspired by the MNIST dataset.
4. :computer: **Hyperparameter Tuning**: Using techniques like KerasTuner to find the most optimal hyperparameters for our models.
5. :computer: **Model Evaluation**: Analyzing performance metrics, and drawing conclusions from the trained models.
6. :computer: **Predictions**: Using the best-performing model to make predictions on test data.

## :gear: Technologies Used

This project utilizes the following technologies:

- Python
- TensorFlow/Keras
- KerasTuner

These tools and libraries are essential for data processing, model training, and evaluation.

## :rocket: Getting Started

To execute the project on your local machine:

1. Ensure all dependencies are installed using `pip install -r requirements.txt`.
2. Run the Jupyter notebook to walk through the data processing, model training, and prediction stages.

## :file_folder: Project Structure

The projected is structured as follows:
├── train
│ ├── images
│ └── labels
├── test
│ └── images
├── models
│ ├── basic_cnn
│ ├── MNIST_inspired
│ └── advanced_model
├── tuning_results.csv
└── README.md


- `train/images`: Directory with training images.
- `train/labels`: Associated labels for the training images.
- `test/images`: Directory with test images.
- `models`: Contains saved models from the project.
- `tuning_results.csv`: Results from hyperparameter tuning phase.

## :chart_with_upwards_trend: Results and Evaluation

The trained models and their evaluations are available within the Jupyter notebook. The most advanced model reached an accuracy of ~91.13% on the validation set, showcasing its potential in the medical imaging field.

## :raising_hand: Acknowledgements

A shoutout to the Kaggle community for providing such a rich dataset and for fostering a competitive environment that drives innovation. This particular dataset and competition were invaluable resources for this project.

## :page_facing_up: License

This endeavor is protected under the MIT License. This grants the liberty to use, adapt, and distribute the content for both academic and commercial applications.

## :email: Contact

For additional details or inquiries, feel free to drop an email at jair2000.0224@hotmail.com.
