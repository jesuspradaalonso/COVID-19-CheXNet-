# COVID-19-CheXNet-
COVID-19 CheXNet code and data

## [Data](https://github.com/jesuspradaalonso/COVID-19-CheXNet-/tree/master/data)

- **[images](https://github.com/jesuspradaalonso/COVID-19-CheXNet-/tree/master/data/images)**: X-ray images from <https://github.com/ieee8023/covid-chestxray-dataset>.
- **[new_images](https://github.com/jesuspradaalonso/COVID-19-CheXNet-/tree/master/data/new_images)**: X-ray images from <https://covid19.espacio-seram.com/index.php>.
- [metadata.csv](https://github.com/jesuspradaalonso/COVID-19-CheXNet-/tree/master/data/metadata.csv): Original metadata for X-ray files in images folder.
- [clean_data.csv](https://github.com/jesuspradaalonso/COVID-19-CheXNet-/tree/master/data/clean_data.csv): Pre-processed metadata for X-ray files in images folder.
- [new_clean_data.csv](https://github.com/jesuspradaalonso/COVID-19-CheXNet-/tree/master/data/new_clean_data.csv): Pre-processed metadata for X-ray files in new_images folder.

## [Scripts](https://github.com/jesuspradaalonso/COVID-19-CheXNet-/tree/master/scripts)

- [grid.ipynb](https://github.com/jesuspradaalonso/COVID-19-CheXNet-/tree/master/scripts/grid.ipynb): Grid search for hyperparameter optimization of first layer CNN model.
- [train.ipynb](https://github.com/jesuspradaalonso/COVID-19-CheXNet-/tree/master/scripts/train.ipynb): Train and evaluation of final first layer CNN model using optimal hyperparameters found in grid.ipynb.
- [final_model.ipynb](https://github.com/jesuspradaalonso/COVID-19-CheXNet-/tree/master/scripts/final_model.ipynb): Train and evaluation of second layer model coded in Python.
- [final_model.R](https://github.com/jesuspradaalonso/COVID-19-CheXNet-/tree/master/scripts/final_model.R): Train and evaluation of second layer model coded in R.

**GitHub created by:** Yvonne Gala García and Jesús Prada Alonso.
