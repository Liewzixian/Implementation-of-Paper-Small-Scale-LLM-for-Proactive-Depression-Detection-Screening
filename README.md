# Implementation of Small-Scale PHQ-Incorporated Depression Detection Conversational Agent

This repository contains the implementation of the proposed **Conversational Agent for Depression Detection**, built on top of the **DAIC dataset** (not included in this repository). The system integrates data augmentation, fine-tuning, and evaluation pipelines to create a chatbot capable of detecting depression indicators using conversational cues and PHQ (Patient Health Questionnaire)-based labeling.

---

## 📂 Repository Structure

* **`Classification_Evaluation/`**
  Scripts to evaluate parsed labels from the classification module output.

* **`Conversational_Depression_Detection_Agent/`**
  Application chatbot code for the proposed system.

* **`Data_Augmentation_Pipeline_Deepseek_API/`**
  Data augmentation pipeline using the DAIC dataset with **DeepSeek API** via prompt engineering.

* **`Qwen_Lora_Finetuning/`**
  Fine-tuning code for the augmented dataset using **LoRA** with Qwen models.

* **`Response_Evaluation/`**
  Scripts to measure lexical and semantic alignment for outputs from the fine-tuned model.

* **`Model/`**
  Contains links to **weight files of the fine-tuned model variants** used in the paper.

---

## ⚠️ Dataset Availability

This project is based on the **DAIC dataset**, which is **not publicly shareable here**.
To use this system:

* Request access to the DAIC dataset from the official community, **or**
* Replace it with a similar dataset of clinical or conversational depression detection.

---

## Workflow Overview

1. **Data Augmentation** → Enhance DAIC dataset with DeepSeek API.
2. **Fine-tuning** → Train Qwen models with LoRA on the augmented dataset.
3. **Classification & Evaluation** → Label parsing and accuracy evaluation.
4. **Conversational Agent** → Chatbot implementation for real-time depression detection.
5. **Response Evaluation** → Assess semantic and lexical alignment of chatbot responses.

---

## 🔗 Model Weights

Links to the fine-tuned model weights are provided in the **`Model/`** folder.
