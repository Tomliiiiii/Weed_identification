# Weed identification

This is a deep learning project for weed classification in winter cereals.  
The dataset is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

## Project Goal
The objective is to develop a robust classification model that can reliably identify seven widespread and hard-to-control weed species.  
This project serves as an entry point into AI-powered precision agriculture and can later be integrated into drones or robotic applications.

## Dataset
- 10,810 images
- 7 classes:  
  - *Avena sterilis*  
  - *Lolium multiflorum*  
  - *Convolvulus arvensis*  
  - *Fumaria officinalis*  
  - *Papaver rhoeas*  
  - *Veronica persica*  
  - *Vicia sativa*  
- Image size: minimum 512×512 px, RGB  
- Images captured under varying lighting and distance conditions  

**License:** CC BY 4.0  

**Citation:**  
If you use this dataset, please cite the original source:

> Dainelli, R., Martinelli, M., Bruno, A., Moroni, D., Morelli, S., Silvestri, M., Ferrari, E., Rocchi, L., & Toscano, P. (2023).  
> *A phenotyping weeds image dataset for open scientific research (v_1_0)* [Data set]. Zenodo.  
> [https://doi.org/10.5281/zenodo.7598372](https://doi.org/10.5281/zenodo.7598372)

## Project Structure
```bash
Weed_identification/
├── data/                # raw and processed data (not tracked in git)
├── notebooks/           # Jupyter notebooks for analysis and training
├── results/             # models, logs, figures
├── requirements.txt     # Python dependencies
└── README.md
