### Generative Artificial Intelligence Engineering Notebooks

The following Amazon SageMaker Studio notebooks are available in this repository:
- `SM-JumpStart-Decoding-Falcon40B-G5.ipynb` demonstrates how to generate text using different decoding strategies with [Amazon SageMaker JumpStart SDK](https://sagemaker.readthedocs.io/en/v2.82.0/overview.html#use-prebuilt-models-with-sagemaker-jumpstart) and [Falcon-40B-Instruct model](https://huggingface.co/tiiuae/falcon-40b-instruct).

- `SM-JumpStart-RAG-Kendra-Falcon40B.ipynb` tation/api/latest/index.html) SDKs to generate text using the Retrieval-Augmented Generation (RAG) pattern. The notebook implements semantic search using [Amazon Kendra](https://aws.amazon.com/kendra/) enterprise search service. The language model used for text generation is [Falcon-40B-Instruct](https://huggingface.co/tiiuae/falcon-40b-instruct).

- `SageMaker-RAG-T5XXL-GPTJ-Faiss.ipynb` demonstrates how to use [SageMaker](https://sagemaker.readthedocs.io/en/stable/) and [LangChain](https://python.langchain.com/docs/get_started/introduction.html) python libraries to generate text following the Retrieval-Augmented Generation (RAG) pattern. The notebook implements semantic search using [Faiss](https://engineering.fb.com/2017/03/29/data-infrastructure/faiss-a-library-for-efficient-similarity-search/) similarity search library and [GPT-J 6B](https://huggingface.co/EleutherAI/gpt-j-6b) embeddings model. The language model used for text generation is [Flan-T5-XXL](https://huggingface.co/google/flan-t5-xxl).


To open a Jupyter Notebook using Amazon SageMaker, consider the two steps below:
1. [Create or Open an Amazon SageMaker Studio Notebook](https://docs.aws.amazon.com/sagemaker/latest/dg/notebooks-create-open.html).
2. [Clone this Git Repository in Amazon SageMaker Studio](https://docs.aws.amazon.com/sagemaker/latest/dg/studio-tasks-git.html).
