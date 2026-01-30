# Dataset Materials

This folder contains tutorials and documentation for all neural datasets used in the workshop. Each dataset includes a Jupyter notebook with loading instructions, exploratory analyses, and project ideas.

## Available Datasets

### MC-Maze (Motor Cortex - Maze Navigation)

**Location**: `mc-maze/mc-maze-dataset.ipynb`

**Description**: Neural recordings from motor cortex while a non-human primate navigates a cursor through a maze.

**Key Features**:
- Primary motor cortex recordings
- Spatial navigation task
- Continuous behavioral data (position, velocity)

**Good for learning**:
- Movement decoding
- Trajectory prediction
- Spatial encoding
- Time-series analysis
- Population coding

---

### Monkey Fingers (Motor Control)

**Location**: `monkey-fingers/monkey-fingers-dataset.ipynb`

**Description**: Neural recordings during a 2-degree-of-freedom finger movement task in non-human primates.

**Key Features**:
- Motor cortex recordings
- Individual finger movements
- Finger kinematics measurements

**Good for learning**:
- Motor decoding
- Fine motor control
- Continuous control problems
- Kinematic decoding

---

### Willet Speech (Brain-Computer Interface)

**Location**: `willet-speech/willet-speech-dataset.ipynb`
**Data Processing**: `willet-speech/data2np_willetSpeechBCI.ipynb`

**Description**: Neural recordings from motor cortex during attempted speech production in humans.

**Key Features**:
- Intracortical recordings
- Attempted speech movements
- Multiple phonemes and words

**Good for learning**:
- Speech decoding
- Classification problems
- Phoneme recognition

---

### Zebra Finch (Vocal Learning)

**Location**: `zebra-finch/zebra-finch-dataset.ipynb`

**Description**: Neural recordings from songbird brain areas during singing and vocal learning.

**Key Features**:
- Premotor area recordings (HVC)
- Natural behavior (singing)
- Temporal structure (song syllables)
- Cross-species neuroscience

**Good for learning**:
- Sequence generation
- Temporal coding
- Pattern recognition


## Getting Started with a Dataset

### Step 1: Read the Overview
Start with `dataset-overview.pdf` to understand the options

### Step 2: Choose Your Dataset
Pick based on your interests and project goals

### Step 3: Open the Notebook
Navigate to the dataset folder and open the `.ipynb` file in Jupyter

### Step 4: Work Through the Tutorial
- Read the background information
- Run cells sequentially
- Understand the data structure
- Explore the example visualizations

### Step 5: Start Your Project
- Define a clear question
- Plan your analysis approach
- Use mini-workshop techniques
- Iterate and refine

## Technical Information

### Data Formats

Most datasets provide:
- **Neural activity**: Spike counts or firing rates in time bins
- **Behavioral data**: Task variables (position, movement, speech attempts, etc.)
- **Metadata**: Trial information, timing, experimental conditions

Common data structures:
```python
# Typical format
neural_data.shape  # (n_trials, n_neurons, n_time_bins)
behavior_data.shape  # (n_trials, n_features, n_time_bins) or (n_trials, n_features)
```

### Required Libraries

All dataset notebooks require:
```python
import numpy as np
import matplotlib.pyplot as plt
import pandas as pd
```

Some may additionally use:
```python
import scipy
import seaborn as sns
from sklearn.model_selection import train_test_split
from sklearn.decomposition import PCA
```

### Loading Data

Each notebook includes complete data loading code. Typical pattern:
```python
# Load data
data = np.load('dataset_file.npz')
neural_activity = data['neural']
behavior = data['behavior']

# Check shapes
print(f"Neural data: {neural_activity.shape}")
print(f"Behavioral data: {behavior.shape}")
```