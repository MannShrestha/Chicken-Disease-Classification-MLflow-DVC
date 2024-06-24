# Chicken-Disease-Classification-MLflow-DVC

### Project Workflows
1. update config.yaml
2. Update secrets.yaml[Optional]
3. update params.yaml
4. update the entity
5. update the configuration manager in src config
6. update the components
7. update the pipeline
8. update the main.py
9. update the dvc.yaml
10. update the app.py



### How to run the projet

### STEPS:

Clone the repository

```bash
https://github.com/MannShrestha/Chicken-Disease-Classification-MLflow-DVC.git
```

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n deepL python==3.8 -y

OR

conda create -p deepL python==3.8 -y
```

```bash
conda activate deepL
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

### After Training the model - to visualize Training report through Tensorboard
```bash
tensorboard --logdir artifacts/prepare_callbacks/tensorboard_log_dir/
```


