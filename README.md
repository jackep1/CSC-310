# Data Science Projects

Jupyter notebooks from CSC 310 (Programming for Data Science) at the University of Rhode Island, ending with a bank marketing classification project.

**Language:** Python · **Libraries:** pandas, NumPy, scikit-learn, seaborn, matplotlib

## Featured: Bank Marketing Analysis

Predicts whether a bank customer will subscribe to a term deposit using the [UCI Bank Marketing dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing) (4,521 customers).

- **Models compared:** decision tree, K-nearest neighbors, support vector machine, and neural network
- **Methods:** grid search for hyperparameters, cross-validation, confusion matrices, precision and recall, permutation importance, and partial dependence plots
- **Result:** a depth-5 decision tree performed best on accuracy and precision and missed the fewest opportunities. Call duration was the most important feature.

Notebook: `Final_Analysis.ipynb`

## All Notebooks

| Notebook | Topic |
|---|---|
| `HW_2` to `HW_4` | Notebook setup and early homework |
| `HW_5` | Data visualization |
| `HW_6` | Model evaluation |
| `HW_8` | Comparing KNN and neural network (MLP) models |
| `HW_10` | Natural language processing |
| `Midterm` | Determining wine quality with a decision tree |
| `Final_Proposal` | Project proposals, including a white wine quality dataset |
| `Final_Analysis` | Bank marketing analysis (featured) |

## Running

The notebooks were written in Google Colab and mount Google Drive to load data. To run them locally, change the data paths to the `Datasets/` folder and remove the Colab imports.

```bash
pip install pandas numpy scikit-learn seaborn matplotlib jupyter
jupyter notebook
```

## Credits

Assignments provided by the CSC 310 course. Analysis and code are my work.
