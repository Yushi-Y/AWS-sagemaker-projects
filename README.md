# AWS-SageMaker-Projects

This repository contains my experiments with both built-in and custom machine learning algorithms using SageMaker Notebooks. These notebooks are adapted from various resources including the official AWS ML Learning Plan, Udemy's AWS ML Speciality course, and other AWS online resources.

## Projects Overview

### Deploy and Fine-Tune Pre-Trained LLMs on SageMaker Jumpstart

- **Transformers_SageMaker.ipynb**: 
  - Includes tokenization and positional encoding, self-attention techniques.
  - Deploys GPT-2 in SageMaker notebooks using Huggingface.

- **text-generation-falcon.ipynb**: 
  - Deploys the pre-trained Falcon models in SageMaker for various text generation tasks like summarization and question answering.

- **llama-2-finetuning.ipynb**: 
  - Fine-tunes the pre-trained LLama-2 model for instruction-like text data in SageMaker.

### Detecting Bees in Images

- Utilized a SageMaker pre-trained object detection algorithm (MXNet) to detect bees in images.
- Performed further training on bee images from inaturalist.org with fine-tuned hyperparameters.
- Used Amazon SageMaker Ground Truth for labeling the images.

### Movie Recommender with Factorization Machines

- Built a movie recommender system using 100k ratings from the MovieLens dataset and the built-in Factorization Machines algorithm.

### Article Retrieval from Wikipedia using TF-IDF

- Developed a PySpark Notebook on an EC2 instance with EMR clusters.
- Retrieved the most relevant Wikipedia articles for a given query by computing TF-IDF scores.

### Custom CNN for MINST Classification

- Developed a custom CNN model in Keras for MINST classification.
- Ran the model directly in a Jupyter Notebook connected to an EC2 instance.
- Created a CNN model script for SageMaker, packaged it in a Keras container, and deployed it to an endpoint for prediction.

### Planned Projects

- **TO ADD**: Mobile price classification using Random Forests and Scikit-Learn.
