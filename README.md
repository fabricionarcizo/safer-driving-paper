# Data Analysis on Speeding Behavior: The Impact of Auditory Warnings and Demographic Factors

This repository contains the dataset, Jupyter Notebook, and supporting materials for the paper titled **"Data Analysis on Speeding Behavior: The Impact of Auditory Warnings and Demographic Factors"**, authored by Christian Bank Lauridsen, Mads Greve Andersen, Max-Emil Smith Thorius, and Fabricio Batista Narcizo.

## Repository Contents

### Files

1. **`data/obd_data.csv`**

   - Dataset containing real-time driving data collected during the study. This includes variables such as vehicle speed, engine speed (RPM), traffic speed, speed limit, and demographic information about drivers.

2. **`data_analysis.ipynb`**
   - Jupyter Notebook used for data analysis. The notebook includes:
     - Data preprocessing steps.
     - Exploratory data analysis (EDA).
     - Statistical methods applied to answer research questions.
     - Visualizations of key findings.

## Study Overview

This study investigates the impact of auditory alerts on speeding behavior across different demographic groups. Key research questions focus on:

- The relationship between driver experience and speeding duration.
- The effect of driver age on engine speed.
- The influence of auditory alerts on the frequency and duration of speeding incidents.
- Variations in alert effectiveness among drivers with different levels of experience.

## How to Use This Repository

### Prerequisites

Ensure that the following software is installed:

- Python 3.11 or later.
- Jupyter Notebook.
- Required Python packages listed in `data_analysis.ipynb` (e.g., pandas, matplotlib, seaborn, scipy).

### Steps to Reproduce Analysis

1. Clone this repository:

   ```bash
   git clone https://github.com/fabricionarcizo/safer-driving-paper.git
   cd safer-driving-paper
   ```

2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook data_analysis.ipynb
   ```

3. Follow the steps outlined in the notebook to reproduce the analysis and visualizations.

### Data Description

- **Source**: Data was collected using a mobile application during a field study in Copenhagen, Denmark. The application recorded real-time data from On-Board Diagnostics (OBD-II) systems and user demographic inputs.

- **Variables**:
  - Vehicle Speed (km/h)
  - Engine Speed (RPM)
  - Traffic Speed (km/h)
  - Speed Limit (km/h)
  - Driver Experience (years)
  - Driver Age (years)

### Key Findings

- Auditory alerts were associated with increased frequency and duration of speeding incidents.
- Driving experience significantly influences how drivers respond to alerts.
- Personalized and adaptive alert systems may enhance road safety.

## License

This repository is licensed under the MIT License. See the LICENSE file for details.

## Citation

If you use this dataset or code in your research, please cite the paper:

```bibtex
@article{Lauridsen2024,
  title={Data Analysis on Speeding Behavior: The Impact of Auditory Warnings and Demographic Factors},
  author={Lauridsen, Christian Bank and Andersen, Mads Greve and Thorius, Max-Emil Smith and Narcizo, Fabricio Batista},
  year={2024}
}
```

## Contact

For questions or feedback, please contact Fabricio Batista Narcizo at:

- **Email**: <narcizo@itu.dk>
- **GitHub**: [fabricionarcizo](https://github.com/fabricionarcizo)

---

We hope this repository supports your research and learning endeavors!
