# Kiosko Challenge: 
The objective of this project is to create a model that can support elements that interfere with the calculation of future sales units.

## Vision
Retailers face challenges in efficient inventory management due to variability in product sales, which is influenced by multiple factors such as promotions, seasonality, and special events. An accurate sales prediction model will help reduce storage costs, minimize losses from unsold products, and improve product availability in stores.

## Project Struture

```bash
├── data
│   ├── holidays_events.csv
│   ├── items.csv
│   ├── sample_submission.csv
│   ├── stores.csv
│   ├── test.csv
│   ├── train.csv
│   └── transactions.csv
├── docs
│   ├── Challenge-Data-Scientist.pdf
│   └── Presentación de Resultados.pdf
├── EDA.ipynb
├── Linear_SGD_train.ipynb
├── README.md
├── requirements.txt
├── Resize_train.ipynb
├── utils
│   ├── helper_functions.py
│   ├── __init__.py
│   └── reg_helper_functions.py
└── XGBoost_train.ipynb

3 directories, 18 files
```
## Data

Once you have downloaded the `data.sip` file to your local directory, you will need to place the content in a root folder named `/data`:

```bash
mkdir data
```

```bash
unzip data.zip -d data/
```

## Enviroment Setup

### Setup Local enviroment 

```bash
python3.10 -m venv env
```

```bash
source env/bin/activate
```

```bash
pip install -r app/requirements.txt
```