# Tunisian-Dialect-Toxicity-Detection-using-Fine_Tuned_Bert
### README for Tunisian-Dialect-Toxicity-Detection-using-BERT

# Tunisian Dialect Toxicity Detection using BERT

This repository contains code for detecting toxicity in Tunisian dialect using a fine-tuned BERT (Bidirectional Encoder Representations from Transformers) model. The project involves data preprocessing, model training, and deploying the model using a Gradio interface.

## Table of Contents

- [Description](#description)
- [Model Training](#model-training)
- [Model Deployment](#model-deployment)
- [Gradio Interface](#gradio-interface)
- [References](#references)

## Description

The purpose of this project is to detect toxic comments in the Tunisian dialect using a machine learning approach. By fine-tuning a BERT model, we aim to leverage its powerful natural language understanding capabilities to classify text as toxic or non-toxic. The project covers all stages from data preprocessing and model training to deploying the model in an interactive web application using Gradio.

## Model Training

The training process involves several key steps:
1. **Data Preparation:** The dataset, which contains comments labeled as toxic or non-toxic, is preprocessed and prepared for training.
2. **Model Fine-Tuning:** A pre-trained BERT model is fine-tuned on the prepared dataset. This process adjusts the model parameters to better fit the specific characteristics of Tunisian dialect toxicity.
3. **Evaluation:** The model's performance is evaluated to ensure it accurately detects toxic comments. The trained model weights are saved for deployment.

## Model Deployment

To make the model accessible and user-friendly, it is deployed as a web application using Gradio. Gradio is a Python library that allows developers to quickly create customizable UI components around their machine learning models. This deployment enables users to interact with the model directly through their web browsers.

## Gradio Interface

The Gradio interface includes two main functionalities: speech recognition and toxicity detection.

### Speech Recognition

Users can record audio using a microphone interface provided by Gradio. The audio is processed and sent to the "Tunisian-Automatic-Speech-Recognition" API. The recognized text is then displayed and can be analyzed for toxicity.

### Sentiment Analysis

The recognized text from the speech recognition function or text input by the user is classified as toxic or non-toxic using the fine-tuned BERT model. This interactive interface allows users to easily test and understand the model's predictions.

## References

- [Gradio Documentation](https://www.gradio.app/docs/)
- [BERT Model](https://www.techtarget.com/searchenterpriseai/definition/BERT-language-model)

For a detailed demonstration of the Gradio interface, watch the video below:

[![Watch the video](file:///E:/telechargements/Untitled%20design%20(1).mp4)]

