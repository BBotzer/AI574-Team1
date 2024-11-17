**Team:**
* Abahana Zelalem
* Benjamin Arnosti
* Brandon Botezr

**Course:** AI 574 – Natural Language Processing (Fall, 2024)

# Problem Statement
The objective of this project is to develop an effective SMS phishing detection system by leveraging cutting-edge NLP models such as BERT and OpenAI LLMs. These models have revolutionized language understanding and exhibit the capability to detect phishing attempts in a more context-aware manner. By comparing their performance to traditional machine learning models such as RNNs, this project aims to highlight the strengths and limitations of each approach.

Our system will analyze both the textual content of SMS messages and any embedded features, such as URLs, email addresses, or phone numbers, to classify messages as phishing, smishing, spam, or legitimate (ham). While traditional models rely on handcrafted features and are generally faster, they may lack the sophistication needed to handle the complexities of modern phishing techniques. Transformer-based models, on the other hand, offer enhanced performance by capturing nuanced patterns in short messages, which is crucial in detecting sophisticated phishing attacks hidden in mobile text formats.

By comparing traditional and advanced models, the project will provide insights into which models strike the best balance between performance, interpretability, and computational efficiency for real-time phishing detection in mobile environments.

* **Keywords:** SMS, Phisishing, Smishing, text, phone, Natural Language Processing


# Dataset Description

URL: https://data.mendeley.com/datasets/f45bkkt8pr/1/

SMS PHISHING DATASET FOR MACHINE LEARNING AND PATTERN RECOGNITION
Published: 20 June 2022| Version 1 | DOI: 10.17632/f45bkkt8pr.1
Contributors:
sandhya mishra,
Description

The dataset is a set of labelled text messages that have been collected for SMS Phishing research. It has 5971 text messages labeled as Legitimate (Ham) or Spam or Smishing. It includes 489 spam messages, 638 smishing messages, and 4844 ham messages. This dataset contains raw message content that can be used as labelled data in Deep Learning or for extracting further attributes. The dataset contains extracted attributes from malicious messages that can be used for Classification of messages as malicious or legitimate. This dataset also includes python code that are used for extracting attributes. The data has been collected by converting the images obtained from the Internet to text using Python code. Attributes have been selected based on their relevance. The details of dataset attributes are given below: 

LABEL- Classification label categorizing the message as ham, spam, or Smishing
TEXT- The raw content of the message.
URL- Gives out whether the message contains a URL or not.
EMAIL- Gives out whether the message contains an email id or not.
PHONE - Gives out whether the message contains a phone number or not.
Python code for extraction of the above listed dataset attributes is attached. The snapshot of this dataset is also attached. Frequency chart of the attributes are also attached.






# smishing repo

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

Work to classify SMS Phishing with NLP models.

## Project Organization

```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         smishing and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── smishing   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes smishing a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations
```

--------

