# <img src="https://upload.wikimedia.org/wikipedia/commons/c/c8/Logo_of_the_Technical_University_of_Munich.svg" height="24">&ensp;DART demand model
This repository contains the demand modeling framework developed under the DART project by the Technical University of Munich (TUM) in Singapore. The framework integrates farecard data with housing and land-use datasets to model travel demand, with a focus on simulating on-demand mobility services. For more details, please refer to the [Wiki](https://github.com/Cacaonut/tum-dart-demand-wiki/wiki).

## 🗂️ Project structure
This shows an excerpt of the project structure to highlight relevant directories.
```
├── data
│   ├── input - data specific to the desired usecase
│   ├── internal - data that is usually usecase independent
│   └── processed - generated during execution
├── src - source code
├── notebooks - jupyter notebooks (only used during development)
├── scripts - scripts for building and running the model (you should use these)
└── results - outputs of various scripts
```

## 🚀 Getting started
To get started, you need to install the required dependencies. We recommend using a conda environment to manage the dependencies:
```bash
conda env create -f environment.yml
conda activate tum-dart-demand
```

## ⚙️ Usage
For usage instructions on the model, please refer to the [Wiki](https://github.com/Cacaonut/tum-dart-demand-wiki/wiki/2.-Usage).
You may also want to look at [this repository](https://github.com/Cacaonut/tum-dart-demand-explorer) for an interactive explorer of your model.

## 🖥️ Tested on
MacOS 15.1.1, M2 Pro, Python 3.11.11<br>
Windows 11 23H2, i7-8700K, Python 3.11.11

## ✉️ Contact
This project: [Karl Benedikt Kaesen (TUM CIT)](mailto:benedikt.kaesen@tum.de)<br>
DART project: [Dr.-Ing. Andreas Rau (TUM Asia)](mailto:andreas.rau@tum-asia.edu.sg), [Zhipu Chen (TUM Asia)](mailto:zhipu.chen@tum.de)<br>
FleetPy framework: [Dr. Florian Dandl (TUM VT)](mailto:florian.dandl@tum.de), [Dr. Antonios Tsakarestos (TUM VT)](mailto:antonios.tsakarestos@tum.de)
