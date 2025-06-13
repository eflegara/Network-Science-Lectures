# Network Science Lectures

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/eflegara/Network-Science-Lectures/blob/master/LICENSE.md)

Network Science, Complex Networks course materials for the [Asian Institute of Management](https://aim.edu/)'s [MSc. in Data Science](https://erikalegara.site/msds-unplugged/) program.

## 📚 Course Notebooks

Click the **"Open in Colab"** button to run any notebook directly in Google Colab (no installation required):

| # | Notebook | Description | Open in Colab |
|---|----------|-------------|---------------|
| 1 | [Intro to Network Analysis](notebooks/01_intro_to_network_analysis.ipynb) | Introduction to network analysis concepts | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eflegara/Network-Science-Lectures/blob/master/notebooks/01_intro_to_network_analysis.ipynb) |
| 2 | [Network Models](notebooks/02_network_models.ipynb) | Network generation models (ER, BA, WS) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eflegara/Network-Science-Lectures/blob/master/notebooks/02_network_models.ipynb) |
| 3 | [Centrality Measures](notebooks/03_centrality_measures.ipynb) | Network vulnerability and robustness | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eflegara/Network-Science-Lectures/blob/master/notebooks/03_centrality_measures.ipynb) |
| 4 | [Community Detection](notebooks/04_community_detection.ipynb) | Community detection in complex networks | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eflegara/Network-Science-Lectures/blob/master/notebooks/04_community_detection.ipynb) |
| 5 | [Error and Attack Tolerance](notebooks/05_error_and_attack_tolerance.ipynb) | Error and attack in complex networks | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eflegara/Network-Science-Lectures/blob/master/notebooks/05_error_and_attack_tolerance.ipynb) |
| 6 | [Vaccination Strategies](notebooks/06_vaccination_strategies.ipynb) | Application: Exploring vaccination strategies | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eflegara/Network-Science-Lectures/blob/master/notebooks/06_vaccination_strategies.ipynb) |
| 7 | [Friendship Paradox](notebooks/07_friendship_paradox.ipynb) | Phenomenon: Friendship paradox | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eflegara/Network-Science-Lectures/blob/master/notebooks/07_friendship_paradox.ipynb) |
| 8 | [Social Distancing](notebooks/08_social_distancing.ipynb) | Application: Social distancing model | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eflegara/Network-Science-Lectures/blob/master/notebooks/08_social_distancing.ipynb) |

## 🚀 Quick Start

### Option 1: Google Colab (Recommended for beginners)
1. Click any "Open in Colab" button above
2. All dependencies are pre-installed in Colab
3. Start learning immediately!

### Option 2: Local Installation

#### Prerequisites
- Python 3.10+ 
- Jupyter Notebook

#### Setup
```bash
# Clone the repository
git clone https://github.com/eflegara/Network-Science-Lectures.git
cd Network-Science-Lectures

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```

#### Required Libraries
- **NetworkX** - Network analysis and visualization
- **Matplotlib and Seaborn** - Plotting and visualization  
- **NumPy** - Numerical computing
- **Pandas** - Data manipulation
- **SciPy** - Scientific computing
- **lmfit** - Curve fitting (for epidemiological models)

For community detection, NetworkX 2.7 and later include a built-in Louvain algorithm. If you encounter issues:
```bash
pip install python-louvain
```

## 📊 Course Structure

This course covers fundamental concepts in network science:

**Foundation (Notebooks 1-2)**
- Basic network concepts and terminology
- Network models and generation algorithms

**Analysis (Notebooks 3-4)** 
- Centrality measures and node importance
- Community structure and detection methods

**Applications (Notebooks 5-8)**
- Network robustness and resilience
- Epidemiological modeling on networks
- Social phenomena and paradoxes

## 📖 Course Information

These notebooks accompany the Network Science course under [AIM's MSc in Data Science program](https://aim.edu/programs/degree-programs/master-science-data-science), where Network Science is a core data science course.

## 🗂️ Repository Structure

```
├── notebooks/           # Jupyter notebooks (numbered sequence)
├── datasets/           # Data files used in examples
├── figures/           # Generated plots and diagrams
├── requirements.txt   # Python dependencies
└── README.md         # This file
```

## 👨‍🏫 Author

**Erika Fille Legara**  
- Website: [erikalegara.site](https://erikalegara.site)
- Institution: Asian Institute of Management

## 🤝 Contributing

Found an issue or have suggestions? Please [open an issue](https://github.com/eflegara/Network-Science-Lectures/issues) or submit a pull request.

## 📄 License

MIT License - see [LICENSE.md](LICENSE.md) for details.

---

*⭐ If you find these materials helpful, please consider giving this repository a star!*
