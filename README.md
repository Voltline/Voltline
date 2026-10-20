# 👋 Hi, I'm Voltline

![GitHub followers](https://img.shields.io/github/followers/Voltline?label=Followers&style=social)
![GitHub User's stars](https://img.shields.io/github/stars/Voltline?affiliations=OWNER%2CCOLLABORATOR&style=social)

CS graduate student at **[Shanghai Jiao Tong University](https://www.sjtu.edu.cn/)**, building things where **systems meet machine learning** — from on-device language models and iOS input methods to IM backends and compilers.

## 🧑‍💻 About Me
- 🎓 Graduate student in Computer Science at **SJTU**.
- 📱 Previously interned at [ByteDance](https://www.bytedance.com/) as an iOS engineer (**Objective-C**, **UIKit**).
- 🧠 Currently working on **on-device small language models** — training, evaluating, quantizing, and shipping them inside a real iOS keyboard.
- 🔭 Interested in **MLLM**, **system programming**, **computer vision**, and high-performance, scalable systems.

## 🛠️ Tech Stack
- **Languages**: C/C++, Go, Python, Swift, Objective-C, Java
- **ML**: PyTorch, Transformers, SentencePiece, Core ML (INT8 quantization, KV cache)
- **Areas**: On-device ML, System Programming, Compiler Design, Computer Vision, Network Communication, MLLM

## 🌟 Current Focus: Vime

> A Japanese input method for iOS, powered by a tiny language model that runs entirely on the device.

- **[Vime](https://github.com/Voltline/Vime)** — An iOS Japanese romaji keyboard written in **Swift**. Offline kana-kanji conversion built on [AzooKeyKanaKanjiConverter](https://github.com/azooKey/AzooKeyKanaKanjiConverter), with whole-sentence and segment conversion, typo correction, candidate learning, user dictionaries, custom skins, and optional **local Core ML reranking and next-word prediction**.
- **[VimeML](https://github.com/Voltline/VimeML)** — The model side of Vime: a **tiny Japanese Transformer LM** (≤15M params) trained from scratch to rerank conversion candidates and suggest phrases inside a memory-constrained keyboard extension. Covers the full pipeline — corpus cleaning, tokenizer training, pretraining, benchmark construction, and Core ML export with INT8 quantization.

```
Romaji → Kana → AzooKey candidates → Tiny Japanese LM rerank → Final candidates
```

## 🚀 Other Projects
### Systems & Tools
- [Betterfly2](https://github.com/Voltline/Betterfly2): A **high-performance instant-messaging backend** written in Go.
- [EERenderer](https://github.com/Voltline/EERenderer): An **embodied experience system** built for Apple Vision Pro.
- [QuickIM](https://github.com/Voltline/QuickIM): A lightweight C++ instant-messaging tool for basic message sending and receiving.
- [MySTL](https://github.com/Voltline/MySTL): A from-scratch, simplified C++ STL covering containers such as `vector`, `list`, and `queue`.

### Course Projects
- [L25-Compiler](https://github.com/Voltline/L25-Compiler): A **compiler** in C++ for the Compiler Principles course, with **syntax analysis** and **code generation**.
- [Betterfly](https://github.com/Voltline/Betterfly): The original Python version of the Betterfly IM backend.
- [Wisdom-Academic-Affairs](https://github.com/Voltline/Wisdom-Academic-Affairs): A Qt-based academic affairs management system (Data Structures course).
- [Fight_Against_Gravity](https://github.com/Voltline/Fight_Against_Gravity): A **2D game** made with **Pygame** — beat gravity to clear each challenge.

## 📬 Contact
- Email: voltline233@gmail.com

Feel free to star or fork any project, and issues or discussions are always welcome!
