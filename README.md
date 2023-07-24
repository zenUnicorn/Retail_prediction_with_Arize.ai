# Retail_prediction_with_Arize.ai
Retail prediction with Arize.ai

## Arize Ai
ML Observability Platform for real-time monitoring, analysis, and explainability. Arize is the machine learning Observability Platform for ML practitioners to monitor, troubleshoot, and explain models. Data Science and ML Engineering teams of all sizes (from individuals to enterprises) use Arize to:

- Monitor real-time model performance, with support for delayed ground truth/feedback.
- Root cause model failures/performance degradation using tracing and explainability.
- Conduct multi-model performance comparisons.
- Surface drift, data quality, and model fairness/bias metrics.

## Installation
```python
pip install arize
```

Initialize Arize client from arize.pandas.logger to call  Client.log() 

```python

from arize.pandas.logger import Client, Schema
​
API_KEY = 'ARIZE_API_KEY'
SPACE_KEY = 'YOUR SPACE KEY'
arize_client = Client(space_key=SPACE_KEY, api_key=API_KEY)
```





