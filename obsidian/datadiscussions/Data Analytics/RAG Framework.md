

Verba, is our open-source RAG framework 🐕  
  
Verba has a modular architecture, which gives developers the flexibility to build! Want to keep your data private and run it 100% free? Use open-source models like SentenceTransformers and Llama2 and run Weaviate locally.  
  
Here is the repository: [https://lnkd.in/gsZRB-ZZ](https://lnkd.in/gsZRB-ZZ)  
  
Let’s dive into each component of the RAG framework developed by [Edward Schmuhl](https://www.linkedin.com/in/ACoAAC3DS9sBVCC0rg2W71rhKp3ufJxBvmnUC2Q)!  
  
Upload your data  
• We've integrated with [unstructured.io](https://www.linkedin.com/company/unstructuredio/) so you can seamlessly ingest your PDFs  
• Connect to [GitHub](https://www.linkedin.com/company/github/) repos by passing in the repo URL  
• Read files in your filesystem  
  
Chunk your data  
• You can choose how you want to chunk your data. Set it at the word or sentence level and determine the overlap of chunks.  
  
Embed your data (choose a provider)  
• [OpenAI](https://www.linkedin.com/company/openai/) (AdaEmbedder): text-embedding-ada-002  
• [Cohere](https://www.linkedin.com/company/cohere-ai/) (CohereEmbedder): embed-multilingual-v2.0 model  
• [Hugging Face](https://www.linkedin.com/company/huggingface/) (MiniLMEmbedder): all-MiniLM-L6-v2  
  
Generate text (choose a provider)  
• [Cohere](https://www.linkedin.com/company/cohere-ai/): command model  
• [OpenAI](https://www.linkedin.com/company/openai/): gpt-3.5-turbo-1106, gpt-4-1106-preview  
• [Hugging Face](https://www.linkedin.com/company/huggingface/): llama-2-7b-chat-hf  
  
Want to give it a try? Test it out on the [Weaviate](https://www.linkedin.com/company/weaviate-io/) documentation, blogs, and videos: [https://verba.weaviate.io/](https://verba.weaviate.io/)

[[Retrieval-Augmentation Generation-From Theory to LangChain Implementation]]
