# Humanizing Technology: Comparing User Experience and Social Perceptions Across Everyday Devices and Applications

## 📄 Project Description
This repository contains the research, data, and analysis for our study on **user experience (UX)** and **social perception** across a diverse range of everyday technologies.  
We investigate how **pragmatic and hedonic qualities** (measured via *AttrakDiff*) relate to perceptions of **warmth and competence** (from the *Stereotype Content Model*), and how these jointly influence **user engagement intentions**.

## 🎯 Objectives
- Compare UX and social perception metrics across eight product types: ChatGPT, Duolingo, Smartwatch, DB Navigator, Spotify, Airfryer, Laptop, and Robot Vacuum.
- Identify which UX and social perception dimensions most strongly predict engagement.
- Visualize product positioning using quadrant mapping and correlation heatmaps.

## 📊 Methodology
- **Design:** Within-subject survey for consistent cross-product comparisons.
- **Measures:**  
  - *AttrakDiff* (Pragmatic Quality, Hedonic Quality–Identity, Hedonic Quality–Stimulation, Attractiveness)  
  - *Stereotype Content Model* (Warmth, Competence)  
  - Engagement Intention (single-item measure)
- **Analysis:**  
  - Descriptive statistics  
  - Reliability analysis (Cronbach’s alpha)  
  - Pearson correlations with Holm corrections  
  - Mixed-effects modeling  
  - Visualizations (quadrant mapping, heatmaps)

## 📈 Key Findings
- **Attractiveness** is the strongest predictor of engagement.
- **Pragmatic Quality** aligns more with perceived **Competence**.
- **Hedonic Qualities** align more with perceived **Warmth**.
- AI tools and educational/entertainment apps show higher engagement than utilities/appliances.

## ⚙️ Installation & Usage

### 1. Clone the repository
```bash
git clone https://github.com/IrfanDanishRajput/hmi-research-project
cd hmi-research-paper
```

### 2. Set up a virtual environment
```bash
python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows
```

### 3. Install dependencies
Make sure you have Python 3.9+ installed. Then run:
```bash
pip install -r requirements.txt
```

### 4. Run the Jupyter Notebook
```bash
jupyter notebook
```
Open **analysis.ipynb** and run all cells to reproduce the analysis.

> **Note:** The notebook includes statistical analysis (correlations, mixed-effects models, visualizations). Ensure you have all required data files in the correct directories before running.

## 🤝 Contributing
Contributions are welcome! Please open an issue or submit a pull request for suggestions, corrections, or additional analyses.
