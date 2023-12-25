# Regression MLops

## Technology

- mlflow
- dvc
- python 3.10.4
- scikit-learn


## Instlation

```
cd regression-mlops
docker build -t mlflow:latest .
docker container run -it -p 5000:5000 mlflow:latest /bin/bash
```