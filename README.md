# Bifurcation and chaos in vocal-ventricular fold co-oscillations
Data driven analysis of experimental data measured from the vocal and ventricular folds.
Sample codes of experimental data analysis measured from the physical models of vocal and ventricular folds.
This data was observed by T. Matsumoto et al, and the paper has been published.

T. Matsumoto, M. Kanaya, D. Matsushima, C. Han, and I. T. Tokuda, Synchronized and Desynchronized Dynamics Observed from Physical Models of the Vocal and Ventricular Folds, Journal of Voice, December 2021
[[Link]](https://www.sciencedirect.com/science/article/pii/S0892199721003581?casa_token=l3j8-1zgEnMAAAAA:6NkvQuTElFXKwLoyBeaI0Q-gJCgTS2nQ1BGGC4tEjRx1iM1pX1nwZnE2fuT16Ju4pEKQrccDqP7B)

The analysis results of this data were written as [bachelor thesis](bachelor_thesis_20230208.pdf) by Takumi INOUE in 2023. With this codes, you can reproduce the numerical experiments in the thesis.

## Data Preparation
Rhythm Lab's students can get the preprocessed datasets from lab's NAS. Please download VF_FVF_DATASETS from the NAS, and save it in ```/data```. 

If you want to use your own datasets, you need to save them in ```/data/VF_FVF_DATASETS_RAW``` , and run ```/src/0-Preprocess/preprocess_csv.py``` and ```preprocess_video.py```.

## Data Analysis Methods
### Attractor reconstruction (Time delay embedding)

### Nonlinear modeling (Echo-State Network)

### High-speed data (Line scanning) 

### Reconstructing bifurcation diagram (Autoencoder & SINDy) 

## Directory Structure
