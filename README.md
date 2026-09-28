# Insect Immunity AI (`insect-ai`)

An interactive, web-based dashboard and AI analysis tool that models and predicts how climate change—specifically heat stress, cold stress, and elevated CO₂ levels—impacts insect immune gene networks.

---

## 📌 Overview

Insect immune systems react dynamically to changing environmental factors. Traditional studies typically focus on single species exposed to single stressors. **Insect Immunity AI** leverages multi-modal data (combining **epigenetic** chemical switches and **transcriptomic** gene expression) across **6 insect orders** to map and predict immune response changes on a global scale.

---

## Key Features

- **Multi-Modal Data Integration**: Combines epigenetic and transcriptomic data to evaluate gene activity.
- **Cross-Species Analysis**: Evaluates data across 6 different insect orders (e.g., bees, mosquitoes, butterflies, locusts, silkworms, planthoppers).
- **Multi-Condition Environmental Modeling**: Assesses 5 distinct conditions:
  - Control (25°C)
  - Heat Stress (35°C)
  - Cold Stress (15°C)
  - Ambient CO₂ (400 ppm)
  - Elevated CO₂ (800 ppm)
- **Deep Learning Predictions**: Uses Graph Neural Networks (GNNs) and Transformer models to predict active genes and classify environmental conditions.
- **Master Switch Discovery**: Identifies key master regulator genes conserved across species.
- **In-Browser Interactive Dashboard**: Run and visualize model comparisons directly from your web browser with zero setup.

---

## 📊 Key Results & Benchmarks

| Feature / Metric | Traditional Linear Models | Our AI Framework (`insect-ai`) |
| :--- | :--- | :--- |
| **Species Scope** | Single species | **6 Insect Orders** |
| **Data Types** | Gene expression only | **Epigenetic + Transcriptomic** |
| **Gene Activity Error (MSE)** | 0.29 | **0.11** *(62% lower error)* |
| **Environment Classification Accuracy** | ~60% | **85%** *(+25% improvement)* |
| **Master Regulator Hubs Found** | None | **24 Hubs** *(10 conserved across all orders)* |
| **Interactive Demo** | No | **Yes (In-browser JavaScript)** |

---

## 🚀 How to Run locally

Since the main dashboard (`index.html`) runs entirely client-side in the browser, no installation or backend setup is required!

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/insect-ai.git](https://github.com/YOUR_USERNAME/insect-ai.git)
   cd insect-ai
