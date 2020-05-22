# COVID-19-CheXNet-
COVID-19 CheXNet code and data

## [Data](https://github.com/jesuspradaalonso/COVID-19-CheXNet-/data)

- **images**: X-ray images from <https://github.com/ieee8023/covid-chestxray-dataset>.
- **new_images**: X-ray images from <https://covid19.espacio-seram.com/index.php>.
- metadata.csv: Original metadata for X-ray files in images folder.
- clean_data.csv: Pre-processed metadata for X-ray files in images folder.
- new_clean_data.csv: Pre-processed metadata for X-ray files in new_images folder.

## [Scripts](https://github.com/jesuspradaalonso/COVID-19-CheXNet-/scripts)

- grid.ipynb: Grid search for hyperparameter optimization of first layer CNN model.
- train.ipynb: Train and evaluation of final first layer CNN model using optimal hyperparameters found in grid.ipynb.
- final_model.ipynb: Train and evaluation of second layer model coded in Python.
- final_model.R: Train and evaluation of second layer model coded in R.