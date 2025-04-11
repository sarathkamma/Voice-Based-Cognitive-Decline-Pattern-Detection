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

## How It Works
1. Audio is transcribed and features extracted
2. Features are normalized and clustered using KMeans
3. Based on the cluster, a risk score is assigned (0 = low risk, 1 = high risk)
