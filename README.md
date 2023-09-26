# Question Answering Mini Project

This mini project demonstrates how to create a Question Answering (QA) model using pre-trained models like BERT, RoBERTa, DistilBERT, and DistilRoBERTa. The objective is to understand the process of building QA models and to evaluate their performance.

## Project Overview

The main focus of this project is to implement a QA system using the Simple Transformers library. The code is contained in the `Custome_QuestionAnswering.ipynb` notebook. The following steps were taken:

1. **Data Preparation**:
   - The project utilizes data stored in the `files` folder, which includes train, test, and prediction JSON files.

2. **Model Training**:
   - The `QuestionAnsweringModel` class and `QuestionAnsweringArgs` class from Simple Transformers were employed to train the QA model. The notebook provides details about the arguments used for training.

3. **Training Iterations**:
   - The model was trained for an initial 5 epochs, followed by a subsequent run with 20 epochs. The accuracy and loss metrics were recorded and evaluated.

## Usage

1. **Notebook**:
   - The main code for training the QA model can be found in the `Custome_QuestionAnswering.ipynb` notebook.

2. **Data Files**:
   - The `files` folder contains the necessary data files (train, test, and prediction JSON files) for training and evaluating the model.

3. **Optimizer**:
   - The trained optimizer state is saved in the `optimizer.pt` file.

## Customization for Specific Domains

This project serves as a foundation for creating specialized QA models tailored to specific domains. For instance, to build a QA model for a hospital's historical data over the past 20 years, the following steps can be taken:

1. **Data Collection**:
   - Gather comprehensive historical data from the hospital, covering various aspects and events.

2. **Data Preprocessing**:
   - Prepare the collected data for training the QA model. This may involve tasks such as cleaning, structuring, and formatting the data.

3. **Model Selection**:
   - Choose the most appropriate pre-trained model (e.g., BERT, RoBERTa, etc.) based on the nature of the hospital's data.

4. **Training**:
   - Utilize the provided code and adapt it to train the QA model on the hospital's specific dataset.

5. **Evaluation**:
   - Assess the model's performance and fine-tune as necessary to achieve the desired level of accuracy.

## Dependencies

The project relies on the following libraries and packages:

- [Python 3.x](https://www.python.org/downloads/)
- [Simple Transformers](https://github.com/ThilinaRajapakse/simpletransformers)

## How to Run

1. Ensure that Python and the required libraries are installed.
2. Open and run the `Custome_QuestionAnswering.ipynb` notebook.

## Additional Notes

- For any further questions or assistance, please contact [Muhammed Thahseer] at [zacthahseer123@gmail.com].

Enjoy exploring the world of Question Answering models!
