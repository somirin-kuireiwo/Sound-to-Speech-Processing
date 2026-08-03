# Sound to Speech Processing of Tangkhul Vowels(Acoustic Analysis of Tangkhul Vowels)

This project presents an acoustic analysis of Tangkhul vowels across five major dialect regions of Ukhrul District, Manipur: North, South, East, West, and Central (Ukhrul Town). The study focuses on examining regional variations in vowel pronunciation by extracting and analyzing acoustic features from speech recordings.

Speech recordings were manually segmented using Praat TextGrids, followed by formant extraction, normalization, statistical analysis, and visualization using Python. The project contributes to the documentation and preservation of the Tangkhul language by providing an acoustic profile of its vowel system.

---

## Objectives

- Analyze the acoustic properties of Tangkhul vowels across five regional dialects.
- Extract vowel formants (F1 and F2) from speech recordings.
- Compare vowel distributions between different dialect regions.
- Perform statistical analysis to identify regional differences.
- Visualize vowel spaces using normalized formant values.
  
---

## Features

- Speech segmentation using Praat TextGrids.
- Automatic extraction of vowel formants (F1 & F2).
- Lobanov normalization of formant values.
- Statistical analysis using ANOVA and Tukey HSD.
- Vowel space visualization.
- Comparative analysis across five Tangkhul dialect regions.
  
---

## Tech Stack

- Python
- Praat
- Statsmodels
- Parselmouth (Praat interface)
- NumPy
- Pandas
- Matplotlib

---

## Project Workflow

- Collected speech recordings from native Tangkhul speakers across five dialect regions: North, South, East, West, and Central (Ukhrul Town).
- Performed manual speech segmentation and vowel annotation using **Praat TextGrids**.
- Extracted the first and second formant frequencies (**F1** and **F2**) using **Python** and the **Parselmouth** library.
- Cleaned and organized the extracted acoustic data for further analysis.
- Applied **Lobanov normalization** to reduce speaker-specific variation in formant values.
- Conducted statistical analysis using **ANOVA** and **Tukey HSD** to compare vowel characteristics across regions.
- Generated vowel space plots and visualizations using **Matplotlib** to analyze and compare regional vowel distributions.
- Interpreted the results to study acoustic variations in the Tangkhul vowel system across the five dialect regions.

---


