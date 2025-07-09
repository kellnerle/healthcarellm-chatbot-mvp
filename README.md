# README: Asthma Medication Reminder and Emergency Guidance Chatbot

---

**Not Medical Diagnosis Disclaimer**  
This chatbot is for educational and informational purposes only. It is not a substitute for professional medical advice, diagnosis, or treatment. Always consult your doctor or call emergency services (911) in the event of a medical emergency.

---

## Project Overview

This project is a locally-deployed healthcare chatbot MVP built using **Ollama** and **AnythingLLM**. It helps users in Halifax, Nova Scotia manage asthma by:

- Reminding users to take daily controller medications  
- Recognizing early signs of asthma attacks  
- Offering emergency guidance based on public education materials from the **Canadian Lung Association**, **Asthma Canada**, and **Nova Scotia Health**

> The chatbot does **not** store personal data, does **not** diagnose, and follows ethical safeguards suitable for offline use in research and prototyping.

---

## Local Deployment Instructions

1. **Install Ollama**: [https://ollama.com/](https://ollama.com/)
2. **Pull a supported model** (e.g., `deepseek r1 latest version`):  
   ```bash
   ollama pull deepseek latest version
   ```
3. **Install and configure AnythingLLM**: [https://docs.anythingllm.com/](https://docs.anythingllm.com/)
4. **Launch the AnythingLLM UI**, add your documents to the `knowledge_base` folder
5. **Upload** the `system_prompt.txt` file in the **Prompt** tab
6. **Connect** AnythingLLM to your local Ollama model
7. **Begin testing** the chatbot using sample queries

---

## Authors and Date

**Author**: Lance Kellner, MBAN Candidate  
**Date**: July 09, 2025  
