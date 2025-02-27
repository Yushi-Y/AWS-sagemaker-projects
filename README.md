# AWS-SageMaker-Projects

This repository contains my experiments with both built-in and custom machine learning algorithms using SageMaker Notebooks. These notebooks are adapted from the official AWS ML Learning Plan, Udemy's AWS ML Speciality course, and other AWS online resources.

## Projects Overview

### Basic SageMaker Notebooks
- **linear_learner_minst.ipynb**: 
  - Train a simple linear classifier for MINST classification.


### Deploy and Fine-Tune Pre-Trained LLMs on SageMaker Jumpstart

- **Transformers_SageMaker.ipynb**: 
  - Apply tokenization, positional encoding, and self-attention.
  - Deploy GPT-2 in SageMaker notebooks using Huggingface.

- **text-generation-falcon.ipynb**: 
  - Deploy the pre-trained Falcon models in SageMaker for various text generation tasks like summarisation and question answering.

- **llama-2-finetuning.ipynb**: 
  - Fine-tune the pre-trained LLama-2 model on instruction-following text data in SageMaker.

### Detecting Bees in Images

- Utilise a SageMaker pre-trained object detection algorithm (MXNet) to detect bees in images.
- Perform further training on bee images from inaturalist.org with fine-tuned hyperparameters.
- Use Amazon SageMaker Ground Truth for labelling the images.

### Movie Recommender with Factorization Machines

- Build a movie recommender system using 100k ratings from the MovieLens dataset and the built-in Factorization Machines algorithm.

### Article Retrieval from Wikipedia using TF-IDF

- Develop a PySpark Notebook on an EC2 instance with EMR clusters.
- Retrieved the most relevant Wikipedia articles for a given query by computing TF-IDF scores.

### Custom CNN for MINST Classification

- Develop a custom CNN model in Keras for MINST classification.
- Run the model directly in a Jupyter Notebook connected to an EC2 instance.
- Create a CNN model script for SageMaker, packaged it in a Keras container, and deployed it to an endpoint for prediction.

### Planned Projects

- **TO ADD**: Mobile price classification using Random Forests and Scikit-Learn.
