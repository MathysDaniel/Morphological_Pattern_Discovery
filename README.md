# 🎵 Musical Pattern Discovery through Morphological Morphology and Structure Representation

This project focuses on the **pattern discovery** in symbolic music data, providing insight into the **underlying metric organization** of musical pieces.  
A **new algorithm** has been developed based on **mathematical morphology** (a framework originally designed for image processing) and adapted here for **symbolic music representation**.  
By applying morphological operators (such as **erosion**) to MIDI data, the system can extract **repetitive musical patterns occurring at regular time intervals**, offering a computational approach to exploring rhythmic regularities.

This repository aims to make the developed algorithm and analysis tools **fully available for transparency and reproducibility of our results**.

---

## 👥 Team

- **Mathys Daniel** (Author) – LIP6, Sorbonne University & IRMA, University of Strasbourg : mathys.daniel@ircam.fr
- **Paul Lascabettes** – IRMA, University of Strasbourg  : lascabettes@math.unistra.fr
- **Moreno Andreatta** – IRMA, University of Strasbourg  : andreatta@math.unistra.fr
- **Isabelle Bloch** – LIP6, Sorbonne University  : isabelle.bloch@sorbonne-universite.fr

This study is based on the work developed by **Paul Lascabettes** in his PhD thesis:  
➡️ [https://hal.science/tel-04480227](https://hal.science/tel-04480227)

---

## 🧠 Scientific Context

This work bridges mathematical morphology and symbolic music analysis.
The algorithm detects repetitive patterns occuring at regular intervals within point sets representing musical events (onsets, pitches) to prodive informations about the metric structure through morphological operations such as erosion and dilation .

This approach enables:

    The discovery of time-regular repetitive patterns
    
    The extraction of pattern lengths that provide information about local rhythmic regularities
    
    The exploration of metric organization and polymetric phenomena in complex musical contexts

---

## 🧩 Repository Structure

The repository is organized into two main parts:

- **`Analyze_pieces_of_music/`**  
  This folder provides a **user-friendly version** of the algorithm.  
  It allows users to analyze any musical piece (as long as a MIDI version is available) using the pattern discovery algorithm.

- **`Our_Work/`**  
  This folder contains the **complete research code** used to generate the results presented in our study.  
  It includes additional **statistical and analytical tools**, and aims to support **reproducibility** of the research results.

---

## 🧭 Usage Guide

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/Rhythmic_Signature_Recognition.git
   cd Rhythmic_Signature_Recognition

2. **Install the dependencies**
    ```bash
    pip install -r requirements.txt

3. **Run the notebook**

     Open Analyze_pieces_of_music/Metric_recognition.ipynb in Jupyter Notebook.

     Place your MIDI files inside a data/ folder (create one if needed).

     Follow the notebook instructions to analyze the piece.


## 🪪 License

This repository is released under the MIT License.
You are free to use and modify the code for academic or research purposes, with appropriate citation.
