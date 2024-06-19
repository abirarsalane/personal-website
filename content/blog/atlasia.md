---
title: "Open Source Moroccan LLMs project"
description: "I joined the Moroccan Community of engineers, researchers, professors, students and professionals building the next generation of customized, open, Moroccan AI models."
dateString: May 2024
draft: false
tags: ["AI", "LLM", "Models", "Open Source", "Datasets"]
weight: 100
cover:
    image: "/blog/atlasia/atlasia.png"
---


# Introduction

I am proud to be a member of Atlasia the Moroccan community of engineers, researchers, professors, students, and professionals dedicated to building the next generation of customized, open AI models. Our mission is to develop AI technologies that are aligned with our values, identity, and culture. This open-source initiative focuses on creating models, datasets, benchmarks, and other resources to advance the field of artificial intelligence in Morocco.


# English-to-Darija Translation Models

## Project Goals

The primary goal of the English-to-Darija translation project was to create high-quality models capable of translating English text into Darija, the colloquial Arabic spoken in Morocco. This initiative aimed to:

- Preserve and promote the Darija language by making it more accessible in the digital age.
- Help moroccans and non-moroccans translate from darija to english and vice-versa.
- Provide a valuable resource for the Moroccan diaspora and non-Darija speakers interested in learning the language.
- Facilitate better communication and cultural exchange between English and Darija speakers.

## Development Process

1. **Data Collection:** Gathered a diverse and extensive dataset of parallel English-Darija texts by the help of volunteers through a website where they can input data in a user friendly interface, and generated datasets from the team and all open-sources contributors.
   
2. **Data Preprocessing:** The collected data was cleaned, normalized, and annotated to ensure high quality and consistency. This step was crucial for training effective machine learning models.

3. **Model Training:** Trained several translation models using state-of-the-art neural network architectures. Experimented with different hyperparameters and configurations to optimize performance.

4. **Evaluation and Benchmarking:** The models were rigorously evaluated using standard metrics and benchmarks. Compared their performance against existing translation tools to ensure they met our quality standards.

5. **Open-Sourcing:** Once the models were finalized, they were published on Hugging Face, making them freely available to the global community. This aligns with our commitment to open-source principles and collaborative development.

**The current available models are:**
- Terjman Nano (77M parameters)
- Terjman Large (240M parameters)
- Terjman Ultra (1.3B parameters) 
- Terjman Supreme (3.3B parameters)

**Closer look at Terjman Suprem:**
The model is built upon the powerful Transformer architecture, leveraging state-of-the-art natural language processing techniques. It is a fine-tuned version of facebook/nllb-200-3.3B on a the darija_english dataset enhanced with curated corpora ensuring high-quality and accurate translations.

It achieves the following results on the evaluation set:

- Loss: 2.3687
- Bleu: 5.6718
- Gen Len: 39.9504

The finetuning was conducted using a A100-40GB and took 57 hours.

**The current available datasets are:**
- darija_english
- ATAM
- DODa

# Impact and Future Work

The release of the English-to-Darija translation models has had a significant impact:

- **Accessibility:** These models have made it easier for people to access and understand Darija, bridging the language gap between English and Darija speakers.
- **Cultural Preservation:** By promoting the use of Darija in digital platforms, we are helping to preserve and celebrate Moroccan culture.
- **Educational Tool:** These models serve as a valuable resource for educators and students, enhancing language learning and research.

## Future Plans

Building on this success, the community plans to:

- **Expand the Dataset:** Continuously update and expand the dataset to improve model accuracy and coverage.
- **Develop Additional Models:** Create more AI models for other Moroccan languages and dialects.

## Conclusion

Joining and contributing to the Moroccan AI community has been an enriching experience. Together, we are not only advancing AI technology but also fostering a sense of pride and identity through our work. I look forward to continuing this journey and making further contributions to this vibrant and impactful community.


