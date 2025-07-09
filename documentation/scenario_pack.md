# 🩺 Asthma Medication Reminder and Emergency Guidance Chatbot Scenario Package

---

## 📖 Scenario Background

In Halifax, Nova Scotia, asthma is a common chronic respiratory condition requiring daily management and quick response to worsening symptoms. Patients often forget to take maintenance inhalers, misuse rescue inhalers, or fail to recognize early warning signs of severe attacks. Nova Scotia Health, the Canadian Lung Association, and other organizations provide clear action plans and educational resources for asthma management.

This scenario asks students to use the **Ollama + AnythingLLM stack**, combined with locally available, authoritative health education materials, to design a chatbot for **Asthma Medication Reminder and Emergency Guidance**.

---

## 🎯 Scenario Goals

- Help users remember and correctly use maintenance and rescue medications  
- Guide users on recognizing early warning signs and using action plans  
- Clearly communicate that the chatbot does **not** provide professional medical diagnoses  

---

## 🗂 Recommended Knowledge Base Materials

Students should collect and organize retrievable, structured local health education materials to serve as their RAG (Retrieval-Augmented Generation) knowledge base. Recommended sources include:

- Canadian Lung Association – Asthma Action Plan Templates  
- Nova Scotia Health – Patient Inhaler Usage Guides  
- Asthma Canada – Early Warning Sign Education  
- Home Environment Control Tips for Asthma Management  
- Any relevant local clinic or public health materials  

> 📌 **Requirement**: Upload as PDF, Markdown, or plain text, using general, consistent file names such as:
```
knowledge_document_1.pdf
knowledge_document_2.md
knowledge_document_3.txt
```

---

## 🎯 Suggested User Questions for Testing

Your final system must be able to answer these scenario questions using your uploaded knowledge base materials:

- **Question 1:** "What should I watch for that tells me an asthma attack is starting?"  
- **Question 2:** "How can I remember to take my maintenance inhaler every day?"

---

## 📦 Suggested GitHub Repository Structure

Recommended folder structure for all project deliverables:

```
📂 /cold-flu-chatbot 
├─ knowledge_base/ 
│  ├─ knowledge_document_1.pdf 
│  ├─ knowledge_document_2.md 
│  └─ knowledge_document_3.txt 
├─ prompt/ 
│  └─ system_prompt.txt 
├─ documentation/ 
│  ├─ scenario_pack.md (Provided) 
│  └─ use_case_description.md 
├─ demo/ 
│  ├─ demo_video.mp4 
│  └─ chat_transcript.txt 
└─ README.md 
```

---

## 📑 Deliverables

- **Knowledge Base**
  - Include all documents actually used in AnythingLLM
  - Must be clearly structured and named using the general format above

- **System Prompt**
  - Defines the chatbot role, tone, scope, and ethical disclaimers

- **Use Case Description**
  - A clear document identifying user pain points and success criteria

- **Demo Materials**
  - Screen recording or video showing chatbot responses to the core scenario questions
  - Chat transcript

- **README.md**
  - Brief project overview
  - Local deployment/testing instructions
  - Author(s) and date

---

## ⚠ Important Notes

- All materials must be uploaded to a **public or private GitHub Repository** for review  
- The project is for **educational research use only** and must **not** be used for real diagnosis or treatment  
- The chatbot `README.md` file must prominently display a **“Not Medical Diagnosis” disclaimer**  
