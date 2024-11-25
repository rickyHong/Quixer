# Quixer

## Installation
```
pip install -r requirements.txt

pip uninstall torch torchtext
pip install --trusted-host pypi.org --trusted-host files.pythonhosted.org torch==2.3.0 torchtext==0.18.0

```

## Running all models

On CPU:
```
python ./run_comprehensive.py cpu
```

On Nvidia GPU:
```
python ./run_comprehensive.py cuda
```
