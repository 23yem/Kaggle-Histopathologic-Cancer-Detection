# Histopathologic Cancer Detection Project

---

<img src="https://miro.medium.com/v2/resize:fit:820/1*8hKi49y9Nw6Xsi6b2M-z6g.png" style="max-width: 1242px; width: 617px; height: 487px; margin: 0px;" alt="Histopathologic Cancer Detection">

## Introduction
This is my second Machine Learning Project. Welcome to the Histopathologic Cancer Detection project repository.  This project is based on a Kaggle competition with the goal of developing an image classification algorithm using Convolutional Neural Networks (CNNs) to identify metastatic tissue in histopathologic scans of lymph node sections.

## Project Description
The primary challenge in this competition is to create a model that can accurately classify microscopic images of lymph node sections as containing metastatic tissue or not. This repository includes the code for building and training a CNN to tackle this problem. The model is developed in Python using TensorFlow and Keras.


## Portfolio Website with my BEST Deployed Models in the cloud
I also made a [custom interactive website for this project](https://michael-ye-histopathologic-cancer-detection-home.streamlit.app/), which describes the project, my techniques, and most importantly, I deployed my best models and allowed users to pass in images which are given to the model in the cloud and gives back predictions of the image having cancer or not. Try it out at https://michael-ye-histopathologic-cancer-detection-home.streamlit.app/


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

