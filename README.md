# Histopathologic Cancer Detection Project

## Introduction
Welcome to the Histopathologic Cancer Detection project repository. This is my second Machine Learning Project. This project is based on a Kaggle competition with the goal of developing an image classification algorithm using Convolutional Neural Networks (CNNs) to identify metastatic tissue in histopathologic scans of lymph node sections.

## Project Description
The primary challenge in this competition is to create a model that can accurately classify microscopic images of lymph node sections as containing metastatic tissue or not. This repository includes the code for building and training a CNN to tackle this problem. The model is developed in Python using TensorFlow and Keras.

## File Descriptions
- `Cancer-Detection-Neural-Network.ipynb`: The main Jupyter notebook with the CNN model development and training process.
- `labels.csv`: The file containing labels for the image data.
- `model2_saved.h5`: The saved model after training, which can be loaded for inference or further training.
- `README.md`: The file you are currently reading, containing information about this project.
- `sample_submission.csv`: A sample of the format that Kaggle expects for submissions.
- `submission.csv`: The final submission file with predictions made by the trained model.
- `testing_df_labels.csv`: Labels for the testing dataframe.
- `train_labels.csv`: Labels for the training images.
- `training_df_labels.csv`: Labels for the training dataframe.
- `valid_df_labels.csv`: Labels for the validation dataframe.

## Important Directories (Not Included in GitHub)
- `test/`: This directory should contain the test images. It is not included in the GitHub repository due to size constraints but can be found on the [Kaggle competition data page](https://www.kaggle.com/competitions/histopathologic-cancer-detection/data).
- `train/`: This directory should contain the training images and is also available on the Kaggle competition data page.

## Installation
To run the code, you will need the following Python libraries: TensorFlow, Keras, NumPy, and Pandas. These can be installed via pip:

```bash
pip install tensorflow keras numpy pandas
```

## Usage
To use this project, start by cloning the repository and navigating to the directory containing the `Cancer-Detection-Neural-Network.ipynb` notebook. Open the notebook in Jupyter to view and run the cells:

```bash
jupyter notebook Cancer-Detection-Neural-Network.ipynb
```

## Contributing
Contributions to this project are welcome. Please open an issue to discuss proposed changes or enhancements before making a pull request.

## Credits
Thank you to [Kaggle](https://www.kaggle.com/) for hosting the dataset and competition.

## License
This project is open source and available under the [MIT License](LICENSE.md).

