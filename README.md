# AI Healthcare Assistant using Hugging Face & Prompt Engineering

## Overview

This project implements an AI-powered Healthcare Assistant using the Hugging Face Transformers library and Prompt Engineering techniques. The assistant is designed to answer medical questions, summarize clinical notes, generate structured outputs, and demonstrate various prompt engineering strategies while reducing hallucinations and improving response consistency.

The project was developed as part of a scenario-based assessment for a Generative AI Engineer role at MediAssist AI Pvt. Ltd.

> **Disclaimer:** This project is intended for educational purposes only and does not provide medical diagnosis or treatment.

---

## Features

- Interactive AI Healthcare Chatbot
- Hugging Face Transformers Integration
- Instruction-Tuned Language Model
- Medical Question Answering
- Prompt Engineering Techniques
- Few-Shot Prompting
- Chain-of-Thought Prompt Design
- Structured JSON Output Generation
- Model Comparison
- Prompt Optimization
- Multi-Role Prompt Template (Doctor, Nurse, Medical Student, Patient)

---

## Technologies Used

- Python
- Hugging Face Transformers
- PyTorch
- Google Colab
- Jupyter Notebook

---

## Model Used

**Model Name**

```
TinyLlama/TinyLlama-1.1B-Chat-v1.0
```

### Why TinyLlama?

- Lightweight and efficient
- Instruction-tuned for conversational tasks
- Suitable for educational projects
- Runs smoothly on Google Colab
- Low computational requirements

---

## Project Structure

```
AI_Healthcare_Assistant/
│
├── notebook/
│   └── AI_Healthcare_Assistant.ipynb
│
├── screenshots/
│   ├── chatbot_demo1.png
│   ├── chatbot_demo2.png
│   └── chatbot_demo3.png
│
├── report/
│   └── AI_Healthcare_Assistant_Report.pdf
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/AI_Healthcare_Assistant.git
```

### Navigate to the Project

```bash
cd AI_Healthcare_Assistant
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Running the Project

Open the notebook:

```
notebook/AI_Healthcare_Assistant.ipynb
```

Run all cells sequentially.

The chatbot will load the TinyLlama model and allow users to enter medical queries interactively.

Example:

```
User:
Patient has fever for three days.

Assistant:
Possible causes include viral infections, influenza, or other respiratory illnesses. Consult a healthcare professional for proper diagnosis and treatment.
```

---

## Prompt Engineering Tasks

### Task 1
Hugging Face chatbot implementation using:
- AutoTokenizer
- AutoModelForCausalLM
- Transformers Pipeline

### Task 2
Prompt Engineering using:
- Role Prompting
- Context
- Constraints
- Output Formatting

### Task 3
Few-Shot Prompting for converting clinical notes into structured summaries.

### Task 4
Chain-of-Thought Prompt Design for clinical reasoning while keeping internal reasoning hidden.

### Task 5
Structured JSON output generation.

### Task 6
Comparison between TinyLlama and Qwen2.5-3B-Instruct.

### Task 7
Prompt optimization to reduce hallucinations and improve response quality.

### Bonus Challenge
Role-based prompt template supporting:
- Doctor
- Nurse
- Medical Student
- Patient

---

## Example JSON Output

```json
{
  "disease": "Possible Respiratory Infection",
  "symptoms": [
    "Fever",
    "Dry Cough",
    "Sore Throat"
  ],
  "risk_level": "High",
  "recommendation": "Seek immediate medical evaluation."
}
```

---

## Learning Outcomes

- Hugging Face Transformers
- Instruction-Tuned Language Models
- Prompt Engineering
- Role Prompting
- Few-Shot Prompting
- Structured Output Generation
- Prompt Optimization
- AI Chatbot Development

---

## Limitations

- Responses depend on the capabilities of the selected language model.
- The assistant may generate incorrect or incomplete medical information.
- It is intended only for educational and demonstration purposes.
- It should not be used for real-world medical diagnosis or treatment.

---

## Future Improvements

- Integrate Retrieval-Augmented Generation (RAG)
- Support multiple Hugging Face models dynamically
- Add voice-based interaction
- Deploy using FastAPI
- Develop a web interface with Streamlit or React
- Integrate electronic health record (EHR) support

---

## Requirements

- Python 3.10+
- transformers
- torch
- accelerate
- sentencepiece

---

## Author

Developed as part of a Generative AI and Prompt Engineering assessment using Hugging Face Transformers.
