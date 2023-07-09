### Generative Artificial Intelligence Engineering Notebooks

The following Amazon SageMaker Studio notebooks are available in this repository:
- `SM-JumpStart-Decoding-Falcon40B-G5.ipynb demonstrates how to generate text using different decoding strategies with [Amazon SageMaker JumpStart SDK](https://sagemaker.readthedocs.io/en/v2.82.0/overview.html#use-prebuilt-models-with-sagemaker-jumpstart) and [Falcon-40B-Instruct model](https://huggingface.co/tiiuae/falcon-40b-instruct).

- `SM-JumpStart-RAG-Kendra-Falcon40B.ipynb` demonstrates how to customize a Large Language Model by adopting the  Retrieval-Augmented Generation (RAG) pattern and Amazon Kendra enterprise search service using [Amazon SageMaker JumpStart SDK](https://sagemaker.readthedocs.io/en/v2.82.0/overview.html#use-prebuilt-models-with-sagemaker-jumpstart) and [Falcon-40B-Instruct model](https://huggingface.co/tiiuae/falcon-40b-instruct).

- `SageMaker-RAG-T5XXL-GPTJ-Faiss.ipynb` emonstrates how to use SageMaker and [LangChain](https://python.langchain.com/docs/get_started/introduction.html) python libraries to generate text following the Retrieval-Augmented Generation (RAG) pattern. The notebook implements semantic search using [Faiss](https://engineering.fb.com/2017/03/29/data-infrastructure/faiss-a-library-for-efficient-similarity-search/) similarity search library.


To open a Jupyter Notebook using Amazon SageMaker, consider the two steps below:
1. [Create or Open an Amazon SageMaker Studio Notebook](https://docs.aws.amazon.com/sagemaker/latest/dg/notebooks-create-open.html).
2. [Clone this Git Repository in Amazon SageMaker Studio](https://docs.aws.amazon.com/sagemaker/latest/dg/studio-tasks-git.html).
