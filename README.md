
# Solaria-GPT 🧠🛠️
A Tailored ChatGPT for Usability Inspection

![Status](https://img.shields.io/badge/status-active-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![ChatGPT](https://img.shields.io/badge/based_on-ChatGPT-ff69b4)
![Version](https://img.shields.io/badge/version-1.0.0-yellow)

**Solaria-GPT** is an AI-driven tool designed to assist in **usability inspection** by detecting defects and classifying heuristic violations. Built on top of ChatGPT, the system supports two types of input formats:

- 📝 **Text Input** — A textual description of a usability defect.
- 🖼️ **Media Input** — A screenshot of the system interface or a video showcasing user interaction/navigation.

---

## 🔧 How to Create a Tailored ChatGPT

### ✅ Prerequisites

- Active **ChatGPT Plus** subscription.

### 🧭 Step-by-Step Guide

1. Access the **[Explore GPTs](https://chat.openai.com/gpts)** section.
2. Click on the **"Create"** button.
3. Use the **"Create"** tab to configure your GPT via conversational prompts.
4. Use the **"Configure"** tab to fill in model details and capabilities.
   - **Name**: "Solaria-GPT"
   - **Description**: "Solaria-GPT is an assistant that detects usability issues and classifies them according to Nielsen's heuristics. To use it, provide a textual description of the problem or a screenshot/video of the design to be evaluated."
   - **Instructions**: Copy and Paste the [Instructional Prompt for Solaria-GPT](https://github.com/lennonchaves/Solaria-GPT/tree/main/prompt) in the field.
   - **Conversation Startes**: Copy and Paste the following icebreakers:
     ```
     Which heuristic is violated in this defect description?
     ```
     ```
     What are the usability issues in the attached video?
     ```
     ```
     Analyze the attached video and perform a usability inspection.
     ```
     ```
     Are there any visible usability issues in the provided image?
     ```
   - **Knowledge**: Attach the file [Nielsen's Heuristics File with Examples](https://github.com/lennonchaves/Solaria-GPT/tree/main/description) in the field.
  
6. Share your tailored GPT with others by generating a public link.

We illustrated the process to tailor a ChatGPT below:
![chatgpt_all](https://github.com/user-attachments/assets/70dcc7a3-ebf4-43d6-b42d-b8e09b3db335)

---

## 🚀 Getting Started

- **Access Solaria-GPT**: [https://chatgpt.com/g/g-gO0eGq3rN-solaria-gpt](https://chatgpt.com/g/g-gO0eGq3rN-solaria-gpt)

---

## 🧠⚙️ Prompt Instructions
- 📜 **[Instructional Prompt for Solaria-GPT](https://github.com/lennonchaves/Solaria-GPT/tree/main/prompt)**
- 📘 **[Nielsen's Heuristics File with Examples](https://github.com/lennonchaves/Solaria-GPT/tree/main/description)**

---

## 📦 Datasets

- 📁 **[Defect Database](https://github.com/lennonchaves/Solaria-GPT/tree/main/dataset)**
- 🖼️ **[Screenshot Collection](https://drive.google.com/file/d/18prJVevaRMQg9G-25ugWOvoMoTxM3dkh/view?usp=sharing)**
- 🎥 **[Video Samples](https://drive.google.com/file/d/1dt35cZ5rBh7wQCyBDuLAqMrLjWEXnhl6/view?usp=sharing)**

---

## 🤖⚙️ Prompt Strategies
- 📑 **Prompt Examples Used with Solaria-GPT**:
  - **Text**:  
    ```
    Which heuristic is violated in the following defect.
    ```
  - **Screenshot**:  
    ```
    Perform a usability inspection of the attached screen.
    ```
  - **Video**:  
    ```
    Analyze the attached video and perform a usability inspection.
    ```

---

## 📊 Output & Results

- 📂 [heuristic_classification_results.xlsx](https://github.com/lennonchaves/Solaria-GPT/blob/main/results/heuristic_classification_results.xlsx) — Spreadsheet with classification outcomes
- 📂 [screenshot_defect_detection.xlsx](https://github.com/lennonchaves/Solaria-GPT/blob/main/results/screenshot_defect_detection.xlsx) — Results from screenshot analysis
- 📂 [video_defect_detection.xlsx](https://github.com/lennonchaves/Solaria-GPT/blob/main/results/video_defect_detection.xlsx) — Results from video analysis

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---


## 👥 Authors

This project was developed by:

- **Lennon Correa Chaves** – [lennon@icomp.ufam.edu.br](mailto:lennon@icomp.ufam.edu.br)
- **Márcia Sampaio Lima** – [msllima@uea.edu.br](mailto:msllima@uea.edu.br)
- **Tayana Uchoa Conte** – [tayana@icomp.ufam.edu.br](mailto:tayana@icomp.ufam.edu.br)

## 🏛️ Institutions:

- Institute of Computing - Federal University of Amazonas - UFAM. 🔗 [https://icomp.ufam.edu.br/](https://icomp.ufam.edu.br/)
- State University of Amazonas - UEA. 🔗[https://www.uea.edu.br/](https://www.uea.edu.br/)
- USES Research Group. 🔗[https://uses.icomp.ufam.edu.br/](https://uses.icomp.ufam.edu.br/)

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request for suggestions and improvements.


