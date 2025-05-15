# 👁️ Emotion & Attention Analysis via Pupil Diameter Trends

This repository contains the code, dataset, and results from our project **"Spatial Emotion Detection using Pupil Diameter Analysis"**, which explores the relationship between **pupil dilation**, **emotions (Happy, Angry, Neutral)**, and **attentional cueing** using a modified **Posner cueing paradigm**.

---

## 🧪 Problem Statement

The objective of this study is to investigate how **emotions and spatial attention (via cues)** influence pupil diameter and reaction time during an emotion recognition task. Specifically, we examine the differences in pupil dilation and response latency across:

- **Three emotions**: Happy (E1), Angry (E2), and Neutral (E3)
- **Cueing conditions**: Valid (cued) vs Invalid (uncued)
- **Eccentricities**: 0, ±4, ±8, ±16

---



## 🧰 Tools & Libraries Used

- **Python 3.9+**
- `pandas` for data handling
- `matplotlib` & `seaborn` for plotting
- `numpy` for numerical operations

---

## 📊 Key Features of the Project

### ✅ Data Cleaning & Preprocessing

- Dropped fixation phase (first 86 columns of pupil diameter)
- Removed unnecessary columns (like stimulus image names)
- Merged sub-blocks for each emotion
- Separate processing for **cued** and **uncued** conditions

### 📈 Analysis Performed

#### 1. **Pupil Diameter Trends**
- Time-series plots of pupil dilation across all participants
- Plotted for all emotions & eccentricities in both **cued** and **uncued** cases
- Focused on post-stimulus interval: **1800 ms to 2600 ms**

#### 2. **Reaction Time Analysis**
- Median reaction times per participant per condition
- Comparative box plots across emotions & eccentricities
- Observed faster RTs for cued trials; slower & noisier for uncued

#### 3. **Supporting Analysis**
- Rate of change in pupil diameter over time
- Insights into constriction/dilation phases across eccentricities

---

## 🔍 Observations & Inferences

- **Cued trials** resulted in faster reaction times compared to uncued ones, consistent with Posner’s cueing paradigm.
- **Neutral faces** caused the **largest pupil dilation**, indicating higher attentional effort.
- **Happy faces** had the **lowest RTs and smallest dilation**, possibly due to positive valence and easier recognition.
- **Higher eccentricities** led to **greater pupil dilation**, suggesting increased cognitive load for peripheral processing.

---

## 📑 Report

For complete explanations, figures, and citations, refer to the full report:
📄 [`D3-6.pdf`](./D3-6.pdf)

---

## 🧠 References

- Henderson, R. R., Bradley, M. M., & Lang, P. J. (2018). *Emotional imagery and pupil diameter*. Psychophysiology, 55(6), e13050. https://doi.org/10.1111/psyp.13050
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [Pandas API](https://pandas.pydata.org/docs/reference/index.html)

---

## 📬 Contact

For any questions or clarifications, feel free to raise an issue in this repository.

---



