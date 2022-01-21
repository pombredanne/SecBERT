<!--
 * @Author: Kun
 * @Date: 2020-11-24 22:58:24
 * @LastEditTime: 2022-01-21 14:05:35
 * @LastEditors: Kun
 * @Description: 
 * @FilePath: /projects/my_open_projects/SecBERT/README.md
-->
# <p align=center>**`SecBERT`**</p>

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/jackaduma/SecBERT)
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://paypal.me/jackaduma?locale.x=zh_XC)

[**中文说明**](./README.zh-CN.md) | [**English**](./README.md)

`SecBERT` is a `BERT` model trained on cyber security text, learned CyberSecurity Knowledge.

* `SecBERT` is trained on papers from the corpus of 
  
  * [APTnotes](https://github.com/kbandla/APTnotes)
  
  * [Stucco-Data: Cyber security data sources](https://stucco.github.io/data/)  
  
  * [CASIE: Extracting Cybersecurity Event Information from Text](https://ebiquity.umbc.edu/_file_directory_/papers/943.pdf)
  
  * [SemEval-2018 Task 8: Semantic Extraction from CybersecUrity REports using Natural Language Processing (SecureNLP)](https://competitions.codalab.org/competitions/17262). 

* `SecBERT` has its own vocabulary (`secvocab`) that's built to best match the training corpus. We trained [SecBERT](https://huggingface.co/jackaduma/SecBERT)  and [SecRoBERTa](https://huggingface.co/jackaduma/SecRoBERTa) versions.


## **Table of Contents**


## **Downloading Trained Models**

SecBERT models now installable directly within Huggingface's framework:
```
from transformers import AutoTokenizer, AutoModelForMaskedLM

tokenizer = AutoTokenizer.from_pretrained("jackaduma/SecBERT")

model = AutoModelForMaskedLM.from_pretrained("jackaduma/SecBERT")


tokenizer = AutoTokenizer.from_pretrained("jackaduma/SecRoBERTa")

model = AutoModelForMaskedLM.from_pretrained("jackaduma/SecRoBERTa")

```

------

## **Pretrained-Weights** 

`Huggingface Modelhub`

  * [SecBert](https://huggingface.co/jackaduma/SecBERT)

  * [SecRoBERTa](https://huggingface.co/jackaduma/SecRoBERTa)


## **Downstream-tasks** 
