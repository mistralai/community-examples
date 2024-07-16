# Mistral Cookbook

The Mistral Cookbook features examples contributed by Mistralers and our community, as well as our partners. If you have cool examples showcasing Mistral models, feel free to share them by submitting a PR to this repo.

## Submission Guidelines:

- File Format: Please submit your example in the .md or .ipynb format.
- Runnable on Colab: If you're sharing a notebook example, try to make sure it's runnable on Google Colab.
- Authorship: Kindly include your name, your Github handle, and affiliation at the beginning of the file.
- Descriptions: Please include your notebook along with its category and descriptions in the table below.
- Tone: Kindly maintain a neural tone and minimize any excessive marketing materials.
- Reproducibility: To ensure others can reproduce your work, kindly tag package versions in your code.
- Image size: If you have images, please make sure each image's size is below 500KB.
- Copyright: Always respect copyright and intellectual property laws.

Disclaimer: Examples contributed by the community and partners do not represent Mistral's views and opinions.

## Content Guidelines:

- Originality: Is your content original and offering a fresh perspective?
- Clear: Is your content well-structured and clearly written?
- Value: Is your content valuable to the community? Does the community need it?

## Main Notebooks

| Notebook                                                                       | Category                     | Description                                                                      |
|--------------------------------------------------------------------------------|-----------------------------|----------------------------------------------------------------------------------|
| [quickstart.ipynb](quickstart.ipynb)                                           | chat, embeddings             | Basic quickstart with chat and embeddings with Mistral AI API                    |
| [prompting_capabilities.ipynb](mistral/prompting/prompting_capabilities.ipynb) | prompting                    | Write prompts for classification, summarization, personalization, and evaluation |
| [basic_RAG.ipynb](mistral/rag/basic_RAG.ipynb)                                 | RAG                          | RAG from scratch with Mistral AI API                                             |
| [embeddings.ipynb](mistral/embeddings/embeddings.ipynb)                        | embeddings                   | Use Mistral embeddings API for classification and clustering                     |
| [function_calling.ipynb](mistral/function_calling/function_calling.ipynb)      | function calling             | Use Mistral API for function calling                                             |
| [evaluation.ipynb](mistral/evaluation/evaluation.ipynb)                        | evaluation                   | Evaluate models with Mistral API                                                 |
| [mistral_finetune_api.ipynb](mistral/fine_tune/mistral_finetune_api.ipynb)     | fine-tuning                  | Finetune a model with Mistral fine-tuning API                                    |
| [mistral-search-engine.ipynb](mistral/rag/mistral-search-engine.ipynb)         | RAG, function calling        | Search engine built with Mistral API, function calling and RAG                   |
| [prefix_use_cases.ipynb](mistral/prompting/prefix_use_cases.ipynb)             | prefix, prompting            | Cool examples with Mistral's prefix feature                                      |
| [synthetic_data_gen_and_finetune.ipynb](mistral/data_generation/synthetic_data_gen_and_finetune.ipynb) | data generation, fine-tuning | Simple data generation and fine-tuning guide        |
| [data_generation_refining_news.ipynb](mistral/data_generation/data_generation_refining_news.ipynb) | data generation | Simple data generation to refine news articles                                |

## Third Party Tools

