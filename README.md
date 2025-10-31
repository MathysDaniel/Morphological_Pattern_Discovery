# 🎵 Metric Recognition

This project aims to **detect the time signature of musical pieces** by using **pattern detection tools**.  
To achieve this, a **new algorithm** has been proposed based on **mathematical morphology**, a framework originally developed for image processing.  
By adapting morphological operators to symbolic music data, this approach enables the extraction of **repetitive musical patterns** and aims to do recognition of **metric structures** within MIDI representations.

This repository has two goals:
1. To make the developed algorithm accessible and reusable.
2. To provide the complete code and analysis tools used in this research for transparency and reproducibility.

---

## 👥 Team

- **Mathys Daniel** (Author) – LIP6, Sorbonne University & IRMA, University of Strasbourg : mathys.daniel@ircam.fr
- **Paul Lascabettes** – IRMA, University of Strasbourg  : paul.lascabettes@ircam.fr
- **Moreno Andreatta** – IRMA, University of Strasbourg  : andreatta@math.unistra.fr
- **Isabelle Bloch** – LIP6, Sorbonne University  : isabelle.bloch@sorbonne-universite.fr

This study is based on the work developed by **Paul Lascabettes** in his PhD thesis:  
➡️ [https://hal.science/tel-04480227](https://hal.science/tel-04480227)

---

## 🧩 Repository Structure

The repository is organized into two main parts:

- **`Analyze_pieces_of_music/`**  
  This folder provides a **user-friendly version** of the algorithm.  
  It allows users to analyze any musical piece (as long as a MIDI version is available) using the rhythmic signature recognition algorithm.

- **`Our_Work/`**  
  This folder contains the **complete research code** used to generate the results presented in our study.  
  It includes additional **statistical and analytical tools**, and aims to support **reproducibility** of the research results.

---

## 🧭 Usage Guide

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/Metric_Recognition.git
   cd Metric_Recognition

2. **Install the dependencies**
    ```bash
    pip install -r requirements.txt

3. **Run the notebook**

     Open Analyze_pieces_of_music/Metric_recognition.ipynb in Jupyter Notebook.

     Place your MIDI files inside a data/ folder (create one if needed).

     Follow the notebook instructions to analyze the piece.

## 🧠 Scientific Context

This work bridges mathematical morphology and symbolic music analysis.
The algorithm detects repetitive patterns and metric structures through morphological operations such as erosion and dilation applied to point sets representing musical events (onsets, pitches).

These mathematical tools allow for:

    The detection of recurring rhythmic or melodic structures.

    The estimation of local and global time signatures.

    The exploration of polymetric phenomena within complex compositions.

## 🪪 License

This repository is released under the MIT License.
You are free to use and modify the code for academic or research purposes, with appropriate citation.
