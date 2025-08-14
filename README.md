# MediAI
# 🩺 Medical Prescription App

A modern *AI-powered Medical Prescription Management Web App* built with *Next.js, **TypeScript, and **Tailwind CSS, integrated with **IBM Granite AI* for intelligent prescription analysis.  

This application helps doctors, pharmacists, and patients manage prescriptions, check drug interactions, and maintain secure medical records.

---

## 🚀 Features

- *📄 Prescription Upload & Analysis* – Upload prescription text for AI-based analysis.  
- *💊 Drug Extraction (IBM Granite AI)* – Extracts drug names, dosage, and frequency with high accuracy.  
- *⚠ Drug Interaction Checking (IBM Granite AI)* – Identifies possible harmful drug interactions.  
- *📱 Responsive UI* – Optimized for mobile, tablet, and desktop devices.   
- *✅ Form Validation* – Type-safe validation using react-hook-form + zod.  

---

## 🛠 Tech Stack

| Category          | Technology |
|-------------------|------------|
| Framework         | [Next.js 15](https://nextjs.org/) |
| Language          | [TypeScript](https://www.typescriptlang.org/) |
| Styling           | [Tailwind CSS](https://tailwindcss.com/) + Tailwind Merge |
| UI Components     | [Radix UI](https://www.radix-ui.com/) |
| Forms & Validation| [React Hook Form](https://react-hook-form.com/), [Zod](https://zod.dev/) |
| Icons             | [Lucide React](https://lucide.dev/) |
| AI Models         | [IBM Granite AI](https://huggingface.co/ibm-granite) via Hugging Face API |
| Charts            | [Recharts](https://recharts.org/) |

---

## 🤖 AI-Powered Features

### 1. *Drug Extraction Tool*
- Function: extractDrugsWithGranite(prescriptionText)
- Uses *IBM Granite 3B Code Instruct* to extract:
  - Drug names
  - Dosage
  - Frequency
  - Confidence score  
- API Endpoint:  
https://api-inference.huggingface.co/models/ibm-granite/granite-3b-code-instruct


### 2. *Drug Interaction Analysis Tool*
- Function: findDrugInteractionsWithGranite(drugs)
- Detects potential drug-to-drug interactions with details about:
- Interaction severity
- Interaction type
- Uses the same IBM Granite AI endpoint.

---
Screenshots:
![Alt text](https://github.com/namrathackolur/MediAI/blob/c7fe378244934d4ac2acb9df096f826a36398134/1.jpg)
![Alt text](https://github.com/namrathackolur/MediAI/blob/c7fe378244934d4ac2acb9df096f826a36398134/2.jpg)
![Alt text](https://github.com/namrathackolur/MediAI/blob/c7fe378244934d4ac2acb9df096f826a36398134/3.jpg)
![Alt text](https://github.com/namrathackolur/MediAI/blob/c7fe378244934d4ac2acb9df096f826a36398134/4.jpg)
![Alt text](https://github.com/namrathackolur/MediAI/blob/c7fe378244934d4ac2acb9df096f826a36398134/5.jpg)
![Alt text](https://github.com/namrathackolur/MediAI/blob/c7fe378244934d4ac2acb9df096f826a36398134/6.jpg)
![Alt text](https://github.com/namrathackolur/MediAI/blob/c7fe378244934d4ac2acb9df096f826a36398134/7.jpg)
