# breast_cancer_prediction

> Classify breast cancer subtypes using [Breast Cancer Wisconsin Dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)). Cancer classification historically requires prior biological knowledge. However, most machine learning engineers lack biological background. Prediction models with high accuracy are aimed to aid oncologists with diagnosis and prognosis. Apart from achieve high accuracy, the goal of this project is to generate comprehensive data analysis that helps with identifying a suitable classifier.

## Data

The data contains 569 samples in total with two classes: malignant cells and benign cells. The original image provides 10 characteristics for each sample: radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry and fracture. The mean value, standard error, and mean of the three largest values are calculated from the original data, respectively, for each data sample. Therefore, 30 features are generated for each sample.

## Visualizations (EDA)

### Pairwise Plot

<img src="./Docs/Figures/pairwise.png" alt="drawing" width="400"/>

### Correlation Heatmap

<img src="./Docs/Figures/heatmap.png" alt="drawing" width="400"/>

### 3D PCA Analysis

<img src="./Docs/Figures/PCA.png" alt="drawing" width="400"/>

### 3D T-SNE Analysis

<img src="./Docs/Figures/tsne.png" alt="drawing" width="400"/>

## Algorithmic Pipeline

<img src="./Docs/Figures/pipeline.png" alt="drawing" width="400"/>

## Model Evaluation

### Decision Surface

<img src="./Docs/Figures/decision_surface.png" alt="drawing" width="500"/>

### Accuracy Comparison

<img src="./Docs/Figures/accuracy.png" alt="drawing" width="500"/>


## Docs

A comprehensive report is available [here](https://ziyuan-shen.github.io/files/breast_cancer_prediction_report.pdf).