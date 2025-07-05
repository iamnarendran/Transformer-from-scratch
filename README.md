# 🧠 Transformer from Scratch 🚀

This project demonstrates a complete implementation of the Transformer architecture from scratch using PyTorch — no Hugging Face, no shortcuts. It's built for learning and understanding the internals of how models like GPT and BERT work at the foundational level.

## 📌 What’s Included?

- ✅ Multi-Head Self Attention  
- ✅ Transformer Encoder & Decoder Blocks  
- ✅ Positional Embeddings  
- ✅ Causal and Padding Masking  
- ✅ Full Transformer Class (Encoder-Decoder)  
- ✅ Dummy Training Data and Forward Pass  
- ✅ Fully Commented and Colab-Friendly Code  
- ✅ Compatible with CPU or CUDA

---

## 📂 Project Structure

├── transformer_from_scratch.ipynb 
          # Complete implementation
└── README.md 
          # project documentation

---

## 🚀 Quick Start

### Clone and Run

```bash
git clone https://github.com/iamnarendran/Transformer-from-scratch.git
cd Transformer-from-scratch
python transformer_from_scratch.py
```

---

## Output Example

```
torch.Size([2, 7, 10])
```

| 2 → batch size

| 7 → output sequence length (target without last token)

| 10 → logits for each token in vocab (vocab size = 10)