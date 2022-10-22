
## Installation guide 
```
git clone https://github.com/KrishnanSG/holt-winters.git
cd holt-winters/
pip install -r requirements.txt
```

## Jupyter Notebook
The [notebook](analysis.ipynb) contains the sales data analysis along with the following:

- What is seasonal decomposition of a time series?
- Model selection and validation.
- Model summary and conclusion.


## Python Script
For those who prefer [python script](analysis.py) over jupyter notebook.


### Generating the analysis
```python
python analysis.py
```

## Anomaly Detection
[anomaly_detection.py](anomaly_detection.py) script contains the implementation of brutlag algorithm to find anomalies in [average temperature of India](dataset/average_temp_india.csv) dataset.

```
python anomaly_detection.py
```

[anomaly_detection.ipynb](anomaly_detection.ipynb)  notebook contains a detailed analysis of anomaly detection using Holt-Winter model and brutlag algorithm.

**Note:** The datasets used for the analysis can be found under the [dataset](dataset/) folder.

