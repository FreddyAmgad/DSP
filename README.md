# Neural Signal Spike Clustering

This project implements a signal processing pipeline for detecting and clustering neural spike activity from raw electrophysiological data. It extracts meaningful features from spike waveforms and applies K-Means clustering to group similar spikes, providing visual insights into neural activity.

## ⚙️ Features

- **Signal Parsing**: Reads and separates raw neural signals from a structured data file.
- **Spike Detection**: Identifies potential spike peaks based on dynamic thresholding.
- **Feature Extraction**: Extracts statistical features such as:
  - Standard deviation in a signal window
  - Maximum difference between successive samples
- **Clustering**: Applies K-Means to group spike events into clusters representing different neurons.
- **Visualization**:
  - Scatter plot of features colored by cluster
  - Signal plot with clustered spike markers
  - Average spike waveform per cluster

## 📁 Input
- A `.txt` file containing two tab-separated columns of neural signal data.

## 📤 Output
- Multiple plots:
  - Feature space visualization
  - Signal with detected and clustered peaks
  - Average spike waveform per cluster

## 🧠 Dependencies
- `pandas`
- `numpy`
- `matplotlib`
- `sklearn`

## 👨‍💻 Contributors
- Freddy Amgad  
- Omar Elawalily  
- Sief Elshabashery
