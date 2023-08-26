# Intent Detection: From Sesame Street to LLMs

#IndoML 2023 #Datathon #Tutorial

<img src="images/poster.jpg" width="100%">


## Notebooks

1. EDA.ipynb → [![Open in Colab](https://colab.research.google.com/github/bsantraigi/)]

## Tutorial

In the online tutorial we will go over the notebooks of this repo. We focus on the [AmazonScience/MASSIVE](https://huggingface.co/datasets/AmazonScience/massive) multilingual intent-detection. 

There are few different parts to the tutorial:

1. EDA.ipynb: We first explore the dataset a bit to understand the task and various stats about the data. We also get to see how to use the `datasets` library from HuggingFace, what metadata information is available, and how to apply preprocessing to the data.
2. FinetuneTransformer.ipynb: We then finetune a transformer model on the dataset. We use the `Trainer` class from HuggingFace to do this. 
3. LLM_PromptEngineering.ipynb: We then explore the use of LLMs for intent detection. We explore an in-context learning method to solve the task using a instruction-finetuned large-language model (LLM), without any finetuning.

There are also a few other bonus scripts available that showcases the use of other advanced techniques like parameter efficient tuning and low-rank adaptation methods. These methods will be useful for the datathon, to tackle the few-shot challenge in later phases and running on GPU devices available through Colab.

## Where to get free GPU resources?

Best options are Kaggle Notebooks and Google Colab.

## Other Links


* Nice blog about training very large models (Falcon-7b!) on Colab: [The Falcon has landed in the Hugging Face ecosystem](https://huggingface.co/blog/falcon)
    * Colab Link: [Finetuning Falcon-7b](https://colab.research.google.com/drive/1BiQiw31DT7-cDp1-0ySXvvhzqomTdI-o?usp=sharing)

