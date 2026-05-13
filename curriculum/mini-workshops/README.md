# Mini-Workshops

This folder contains focused, modular sessions on specific techniques and topics in neural data analysis. Each mini-workshop is designed to be a optional break-out session that can participants can choose to attend.

## Folder Structure

```
mini-workshops/
├── how-to-data-visualization/          # Creating effective figures and plots
├── how-to-statistics/                  # Statistical testing for neural data
├── latent-neural-dynamics/             # Dimensionality reduction and dynamics
├── linear-ml-introduction/             # Linear ML methods for decoding
├── neural-data-tips-and-tricks/        # Practical advice for neural data
├── neural-decoding-gallery/            # Overview of historic decoding approaches
├── nonlinear-ml-techniques/            # Neural networks and advanced ML
└── README.md                          # This file
```

## Learning objectives for each topic:
We understand that you may want to modify/make new slides for these topics, so we wanted to highlight the major learning objectives for each topic to provide some focus/direction:

### How-to: Data Visualization
Discussing how to make plots and present data.

1. Introduce different kinds of plots common generally in data science. Could use a tighter focus on neural engineering (perhaps introducing PSTHs, etc) but the goal was to introduce different kinds of continuous and categorical plots to the students and briefly explain their use cases.
2. Review common plotting packages in python, e.g. matplotlib, seaborn. Introducing pandas dataframes here can be helpful as well
3. Emphasizing clarity of 'storytelling' through figures - don't include extraneous information, use colors to differentiate groups, make sure axes are clearly labelled, etc.
    
### How-to: Statistics
What stats can you do for these kinds of analyses?

1. Review hypothesis testing - hopefully most students should have taken some sort of stats by now
2. Point to common statistical tests for comparisons
3. Introduce evaluation metrics for decoding (MSE, Pearson Correlation, R^2 - coeff of determination)

### Latent Neural Dynamics
How do we look at neural data at a population level?

1. Introduce modern perspectives on population-level analyses of neural data
2. Introduce dimensionality reduction at a high level
3. For stereotyped tasks, introducing trial averaging and alignment
4. If time, mention potential applications (aligning drift over time, etc)

### Linear ML Introduction
Introduction to basic machine learning

1. Supervised ML
2. Within supervised ML, classification and regression (1 basic example of each, with list of other methods to look at) - take some time here to explain mathematically
3. Unsupervised ML - clustering and dimensionality reduction
4. For clustering - introduce K-means, then list other approaches
5. For dimensionality reduction- I start with a generic real-world example (can we explain 3 variables with 1) - then introduce PCA in some detail, followed by name dropping other approaches

### Neural Data Tips and Tricks
Hodge-podge of tips that don't fit in other presentations. Smoothing neural data, looking at different lags when training decoders, including time history, common average referencing.

### Neural Decoding Gallery
Review of approaches for modelling neural data, and basic decoding approaches. Gives students an overview of typical approaches in the field and what kinds of tasks have been done.

### Nonlinear ML Techniques
Introduction to nonlinear methods and artifical neural networks

1. Nonlinear classification (e.g. DBSCAN)
2. Nonlinear Regression
3. Artificial Neural Networks

