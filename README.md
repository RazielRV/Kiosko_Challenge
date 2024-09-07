# Kiosko Challenge: 
El objetivo de este proyecto es crear un modelo que pueda soportar elementos que interfiera en el cálculo de unidades de venta a futuro.

## Vision
La cadena de tiendas enfrenta desafíos en la gestión eficiente de inventarios debido a la variabilidad en las ventas de productos, que se ve influenciada por múltiples factores como promociones, estacionalidad y eventos especiales. Un modelo preciso de predicción de ventas ayudará a reducir costos de almacenamiento, minimizar pérdidas por productos no vendidos y mejorar la disponibilidad de productos en las tiendas.

## Estructura del proyecto

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

Una vez que hayas descargado en tu local el arcivo  `data.sip`,deberás alojar el cotenido en un carpeta en raíz conel nombre de `/data`:

```bash
mkdir data
```

```bash
unzip data.zip -d data/
```

## Configuración del ambiente

### Crear ambiente local

```bash
python3.10 -m venv env
```

```bash
source env/bin/activate
```

```bash
pip install -r app/requirements.txt
```