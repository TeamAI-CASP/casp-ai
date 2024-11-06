## Base Configuration

### General Configuration

- **Configuration Name:** base_configuration
- **Folder:** (not specified)
- **Framework:** llama
- **Task:** text-generation
- **GPT Flag:** false
- **Llama Flag:** false

### Model Details

- **GPT Model:** gpt-3.5-turbo
- **Llama Model:** meta-llama/Llama-2-7b-chat-hf

### Sampling and Decoding Parameters

- **Do Sample:** true
- **Top-k:** 10
- **Number of Return Sequences:** 1
- **Max Length:** 400

### Retriever and Reader Configuration

- **Retriever:** BM25Retriever
- **Retriever k:** 10
- **Reader:** deepset/minilm-uncased-squad2
- **Reader k:** 1
