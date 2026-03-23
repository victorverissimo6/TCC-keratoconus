# Diagnóstico Explicável de Ceratocone com CNNs

Código dos experimentos do TCC de Victor Veríssimo — UFCG 2024.

## Dataset
Keratoconus Detection — disponível em:  
https://www.kaggle.com/datasets/alitimemy/keratoconus-detection

## Experimentos
- `exp1.ipynb` — Treino UNIFESP, teste CRO
- `exp2.ipynb` — Dados mesclados, 3 classes
- `exp3.ipynb` — Dados mesclados, Normal vs KC

## Requisitos
- Python 3.10+
- torch
- torchvision
- albumentations
- grad-cam
- scikit-learn
- matplotlib
- seaborn
- numpy
- Pillow
- pandas

Instalar com:
```
pip install torch torchvision albumentations grad-cam scikit-learn matplotlib seaborn numpy Pillow pandas
```
