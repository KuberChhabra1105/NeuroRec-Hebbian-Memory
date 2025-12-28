# NeuroRec: Biologically Inspired Hebbian Recommender System 

### Hackathon Project Submission

## Overview
**NeuroRec** is a novel approach to recommender systems that moves away from traditional matrix factorization and deep learning backpropagation. Instead, it utilizes **Hebbian Learning Principles** ("Neurons that fire together, wire together") to create a dynamic, sparse memory graph of user preferences.

This system simulates a neural network where:
* **Users** are represented as neurons.
* **Co-interactions** (watching the same movie) create synaptic connections.
* **Repeated activity** strengthens these connections, forming a "memory" of shared preferences.

## 🚀 Key Features
* **Biological Plausibility:** Mimics how the human brain strengthens synaptic pathways.
* **Energy Efficiency:** No expensive backpropagation or GPU-heavy training loops.
* **Sparse Graph Topology:** Visualizes how user communities emerge naturally over time.
* **Dynamic Learning:** The system learns in real-time as new data streams in.



*Figure 1: Emergent community structure among users based on Hebbian weight strengthening.*

## 🛠️ Tech Stack
* **Python 3.10+**
* **NetworkX:** For graph topology and visualization.
* **Pandas:** For handling the MovieLens 100k dataset.
* **Matplotlib:** For plotting activation density and synaptic weights.

## 💻 How to Run
You can run this project directly in Google Colab without any local setup.

1.  Open the notebook `BDH-Hebbian-Memory.ipynb` in this repository.
2.  Click the "Open in Colab" button (or download and upload to Colab).
3.  **Run All Cells**: The notebook automatically downloads the MovieLens dataset, so no manual file handling is required.

## 🔮 Future Scope
While current sparse memory graphs require sufficient exposure time to form strong clusters, future iterations will include:
* **Hybrid Initialization:** Pre-weighting synapses using item popularity.
* **Decay Mechanisms:** Implementing "forgetting" curves to handle drifting user preferences over time.

## Team - Data Donz
* Ashutosh Sharma (leader)
* Kuber Chhabra
* Manav Bhatt
