# Leveraging Pretrained Language Models for Code Generation

Code generation has become an indispensable tool within the software development process, empowering developers to navigate intricate coding scenarios effortlessly. With the advent of language models and generative AI technology, code generation has evolved to harness automated tools that scrutinize codebases, identify programming patterns, and propose code completions or enhancements. Consequently, this evolution has resulted in a significant enhancement of programming efficiency and reliability.
A pivotal advancement in contemporary technology lies in the creation of transformer language models. These models have demonstrated exceptional efficacy in capturing subtle nuances in language, producing coherent, and contextually appropriate text. Successfully deployed in diverse natural language processing tasks, including text classification, text generation, sentiment analysis, machine translation, and speech recognition, transformer language models stand as a key breakthrough in modern technological landscape.

In this work, we explore the integration of pre-trained transformer language models with the Marian Decoder for code generation. We evaluate the performance of these models on two datasets and compare them to existing state-of-the-art models. We aim to investigate the potential of pre-trained transformer language models to revolutionize code generation, offering improved precision and efficiency in navigating complex coding scenarios.
We select four transformer language models, DistilRoBERTa, DistilBERT, ELECTRA, and LUKE, for our study, based on their strong performance in various natural language processing tasks. Our thorough analysis includes evaluations on the CoNaLa and DJANGO datasets, as well as assessments of static errors and refactoring.

Our results show that these models, when combined with the Marian Decoder, significantly improve code generation accuracy and efficiency. Notably, the RoBERTaMarian model achieved a maximum BLEU score of 35.74 and an exact match accuracy of 13.8\% on CoNaLa, while LUKE-Marian attained a BLEU score of 89.34 and an exact match accuracy of 78.50% on DJANGO.
Our findings demonstrate the potential of pre-trained transformer language models to revolutionize code generation, offering improved precision and efficiency in navigating complex coding scenarios. The introduced models represent a significant step forward in this field, paving the way for future advancements in code assistance and automation.

# Proposed Models

## 1- DistilBERT + Marian Decoder

### On CoNaLa
Implementation of the model is done this notebook at Google Colab Pro
## [Implementation code for BERTMarian Model on CoNaLa Dataset](https://github.com/AhmedSSoliman/Leveraging-Pretrained-Language-Models-for-Code-Generation/blob/master/DistilBERT_Marian_CoNaLa.ipynb) &nbsp;&nbsp; [![Open in Colab][Colab Badge]][DistilBERT-Marian-CoNaLa]

<br />

### On DJANGO
Implementation of the model is done this notebook at Google Colab Pro
## [Implementation code for BERTMarian Model on DJANGO Dataset](https://github.com/AhmedSSoliman/Leveraging-Pretrained-Language-Models-for-Code-Generation/blob/master/DistilBERT_Marian_DJANGO.ipynb) &nbsp;&nbsp; [![Open in Colab][Colab Badge]][DistilBERT-Marian-DJANGO]

<br />


## 2- DistilRoBERTa + Marian Decoder

### On CoNaLa
Implementation of the model is done this notebook at Google Colab Pro
## [Implementation code for RoBERTaMarian Model on CoNaLa Dataset](https://github.com/AhmedSSoliman/Leveraging-Pretrained-Language-Models-for-Code-Generation/blob/master/DistilRoBERTa_Marian_CoNaLa.ipynb) &nbsp;&nbsp; [![Open in Colab][Colab Badge]][DistilRoBERTa-Marian-CoNaLa]

<br />

### On DJANGO
Implementation of the model is done this notebook at Google Colab Pro
## [Implementation code forRoBERTaMarian Model on DJANGO Dataset](https://github.com/AhmedSSoliman/Leveraging-Pretrained-Language-Models-for-Code-Generation/blob/master/DistilRoBERTa_Marian_DJANGO.ipynb) &nbsp;&nbsp; [![Open in Colab][Colab Badge]][DistilRoBERTa-Marian-DJANGO]

<br />


## 3- ELECTRA + Marian Decoder

