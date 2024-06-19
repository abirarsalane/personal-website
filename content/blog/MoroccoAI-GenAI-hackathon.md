---
title: "Building a Speech-to-Speech Chatbot for enviromental Education"
description: "Building a Speech-to-Speech Chatbot for enviromental Education in a GenAI Hackathon."
dateString: Dec 2023
draft: false
tags: ["LLM", "AI", "GenAI", "Hugging Face", "RAG", "Fine-tuning", "Python"]
weight: 103
cover:
    image: "/blog/MoroccoAI-GenAI-hackathon/EcoTeach_image.jpg"
---


# Introduction
On December 2023, I embarked on an exhilarating journey during the **MoroccoAI Generative AI Hackathon**. Organized by [**MoroccoAI**](https://morocco.ai/). Our mission? To leverage the latest GenAI advances to address real-world challenges in specific industries.

# The Challenge: Educating Children on Climate Change
Our team's focus was clear: **environmental education for children**. We envisioned a **speech-to-speech chatbot** that would empower young minds with knowledge about climate change. Why kids? Because they are like sponges, eagerly absorbing information and forming lifelong habits.




# Technical Marvels: Models, Frameworks, and Fine-Tuning
## 1. Models from Hugging Face
We delved into the rich repository of **Hugging Face** models to find the best models for our use case. After benchmarking a couple of them in the limited amount of time we had, we went with models that balanced accuracy, fluency, and computational efficiency:
- STT: **facebook/seamless_m4t**:  foundational multilingual and multitask model that seamlessly translates and transcribes speech and text across 100 languages (including Moroccan dialect) 
- LLM: **mistralai/Mistral-7B-Instruct-v0.1**: The SOTA 7B LLM at the time of the hackathon.
- TTS: **LeeSangHoon/HierSpeech_TTS**: Speech synthesis at its finest! We harnessed this model to create expressive and context-aware speech utterances.

## 2. Langchain Framework
To orchestrate our chatbot's magic, we turned to the **Langchain** framework. Its modular design allowed us to seamlessly integrate different components. We crafted a pipeline that combined text preprocessing, model inference, and speech synthesis. The result? A harmonious symphony of words and voices.

## 3. Fine-Tuning and Prompt Engineering
Our chatbot wasn't just an out-of-the-box solution. We fine-tuned our chosen models using PEFT library on domain-specific data related to climate change. By feeding them relevant prompts, we tailored their responses to environmental queries. The art of prompt engineering became our secret sauce, ensuring that our chatbot spoke the language of eco-consciousness.

# Streamlit: The Interactive Interface
A chatbot without a user-friendly interface is like a book without a cover. Enter **Streamlit**! We crafted an elegant web app that allowed users to converse with our chatbot effortlessly. The interface featured input fields where curious minds could ask questions about climate, pollution, and sustainability. The chatbot responded with synthesized speech, making learning engaging and accessible.

So, next time you see a child interacting with our chatbot, remember: **we're nurturing a greener future, one conversation at a time.**
