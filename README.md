===============================================================================
# RAG-Using-Llama2-in-Local-setup
===============================================================================
## Tech stack:
        (1)Python
        (2)Langchain
        (3)Flask
        (4)Meta Llama2 LLM
        (5)FAISS (Vector DB)
-------------------------------------------------------------------------------
## Steps to run:

### (1) Create Environment
```bash
conda create -n llama2_cpu python=3.8 -y
```
```bash
conda activate llama2_cpu
```

### (2) Install "requirements.txt"
```bash
pip install -r requirements.txt
```
### (3) Download the quantized model from the link given below:
```ini
## Llama 2 Model name with version:
llama-2-7b-chat.ggmlv3.q4_0.bin

## Download link:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main
```
### (4) Run "main.py":
```bash
python main.py
```
-------------------------------------------------------------------------------