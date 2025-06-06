# From Zero to GPT: A Hands-On Deep Learning Journey

Welcome to this curated Colab series inspired by Andrej Karpathy’s **"Zero to Hero"** tutorials. These notebooks walk you step-by-step from the fundamentals of backpropagation to building your own GPT-like Transformer, with a practical and minimalist approach to understanding deep learning through code.

---

## 🔢 1. [Micrograd – Autodiff from Scratch](./Micrograd/01_micrograd.ipynb)

A ground-up implementation of backpropagation using a custom `Value` class.

**What you'll learn:**
- Derivatives from scratch (single & multi-input)
- Manual backpropagation on expressions and neurons
- Building a computation graph
- Implementing a backward pass
- Comparing with PyTorch’s autograd
- Creating a tiny MLP neural net from first principles

---

## 🔤 2. [Makemore-01 – Bigram Language Model](./makemore01_colab.ipynb)

Construct a simple bigram character-level model using both counting and neural methods.

**Highlights:**
- Count-based bigram matrix (Python & torch.Tensor)
- Sampling and probability visualization
- Negative log likelihood loss
- Vectorization and efficiency via tensor broadcasting
- One-hot encoding and a minimal neural net
- Manual training loop with PyTorch

---

## 🧠 3. [Makemore-02 – MLP Language Model](./makemore02_colab.ipynb)

Build a deeper neural language model following Bengio et al. (2003).

**Includes:**
- Embedding lookups
- Hidden layers and output logits
- `F.cross_entropy` loss
- Training on full dataset with minibatches
- Learning rate tuning
- Visualization of learned embeddings
- Sampling generated text

---

## ⚙️ 4. [Makemore-03 – Deep MLPs & BatchNorm](./makemore03_colab.ipynb)

Train deeper networks reliably with better initialization and normalization.

**You’ll explore:**
- Diagnosing training issues (e.g. vanishing gradients)
- Tanh saturation and how to fix it
- Kaiming initialization
- Batch Normalization: theory and practice
- Visualizing forward/backward pass statistics

---

## 🧱 5. [Makemore-04 – Leaky Abstractions in Deep Learning](./makemore04_colab.ipynb)

A philosophical and practical reminder: abstractions like `.backward()` can leak.

**Key ideas:**
- Why understanding backpropagation still matters
- Real-world issues: shape bugs, silent gradient issues, misuse of `.detach()`
- Encourage a deeper understanding of what the model is really doing

---

## 🌊 6. [Makemore-05 – WaveNet-Inspired Architecture](./makemore05_colab.ipynb)

Build a deeper model with a WaveNet-style, hierarchical architecture.

**Topics covered:**
- Refactoring with `torch.nn.Module`
- Expanding `block_size` for longer context
- BatchNorm troubleshooting
- Model scaling and experimental harnesses
- Preparation for dilated causal convolutions

---

## 🧠 7. [GPT – A Minimal Transformer from Scratch](./gpt_colab.ipynb)

Train a Transformer (nanoGPT-style) on Shakespeare from scratch.

**What you're building:**
- A minimal GPT: ~300 lines of code
- Transformer model (self-attention, feedforward, layernorm, etc.)
- Trains on raw character-level data
- Produces Shakespeare-like text
- Framework extensible to larger datasets or pretrained weights

---

## 📚 Technologies Used

- Python (3.8+)
- PyTorch
- Jupyter / Google Colab
- Matplotlib (for visualizations)
- Numpy

---

## 🧭 Learning Path Overview

1. **Backprop & Autodiff** → `micrograd`
2. **Simple Models** → `bigram`, `neural bigram`
3. **Scaling up** → `MLP`, `BatchNorm`, `WaveNet`
4. **Modern Deep Learning** → `Transformer`, `GPT`

Each notebook builds on the previous, blending intuition, math, and clean PyTorch code. Perfect for learners who want to **understand, not just run** deep learning models.

---

## ✅ How to Use

Open each notebook in [Google Colab](https://colab.research.google.com/), run the cells step-by-step, and explore the outputs. All notebooks are self-contained and progressively increase in complexity.

---

## Credits

Tutorial series based on Andrej Karpathy's [Zero to Hero](https://karpathy.ai/) series. Reimplemented, adapted, and extended in Colab format for clarity and experimentation.


## Contact

📧 henningkb@outlook.com

🌐 [GitHub](https://github.com/Henning-Kubatzsch)  

🌍 [LinkedIn](https://www.linkedin.com/in/henning-kubatzsch-632353324/)

---

Thanks for visiting!
