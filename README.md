# corpus-thesis-vanbakel
# Elderly Suicide Media Corpus – South Korea and the Netherlands

This repository contains the qualitative media corpus used for the analysis of my bachelor thesis titled: **"Elderly Suicide in South Korea and the Netherlands: A comparative mixed-method analysis of socioeconomic predictors and media discourse"**.

## Overview

This corpus-based dataset includes stratified samples of newspaper articles from **South Korea** and **the Netherlands** between **2010 and 2025**, focusing on how elderly suicide is represented in national media. The corpora were used to perform a linguistic and thematic analysis using **Sketch Engine**.

## Contents

- `/netherlands/`:  
  48 Dutch newspaper articles from *De Telegraaf*, *Algemeen Dagblad*, and *De Volkskrant*, tagged by year and source (e.g., `2012AD.txt` for Algemeen Dagblad 2012).
  
- `/south_korea/`:  
  48 South Korean newspaper articles from *동아일보 (Dong-A Ilbo)*, *중앙일보 (JoongAng Ilbo)*, and *한국일보 (Hankook Ilbo)*, tagged by year and source (e.g., `2013동.txt` for Dong-A Ilbo 2013).

## Methodology

- **Sampling**: Stratified sampling was used to ensure balanced representation across sources and years (2010–2025).
- **Search Terms**: 
  - Korean corpus: “노인 자살” (elderly suicide)
  - Dutch corpus: “ouderen zelfmoord” (elderly suicide)
- **Sources**:
  - South Korea: Articles retrieved from [BigKinds](https://www.bigkinds.or.kr/)
  - Netherlands: Articles retrieved from [Nexis Uni](https://www.lexisnexis.com)
- **Preprocessing**: Articles were converted to plain `.txt` format and cleaned using language-specific stopword lists for compatibility with Sketch Engine.
