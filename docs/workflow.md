# Workflow and reproducibility

## Notebook structure

- Fighting Fire with Data - Starter Notebook
- Setup
- Libraries Used
- EDA + Feature Engineering
- Adding date features
- Time Series Analysis
- Removing Collinearity
- Adding more features - some ideas
- Data Split for Validation
- Feature Selection
- Simple Model
- Hyperparameter tuning
- Model 2 - SVM
- Gradient Boosting
- Lasso Regression
- Linear Regression
- Decision Tree Regression
- Making A Submission
- Tips for improving your score

## Required inputs

The original challenge inputs are `Train.csv`, `Test.csv`, `variable_definitions.csv` and `SampleSubmission.csv`. Obtain them from the original competition source; no unverified replacement dataset is supplied. Set `BURNT_AREA_DATA_DIR` to their directory.

## Run and interpret

The notebook is an experiment log, not one finalized forecasting pipeline. It includes target-derived lags together with random splits. Those results need a time/group-aware validation review before being used as forecast evidence. Never construct holdout features from unavailable future targets. Published historical outputs are retained, not presented as a new benchmark.

## Maintenance verification

Personal Drive paths were replaced with a configurable data directory; setup and validation limitations are documented. The notebook was checked as Jupyter format. Any preview in the README comes from existing saved output; the full external-data experiment was not rerun. Package installation and original environment compatibility may need adjustment for the historical code. Data, checkpoints and exported outputs are excluded from Git by default.
