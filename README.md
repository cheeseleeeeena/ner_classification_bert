# Task 2: NER Classification (tner/bc5cdr)

Using pretrained BERT with PyTorch

## Environment Setup

1. Operating System
    - Name: `macOS Ventura`
    - Version: `13.5.2`
2. Python Environment
    - Version: `3.9+`
    - `conda` Version: `23+`
    - `pip` Version: `23+`

## Installation

1. Clone repository

```sh
git clone https://github.com/cheeseleeeeena/ner_classification_bert.git
```

2. Install **required packages**

```sh
conda install --yes --file requirements. txt
```

3. Install [**PyTorch**](https://pytorch.org/get-started/locally/#start-locally)

|選項|描述|選擇|
|-|-|-|
|PyTorch Build|請選**穩定版**避免未知錯誤|`Stable(2.0.1)`|
|Your OS|依照**作業系統**來選擇|`Mac`|
|Package|安裝 **PyTorch** 使用的方法|`Conda`|
|Language|當前執行 **Python** 版本|`Python 3.9`|
|CUDA|電腦上是否有 **GPU** 且支援 **CUDA 架構**|`Default`|

```sh
conda install pytorch::pytorch torchvision torchaudio -c pytorch
```

## References

1. Hugging Face NLP Course (https://huggingface.co/learn/nlp-course/chapter3/1?fw=pt)
