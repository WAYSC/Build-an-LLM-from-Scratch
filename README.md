# Build a Large Language Model from Scratch

This repository contains my **chapter-by-chapter implementations and experiments** based on the book  
**“Build a Large Language Model (From Scratch)” by Sebastian Raschka**.

The goal of this project is to **understand and implement the full LLM training pipeline from first principles**, without relying on high-level abstractions.

---

## 🎯 Objective

This repository focuses on:

- Understanding how large language models work internally
- Implementing a GPT-style model step by step
- Training models on unlabeled and labeled data
- Applying fine-tuning techniques, including LoRA
- Gaining hands-on experience with PyTorch-based training loops

This is a **from-scratch, learning-oriented implementation**, not a production framework.

---

## 📚 Book Structure & Covered Topics

The repository follows the structure of the book and corresponding chapters:

### Chapter Overview

1. **Understanding Large Language Models**  
   High-level concepts behind modern LLMs and transformer-based architectures.

2. **Processing Text Data**  
   Tokenization, vocabulary construction, and text-to-tensor pipelines.

3. **Encoding with Attention Mechanisms**  
   Self-attention, scaled dot-product attention, and multi-head attention.

4. **Building a GPT Model from Scratch**  
   Implementing a full GPT-style model capable of text generation.

5. **Pretraining on Unlabeled Data**  
   Language modeling objectives, training loops, and optimization strategies.

6. **Classification Fine-Tuning**  
   Adapting pretrained models for downstream classification tasks.

7. **Instruction Fine-Tuning**  
   Training models to follow instructions and align with user intent.

---

## 📎 Appendices Implemented

Additional advanced topics are explored through appendices:

- **Appendix A — PyTorch Primer**  
- **Appendix B — References and Further Reading**  
- **Appendix C — Exercise Solutions**  
- **Appendix D — Extending the Training Loop**  
- **Appendix E — Parameter-Efficient Fine-Tuning with LoRA**

---

## 📁 Repository Structure

The repository is organized by **book chapters**, ensuring a clear mapping between theory and implementation:

```text
├── ch02.ipynb
├── ch03.ipynb
├── ch04.ipynb
├── ch05.ipynb
├── ch06.ipynb
├── ch07.ipynb
├── images/
│   └── figures_and_diagrams
└── assets/
```
- Each chXX.ipynb corresponds directly to a book chapter
- Notebooks contain experiments, implementations, and training code
- The images/ folder stores figures used in explanations and notes

## 📝 Language Notes
- All filenames and documentation are written in English

- Code comments may be written in Chinese

Chinese comments are used intentionally to:

- Capture detailed reasoning during implementation

- Explain non-trivial design decisions

- Serve as teaching-oriented annotations

## ⚠️ Disclaimer
- This repository is for educational and research purposes

- Code prioritizes clarity and understanding over optimization

- Implementations may evolve as understanding deepens

## 📬 Feedback
Questions, corrections, and discussions are welcome.

This repository represents an ongoing exploration of how large language models are built from the ground up.