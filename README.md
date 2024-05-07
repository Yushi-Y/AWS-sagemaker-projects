# AWS-SageMaker-Projects
Using SageMaker Notebooks, I experimented with built-in and custom machine learning algorithms. The notebooks are modified based on the official AWS ML Learning Plan, Udemy's AWS ML Speciality course, and AWS online resources. 

Deploy and fine-tune pre-trained LLMs on SageMaker Jumpstart:
- Transformers_SageMaker.ipynb: Included tokenization and positional encoding, self-attention, and deployed GPT-2 in Sagemaker notebooks with Huggingface
- text-generation-falcon.ipynb: Deployed the pre-trained Falcon models in Sagemaker to do a variety of text generation tasks (summarisation, question answering, etc.)
- llama-2-finetuning.ipynb: Fine-tuned the pre-trained LLama-2 model for instruction-like text data in Sagemaker

Detecting Bees in Images: 
Detected bees in images using a SageMaker pre-trained object detection algorithm (MXNet). Further training was performed on the images of bees from inaturalist.org with fine-tuned hyperparameters. The images were first labeled using Amazon SageMaker Ground Truth.

Article Retrival from Wikipedia using TF-IDF: 
Built a PySpark Notebook on an EC2 instance with EMR clusters. Retrieved the most relevant Wikipedia articles for a given article by computing the TF-IDF scores.

CNN for MINST Classification: 
Developed a custom CNN model in Keras for MINST classification, both on EC2 and SageMaker. For EC2, I connected a Jupiter notebook to an EC2 instance and ran the model directly in the notebook. For SageMaker, I created a CNN model script, packaged it in a Keras container, and deployed it to an endpoint for prediction.

TO ADD: mobile price classification with RF and SKlearn

