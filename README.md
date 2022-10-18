# Genre Classification

Random Forest classification using MLFlow and wandb.

## Conda Environment

Create conda environment
```
conda create --name udacity python=3.8 mlflow jupyter pandas matplotlib requests wandb protobuf -c conda-forge
```

Activate the created environment
```
conda activate udacity
```

## Troubleshoot

```
for f in $(ag --files-with-matches "wandb==0.10.21");
do
  sed -i -e 's,wandb==0.10.21,wandb==0.13.4,g' "${f}";
done
```
