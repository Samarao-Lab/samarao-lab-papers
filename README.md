# Samarao-Lab Papers

This repository collects the **code, processed data, and supporting materials** associated with research papers developed by Samarao-Lab.

Each paper is organised in its own folder so that the corresponding datasets, scripts, figures, and methodological resources can be accessed and reproduced more easily.

The repository will be updated as new papers are released. Raw market data used in the studies are obtained from the original public data providers where applicable, while processed datasets and research code are documented here.

## Most recent paper

### How Revenue Stacking Shapes BESS Sizing for Investment Decisions Under Uncertainty

This study investigates how access to different electricity-market revenue streams changes the economically preferred energy capacity of a fixed-power battery energy storage system (BESS).

The analysis combines day-ahead and intraday energy markets with Portuguese mFRR and aFRR mechanisms in a two-stage stochastic optimisation framework.

The results show that **revenue stacking is not energy-capacity stacking**: broader market access can increase project value while reducing the amount of energy capacity that is economically justified.

Supporting code, processed data, and additional material for this paper are provided in the corresponding project folder.

## Repository structure

```text
samarao-lab-papers/
├── paper-name/
│   ├── README.md
│   ├── code/
│   ├── data/
│   ├── processed_data/
│   └── outputs/
└── ...
```

## Data and reproducibility

This repository is intended to support the reproducibility of the research developed by Samarao-Lab.

For each paper, the corresponding folder will contain, where applicable:

- processed datasets used in the analysis;
- data-preprocessing and transformation scripts;
- optimisation and simulation code;
- scenario-generation procedures;
- scripts used to generate figures and tables;
- model parameters and configuration files;
- additional documentation required to reproduce the reported results.

Raw market data are obtained from the original public data providers whenever possible. For studies involving the Iberian and Portuguese electricity markets, these sources include **REN** and **OMIE**. The repository therefore focuses primarily on the processed datasets, modelling code, and research workflows developed by the authors.

Some datasets may also be accessible through the **Samarao-Lab API**, which provides structured access to market and research data.

Each paper-specific folder will include its own `README.md` describing the relevant data sources, preprocessing steps, code structure, and instructions for reproducing the analysis.

Repository contents may be updated as papers are revised or published. Where appropriate, versioned releases will be created to preserve the exact code and data associated with a particular manuscript version.

## Citation

If you use code, processed data, figures, or other material from this repository, please cite the corresponding research paper.
