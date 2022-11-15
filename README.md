Download Data --> [source](https://drive.google.com/drive/u/0/folders/1tz4IOoJKdi999IRdqJY04VOifyllRzj1)

## create environment
```bash
conda create --prefix ./env python=3.7 -y
```

## activate environment
```bash
conda activate ./env
```

## install requirements
```bash
pip install -r requirements.txt
```

## initalize repo and dvc
```bash
git init
dvc init
```

## create folders and files
```bash
mkdir src
mkdir src/utils
mkdir config
```

```bash
touch config/config.yaml
touch src/utils/__init__.py
touch src/utils/all_utils.py
touch src/__init__.py
touch src/stage_01_load_save.py
touch dvc.yaml
touch params.yaml
touch README.md
touch setup.py
```