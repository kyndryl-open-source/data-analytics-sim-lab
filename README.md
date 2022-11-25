# SRE@Kyndryl

## SRE Public Labs - Data Analytics Sim

* Version: `0.1.0`
* License: `MIT`

### Learning objectives

* Learn how to use Python NumPy and matplolib for statistical methods

* Learn how to analyze a data set using Python code

### Pre-requisite knowledge

* Basic notions on `Python` programming language

* Understanding of histograms and percentiles

### Contents

* Histogram

Folder: `python`

| **File / folder** | **Description** |
|:--------------------------------|:--------------------------------|
| histogram.py | `Python code that generates random data set and applies statistical methods` |
| | |

* Latency Analysis

Folder: `python`

| **File / folder** | **Description** |
|:--------------------------------|:--------------------------------|
| latency.py | `Python code that reads a data set from a CSV file and computes its percentile and histogram` |
| latency.csv | `Data set of latency metric in CSV format` |
| requirements.txt | `Python dependecies for the app` |
| | |

### Installation

* Python and pip

1. To install `python` and `pip`, check the documentation [here](https://www.python.org/downloads/).

### Configuration

* Python

1. Install `NumPy` package with the following command:

* `pip install numpy`

2. Install `matplotlib` library with this command:

* `pip install matplolib`

Alternatively, you can just run the following command:

`pip install -r requirements.txt`

### Usage

* Histogram

```shell
cd python
python histogram.py
```

* Latency Analysis

```shell
cd python
python latency.py latency.csv
```

Now you can try changing the variable `P` to see other calculated percentile values:

```python
P = 50
```

## End of Document
