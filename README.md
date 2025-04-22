# 📰 Fake News Detection Using Ensemble Learning

---

| S. No |    ID No.     | Name             |
| ----: | :-----------: | :--------------- |
|    1. | 2022A7PS0003U | Yusra Hakim      |
|    2. | 2022A7PS0019U | Joseph Cijo      |
|    3. | 2022A7PS0031U | Ritvik Bhatnagar |

This Repository hosts the model building part for the project in Data Mining (CS F415) course. It contains the code used for preparing the ensemble model using the dataset mentioned below.

### Dataset Details

**Dataset introduced in:**
V. Pawan Kumar, A. Prateek, A. Ivone and P. Radu, "WELFake: Word Embedding Over Linguistic Features for Fake News Detection," _IEEE Transactions on Computational Social Systems_, vol. 8, no. 4, pp. 881-893, 2021.
[Kaggle | WELFake Dataset](https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification)

### Setting Up an Environment for the Jupyter notebook

Firstly install Miniconda from [here](https://docs.anaconda.com/miniconda/install/).

Then open a command prompt in this directory, and run the following. This will create and activate an environment called "PROJ".

```bash
    conda create -n proj python=3.12
    conda activate proj
```

After running this, your CMD prompt should have a "`(proj)`" prefixed at the start.

Run the following command to install packages, such as [PyTorch](https://pytorch.org/get-started/locally/). This will take some time.

```bash
%conda install -n proj ipykernel ipywidgets --update-deps --force-reinstall
%conda install -n proj nltk
%conda install -n proj conda-forge::textblob
%pip install scikit-learn matplotlib pandas pyperclip contractions scipy numpy
%conda install -n proj conda-forge::transformers
%pip install torch --index-url https://download.pytorch.org/whl/cu124
```

Remember to select the PROJ environment at the bottom-right.
