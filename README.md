# p4-model-optimization

## Optimize ML model by AutoML & Tensor Decomposition

## Run

### 1. train
python train.py --model_name {model_name}

(path: configs/model/)

### 2. inference
python inference.py --weight_dir {weight_dir}

(path: exp/)

### 3. tune
python tune.py
