
# Solaria-GPT 🧠🛠️
A Tailored ChatGPT for Usability Inspection

![Status](https://img.shields.io/badge/status-active-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![ChatGPT](https://img.shields.io/badge/based_on-ChatGPT-ff69b4)
![Version](https://img.shields.io/badge/version-1.0.0-yellow)
[![DOI](https://zenodo.org/badge/922763471.svg)](https://doi.org/10.5281/zenodo.15282435)

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

How to use Solaria-GPT?

1. **Access Solaria-GPT**: [https://chatgpt.com/g/g-gO0eGq3rN-solaria-gpt](https://chatgpt.com/g/g-gO0eGq3rN-solaria-gpt)
2. **Data Input**: Enter some input data
   - **Text**: description of some usability defect
   - **screenshot**: a screenshot of the software that you want to check for usability defects
   - **video**: a recording of a video interaction with the software that you want to check for usability defects
 3. **Processing**: Wait for the Solaria-GPT to process your input
 4. **Response**: Solaria-GPT will have the following response:
    - **For text**: the violated heuristic by the problem inserted
    - **For media (screenshot and video)**: the defect description, the location where the problem happens, and the violated heuristic  
---

## 🧠⚙️ Prompt Instructions
- 📜 **[Instructional Prompt for Solaria-GPT](https://github.com/lennonchaves/Solaria-GPT/tree/main/prompt)**
- 📘 **[Nielsen's Heuristics File with Examples](https://github.com/lennonchaves/Solaria-GPT/tree/main/description)**

---
# Experiments and Comparison with Other Tools 

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

## Execution
- Use the dataset available
- Use the prompt strategies
- TOOL must be: Solaria-GPT, Qween, DeepSeek, Claude, and Gemini.

### Textual Validation
1. Open the [TOOL]
2. Type the prompt strategy for textual input
3. Add the defect from the *defects database*

### Screenshot Validation
1. Open the [TOOL]
2. Type the prompt strategy for screenshot input
3. Attach the screenshot from the *screenshot collection*

### Video Validation
1. Open the [TOOL]
2. Type the prompt strategy for video input
3. Attach the video from the *video samples*

---

## 📊 Output & Results

- 📂 [heuristic_classification_results.xlsx](https://github.com/lennonchaves/Solaria-GPT/blob/main/results/heuristic_classification_results.xlsx) — Spreadsheet with classification outcomes
- 📂 [screenshot_defect_detection.xlsx](https://github.com/lennonchaves/Solaria-GPT/blob/main/results/screenshot_defect_detection.xlsx) — Results from screenshot analysis
- 📂 [video_defect_detection.xlsx](https://github.com/lennonchaves/Solaria-GPT/blob/main/results/video_defect_detection.xlsx) — Results from video analysis

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---
## 📝Paper Reference

Chaves, L., Lima, M., & Conte, T. (2025). _Solaria-GPT: A Tailored ChatGPT Tool for Usability Inspection_. In Proceedings of the XXXIX Brazilian Symposium on Software Engineering (SBES 25). Recife, PE, Brazil, 2025. [Pre-print](https://github.com/lennonchaves/Solaria-GPT/blob/main/2025_SBES_Tool_Paper.pdf).


## 👥 Authors

This project was developed by:

- **Lennon Correa Chaves** – [lennon@icomp.ufam.edu.br](mailto:lennon@icomp.ufam.edu.br)
- **Márcia Sampaio Lima** – [msllima@uea.edu.br](mailto:msllima@uea.edu.br)
- **Tayana Uchoa Conte** – [tayana@icomp.ufam.edu.br](mailto:tayana@icomp.ufam.edu.br)

## 🏛️ Institutions:

- Institute of Computing - Federal University of Amazonas - UFAM. 🔗 [https://icomp.ufam.edu.br/](https://icomp.ufam.edu.br/)
- State University of Amazonas - UEA. 🔗[https://www.uea.edu.br/](https://www.uea.edu.br/)
- USES Research Group. 🔗[https://uses.icomp.ufam.edu.br/](https://uses.icomp.ufam.edu.br/)

## 📚 Citation

If you use **Solaria-GPT** in your research or project, please cite it as follows:

```bibtex
@misc{solariaGPT,
  author       = {Lennon Chaves, Marcia Lima, Tayana Conte},
  title        = {{Solaria-GPT: A Usability Inspection Tool}},
  year         = {2025},
  howpublished = {\url{https://github.com/lennonchaves/Solaria-GPT}},
  doi = {10.5281/zenodo.15282435}
}
```

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request for suggestions and improvements.


