# 🎶 Polygondwanaland — Pattern Detection and Polymeter Analysis

## 🔍 What This Project Does

- Detects repetitive patterns at regular time intervals in a MIDI dataset using an original morphological approch
- Analyze them and provide informations about the evolution of the time signatures evolution of given pieces of music
- Provide visualization tools to observe those structures

---

This repository contains all the code developed for the **musical pattern and polymetrer analysis** of *Polygondwanaland* by **King Gizzard & the Lizard Wizard**.

It also includes a set of **original visualizations** of the internal rhythmic structure of a musical piece.

---

## ⚙️ Environment Requirements

> 🧠 **Important:**  
> This notebook is designed to work primarily with **Google Colab**. You can adapt it for local execution (as in the `Analyze_pieces_of_music/` directory), but the provided setup assumes a Colab environment.

---

## 📁 Setup Instructions (Google Colab)

1. Create a folder in your **Google Drive** named:
   ```
   Pattern_Detection
   ```

2. Inside that folder, upload your **MIDI datasets** — these are the source files used for analysis.

3. To analyze the *Polygondwanaland* album:
   - Download the dataset folder:
     ```
     Polygondwanaland_MIDI
     ```
     (available in this repository)
   - Place it inside a subfolder called:
     ```
     MIDI_Source
     ```
   - You can also store any other dataset of your choice in the same folder.

   **Example folder structure:**
   ```
   My Drive/
   └── Pattern_Detection/
       └── MIDI_Source/
           ├── Polygondwanaland_MIDI/
           └── Beatles_MIDI/
   ```

---

## 🎵 Dataset Sources

- **Polygondwanaland (King Gizzard & the Lizard Wizard)**  
  Created by [8-bit Escapades](https://8-bitescapades.bandcamp.com/album/polygondwanaland)

- **The Beatles MIDI Dataset**  
  From the PhD research of *Victoria Callet* (IRMA, University of Strasbourg):  
  https://math-musique.pages.math.unistra.fr/midi/pop-rock-midi.html

---


## 📦 Repository Structure (suggested)

```
.

├── Metric_Recognition_KingGizzard.ipynb
├── MIDI_Source/
│   └── Polygondwanaland_MIDI/
│   └── Beatles_10tracks/
```

---
