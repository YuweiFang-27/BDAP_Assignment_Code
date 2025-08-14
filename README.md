# Factors affecting the severity of traffic accidents
This repository contains a three-part project analyzing factors influencing the severity of traffic accidents in Victoria, Australia. The project involves data cleaning, exploratory analysis, clustering, and supervised modeling.

## Project Structure
| File | Description |
|------|-------------|
| `Part A.ipynb` | Data preprocessing, merging, and initial exploration |
| `Part B.ipynb` | Exploratory data visualization, PCA, and clustering (KMeans) |
| `Part C.ipynb` | Supervised learning (Logistic Regression, Random Forest, XGBoost) and model evaluation |

## Dataset
The dataset is derived from publicly available Victorian traffic accident data and includes information on accident type, speed zone, light condition, road geometry, and more.

### Raw Data (`raw_data.zip`)
- `accident.csv`
- `road_surface_cond.csv`
- `atmospheric_cond.csv`
- `accident_merged.csv` —— Merged dataset using `ACCIDENT_NO` as key

### Cleaned Dataset
- `accident_cleaned.csv` – Final dataset after data cleaning

## Execution

To reproduce the results:

1. Clone or download the repository.
2. Unzip the `raw_data.zip` file and place all datasets in the same directory as the notebooks.
3. Run the notebooks in sequence: Part A → Part B → Part C.
