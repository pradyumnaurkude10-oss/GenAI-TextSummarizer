TEXT SUMMARIZER

An open-source, local-first Generative AI application that leverages state-of-the-art Deep Learning to distill long-form text into crisp, concise summaries. Built using Hugging Face Transformers, optimized with PyTorch, and wrapped in an intuitive web interface powered by Gradio.

Key Features:

State-of-the-Art NLP: Powered by the distilbart-cnn-12-6 model for high-quality abstractive text summarization.

Performance Optimized: Configured with bfloat16 precision for fast, memory-efficient inference (runs smoothly on local machines with CUDA/NVIDIA GPU acceleration).

User-Friendly UI: Simple, clean Gradio web interface featuring easy text input, customizable lengths, and single-click execution.

Hugging Face Spaces Ready: Pre-configured for seamless deployment and instant cloud hosting.

Tech Stack:

Frameworks: PyTorch, Gradio

Model Provider: Hugging Face (Transformers)

Core Model: sshleifer/distilbart-cnn-12-6

⚙️ Quick Start Instructions
Install Dependencies: Open your terminal in the project directory and run the command: pip install -r requirements.txt
(Ensure you have Python 3.10 and the appropriate NVIDIA CUDA toolkit installed if you wish to leverage GPU acceleration).

Run the Application: Launch the development server by executing: python app.py

Open the App: Once running, open your web browser and navigate to http://localhost:7860 to start summarizing your text!

---
title: TextSummarizer
emoji: 🦀
colorFrom: red
colorTo: yellow
sdk: gradio
sdk_version: 4.29.0
app_file: app.py
pinned: false
license: apache-2.0
---

Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference
