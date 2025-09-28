## How to run?

conda create -n test python=3.13.7 -y

conda activate test

 python -m pip install -r requirements.txt

git init

dvc init

dvc repro

dvc dag

dvc metrics show
