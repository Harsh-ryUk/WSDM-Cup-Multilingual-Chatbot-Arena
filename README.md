# WSDM Cup ‑ Multilingual Chatbot Arena

##  Competition Overview

- **Name**: WSDM Cup ‑ Multilingual Chatbot Arena ([kaggle.com](https://www.kaggle.com/competitions/wsdm-cup-multilingual-chatbot-arena))  
- **Hosted by**: Kaggle in collaboration with LMSYS and Chatbot Arena (lmarena.ai) ([wsdm-conference.org](https://www.wsdm-conference.org/2025/2025-wsdm-cup-lmsys-multilingual-chatbot-arena))  
- **Objective**: Predict which responses users will prefer in a head‑to‑head battle between chatbots powered by large language models.

##  Important Dates

- Competition start: November 18, 2024  
- Submission deadline: February 3, 2025  
- Award Ceremony during WSDM 2025 conference, March 10‑14, 2025  

##  Dataset & Task

- Data comes from **Chatbot Arena** (formerly LMSYS) interactions. Each instance involves a user prompt, and two candidate responses from different chatbots. A judge (human) indicates which response they prefer.  
- The task is to build a model (auto‑rater) that can predict, given prompt + two responses, which response the user will prefer.

##  Evaluation

- Models are evaluated by how well they match the human preference judgments.  
- Being multilingual, performance across different languages is expected to matter.

##  How to Get Started

1. Download the dataset from the competition page on Kaggle.  
2. Explore data formats and splits (train, test, etc.)  
3. Preprocess text, including multilingual support: tokenization, normalization depending on languages.  
4. Choose or build a model architecture for preference prediction. Options may include transformer‑based models that are multilingual.  
5. Train, validate (e.g. via cross‑validation), and test.  
6. Submit predictions following the competition’s submission format.

## Useful Resources

- [Competition page on Kaggle](https://www.kaggle.com/competitions/wsdm-cup-multilingual-chatbot-arena)  
- [WSDM Conference page](https://www.wsdm-conference.org/2025/2025-wsdm-cup-lmsys-multilingual-chatbot-arena)  
- [Hugging Face dataset mirror](https://huggingface.co/datasets/baohao/WSDM-Cup-Multilingual-Chatbot-Arena/tree/8606715ac4044caf1ea7088737645d2223bf5223)  

##  Considerations & Tips

- Be mindful of **language imbalance**. Some languages may have fewer examples, which can affect performance.  
- Preference prediction models may suffer from **biases** (e.g. order bias, verbosity bias) — consider them in training / evaluation.  
- Evaluation metric details are given in competition rules; check edge cases.  