| Tools                                                                                                           | Category               | Party      |
| :-------------------------------------------------------------------------------------------------------------- | :--------------------- | :--------- |
| [adaptive_rag_mistral.ipynb](third_party/langchain/adaptive_rag_mistral.ipynb)                                  | RAG                    | Langchain  |
| [Adaptive_RAG.ipynb](third_party/LlamaIndex/Adaptive_RAG.ipynb)                                                 | RAG                    | LLamaIndex |
| [Agents_Tools.ipynb](third_party/LlamaIndex/Agents_Tools.ipynb)                                                 | agent                  | LLamaIndex |
| [arize_phoenix_tracing.ipynb](third_party/Phoenix/arize_phoenix_tracing.ipynb)                                  | tracing data           | Phoenix    |
| [azure_ai_search_rag.ipynb](third_party/Azure_AI_Search/azure_ai_search_rag.ipynb)                              | RAG, embeddings        | Azure      |
| [Chainlit - Mistral reasoning.ipynb](third_party/Chainlit/Chainlit_Mistral_reasoning.ipynb)                     | UI chat, tool calling  | Chainlit   |
| [corrective_rag_mistral.ipynb](third_party/langchain/corrective_rag_mistral.ipynb)                              | RAG                    | Langchain  |
| [distilabel_synthetic_dpo_dataset.ipynb](third_party/argilla/distilabel_synthetic_dpo_dataset.ipynb)            | synthetic data         | Argilla    |
| [E2B Code Interpreter SDK with Codestral](third_party/E2B_Code_Interpreting)                                    | tool, agent            | E2B        |
| [function_calling_local.ipynb](third_party/Ollama/function_calling_local.ipynb)                                 | tool call              | Ollama     |
| [Gradio Integration - Chat with PDF](third_party/gradio/README.md)                                              | UI chat, demo, RAG     | Gradio     |
| [haystack_chat_with_docs.ipynb](third_party/Haystack/haystack_chat_with_docs.ipynb)                             | RAG, embeddings        | Haystack   |
| [Indexify Integration - PDF Entity Extraction](third_party/Indexify/pdf-entity-extraction)                      | entity extraction, PDF | Indexify   |
| [Indexify Integration - PDF Summarization](third_party/Indexify/pdf-summarization)                              | summarization, PDF     | Indexify   |
| [langgraph_code_assistant_mistral.ipynb](third_party/langchain/langgraph_code_assistant_mistral.ipynb)          | code                   | Langchain  |
| [langgraph_crag_mistral.ipynb](third_party/langchain/langgraph_crag_mistral.ipynb)                              | RAG                    | Langchain  |
| [llamaindex_agentic_rag.ipynb](third_party/LlamaIndex/llamaindex_agentic_rag.ipynb)                             | RAG, agent             | LLamaIndex |
| [llamaindex_mistralai_finetuning.ipynb](third_party/LlamaIndex/llamaindex_mistralai_finetuning.ipynb)           | fine-tuning            | LLamaIndex |
| [Mesop Integration - Chat with PDF](third_party/mesop/README.md)                                                | UI chat, demo, RAG     | Mesop      |
| [neon_text_to_sql.ipynb](third_party/Neon/neon_text_to_sql.ipynb)                                               | code                   | Neon       |
| [ollama_mistral_llamaindex.ipynb](third_party/LlamaIndex/ollama_mistral_llamaindex.ipynb)                       | RAG                    | LLamaIndex |
| [Ollama Meetup Demo](third_party/Ollama/20240321_ollama_meetup)                                                 | demo                   | Ollama     |
| [Panel Integration - Chat with PDF](third_party/panel/README.md)                                                | UI chat, demo, RAG     | Panel      |
| [pinecone_rag.ipynb](third_party/Pinecone/pinecone_rag.ipynb)                                                   | RAG                    | Pinecone   |
| [RAG.ipynb](third_party/LlamaIndex/RAG.ipynb)                                                                   | RAG                    | LLamaIndex |
| [RouterQueryEngine.ipynb](third_party/LlamaIndex/RouterQueryEngine.ipynb)                                       | agent                  | LLamaIndex |
| [self_rag_mistral.ipynb](third_party/langchain/self_rag_mistral.ipynb)                                          | RAG                    | Langchain  |
| [Streamlit Integration - Chat with PDF](third_party/streamlit/README.md)                                        | UI chat, demo, RAG     | Streamlit  |
| [SubQuestionQueryEngine.ipynb](third_party/LlamaIndex/RouterQueryEngine.ipynb)                                  | agent                  | LLamaIndex |
