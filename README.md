# sentiment-analyzer
Sentiment Classification using lightgbm, tracked with MLflow in AWS EC2 instance, ML pipeline with DVC

### 1. Create a conda environment after cloning the repository

```bash
conda create -n sen-analyzer-cenv python=3.11 -y
```

```bash
conda activate sen-analyzer-cenv
```


### 2. install the requirements
```bash
pip install -r requirements.txt
```

# 5 Steps in DVC pipeline

1. Data Ingestion
2. Data Preprocessing
3. Model Building
4. Model Evaluation
5. Model Registration

### DVC Commands
```bash
dvc init
dvc repro
dvc dag
```
