### Generative Artificial Intelligence Engineering Notebooks

This repository provides a collection of Generative AI engineering notebooks that demonstrate how to use Amazon SageMaker JumpStart SDK to customize Large Language Models (LLMs). The notebooks show using the Falcon and other model variants how to apply basic levels of inference customization such as: decoding strategies, prompting techniques, and Retrieval-Augmented Generation. The notebooks are designed to be easy to deploy and follow, making them a good resource for learning about LLM inference customization.

The following Amazon SageMaker Studio notebooks are available in this repository:
- `LLM-Custom-Decoding-Falcon7B.ipynb` demonstrates how to generate text using different decoding strategies with [Amazon SageMaker JumpStart SDK](https://sagemaker.readthedocs.io/en/v2.82.0/overview.html#use-prebuilt-models-with-sagemaker-jumpstart) and [Falcon-7B-Instruct model](https://huggingface.co/tiiuae/falcon-7b-instruct).

- `LLM-Custom-Prompting-Falcon7B.ipynb` demonstrates how to generate text using prompting engineering techniques with [Amazon SageMaker JumpStart SDK](https://sagemaker.readthedocs.io/en/v2.82.0/overview.html#use-prebuilt-models-with-sagemaker-jumpstart) and [Falcon-7B model](https://huggingface.co/tiiuae/falcon-7b).
  
- `LLM-Custom-RAG-Kendra-Falcon7B.ipynb` demonstrates how to use [SageMaker](https://sagemaker.readthedocs.io/en/stable/) and [boto3](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html) SDKs to generate text using the Retrieval-Augmented Generation (RAG) pattern. The notebook implements semantic search using [Amazon Kendra](https://aws.amazon.com/kendra/) enterprise search service. The language model used for text generation is [Falcon-7B-Instruct](https://huggingface.co/tiiuae/falcon-7b-instruct).

- `LLM-Custom-RAG-FlanUL2-GPTJ-Faiss.ipynb` demonstrates how to use [SageMaker](https://sagemaker.readthedocs.io/en/stable/) and [LangChain](https://python.langchain.com/docs/get_started/introduction.html) python libraries to generate text following the Retrieval-Augmented Generation (RAG) pattern. The notebook implements semantic search using [Faiss](https://engineering.fb.com/2017/03/29/data-infrastructure/faiss-a-library-for-efficient-similarity-search/) similarity search library and [GPT-J 6B](https://huggingface.co/EleutherAI/gpt-j-6b) embeddings model. The language model used for text generation is [Flan-UL2](https://huggingface.co/google/flan-ul2).


To open a Jupyter Notebook using Amazon SageMaker, consider the two steps below:
1. [Create or Open an Amazon SageMaker Studio Notebook](https://docs.aws.amazon.com/sagemaker/latest/dg/notebooks-create-open.html).
2. [Clone this Git Repository in Amazon SageMaker Studio](https://docs.aws.amazon.com/sagemaker/latest/dg/studio-tasks-git.html).
