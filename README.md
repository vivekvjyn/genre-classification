# Genre classification

## How to run

**Clone the repository**

```bash
git clone https://github.com/vivekvjyn/genre-classification.git
cd genre-classification
```

**Create and activate conda environment**

```bash
conda create -n genreclassification python=3.10
conda activate genreclassification
```

**Install CUDA and CuDNN**

```bash
conda install -c conda-forge -y cudatoolkit=11.2 cudnn=8.1
```

**Install dependencies**

```bash
pip install -r requirements.txt
```

**Run jupyter server**
```bash
CUDA_VISIBLE_DEVICES=0 TF_CPP_MIN_LOG_LEVEL=3 jupyter notebook
```

## Open in colab
>[!Note]
>To open in colab, click on ![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg) at the top of the notebook.
