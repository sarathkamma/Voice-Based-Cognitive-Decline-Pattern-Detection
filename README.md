# Voice-Based-Cognitive-Decline-Pattern-Detection

# Cognitive Decline Detection via Voice

This project uses voice-based speech features and unsupervised ML (KMeans) to detect potential signs of cognitive decline.

## Features Extracted
- Duration
- Tempo
- Pitch Variability
- Word Count
- Pauses
- Hesitations
- Speech Rate


- 🟢 **Low Risk** – Likely fluent, consistent speech
- 🔴 **High Risk** – Signs of hesitations, pitch variability, slower pace

---

## Project Structure

---

##  Features Extracted

- **Audio-based**
  - `duration`
  - `tempo`
  - `pitch_variability`
- **Speech pattern**
  - `word_count`
  - `pauses`
  - `hesitations`
  - `speech_rate`

---

##  Model Details

- **Algorithm**: `KMeans` (unsupervised clustering)
- **Scaling**: Standardized with `StandardScaler`
- **Dimensionality Reduction**: PCA used for visualization only (not in prediction)
- **Clusters**:
  - `Cluster 0`: 🟢 Low Risk
  - `Cluster 1`: 🔴 High Risk

---
## How It Works &Model Details
1. Audio is transcribed and features extracted
2. Features are normalized and clustered using KMeans
3. Based on the cluster, a risk score is assigned (0 = low risk, 1 = high risk)