### On CoNaLa
Implementation of the model is done this notebook at Google Colab Pro
## [Implementation code for ELECTRAMarian Model on CoNaLa Dataset](https://github.com/AhmedSSoliman/Leveraging-Pretrained-Language-Models-for-Code-Generation/blob/master/ELECTRA_Marian_CoNaLa.ipynb) &nbsp;&nbsp; [![Open in Colab][Colab Badge]][ELECTRA-Marian-CoNaLa]

<br />

### On DJANGO
Implementation of the model is done this notebook at Google Colab Pro
## [Implementation code for ELECTRAMarian Model on DJANGO Dataset](https://github.com/AhmedSSoliman/Leveraging-Pretrained-Language-Models-for-Code-Generation/blob/master/ELECTRA_Marian_DJANGO.ipynb) &nbsp;&nbsp; [![Open in Colab][Colab Badge]][ELECTRA-Marian-DJANGO]

<br />


## 4- LUKE + Marian Decoder

### On CoNaLa
Implementation of the model is done this notebook at Google Colab Pro
## [Implementation code for LUKEMarian Model on CoNaLa Dataset](https://github.com/AhmedSSoliman/Leveraging-Pretrained-Language-Models-for-Code-Generation/blob/master/LUKE_Marian_CoNaLa.ipynb) &nbsp;&nbsp; [![Open in Colab][Colab Badge]][LUKE-Marian-CoNaLa]

<br />

### On DJANGO
Implementation of the model is done this notebook at Google Colab Pro
## [Implementation code for LUKEMarian Model on CoNaLa Dataset](https://github.com/AhmedSSoliman/Leveraging-Pretrained-Language-Models-for-Code-Generation/blob/master/LUKE_Marian_CoNaLa.ipynb) &nbsp;&nbsp; [![Open in Colab][Colab Badge]][LUKE-Marian-DJANGO]

<br />



```


# Citation

We now have a [paper](https://doi.org/10.1186/s44147-022-00159-4) for this work and you can cite:

```
@article{soliman2022mariancg,
  title={Leveraging pre-trained language models for code generation},
  author={Soliman, Ahmed and Shaheen, Samir and  Hadhoud, Mayada},
  journal={Complex & Intelligent Systems},
  year={2024},
  publisher={Springer}
  url={https://doi.org/10.1007/s40747-024-01373-8}
}

```


### Support
1.  **Star this repository**
2.  **Promote this repository**
3.  **Contribute to this repository**





[Colab Badge]:          https://colab.research.google.com/assets/colab-badge.svg
[License-Badge]:        https://img.shields.io/badge/License-MIT-blue.svg
[DistilBERT-Marian-CoNaLa]:         https://colab.research.google.com/drive/1liPpj16n4NWZX-W0sDYWFcPoWxHEJpgh?usp=sharing
[DistilBERT-Marian-DJANGO]:         https://colab.research.google.com/drive/1qwuFUCX-DwdnCnd5Y6J2e3yNjOMUSocJ?usp=sharing
[DistilRoBERTa-Marian-CoNaLa]:         https://colab.research.google.com/drive/1vFysJpj6FLxqBq6VXFzoqvk6DUQdYEM4?usp=sharing
[DistilRoBERTa-Marian-DJANGO]:         https://colab.research.google.com/drive/1CWccGEeQUHt56wQatWZlSWxApNHX3LTn?usp=sharing
[ELECTRA-Marian-CoNaLa]:         https://colab.research.google.com/drive/18lXuDhb-AfSOhn_TJUCV_45un0C-q39v?usp=sharing
[ELECTRA-Marian-DJANGO]:         https://colab.research.google.com/drive/1d5amVCygH0C45Uy5cMNKzDkkje8nvsRe?usp=sharing
[LUKE-Marian-CoNaLa]:         https://colab.research.google.com/drive/1-DrB0eaoBEiJwaQLESrYps2R78vM3Xgi?usp=sharing
[LUKE-Marian-DJANGO]:         https://colab.research.google.com/drive/1sm3WPe5wnN_sSEDaHaMpp-cI9aWP5dMw?usp=sharing
