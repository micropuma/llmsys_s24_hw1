# CMU-LLM environment set up
```shell
conda create -n minitorch python=3.9
conda activate minitorch
python -m pip install -r requirements.txt
python -m pip install -r requirements.extra.txt
python -m pip install -Ue .
```
