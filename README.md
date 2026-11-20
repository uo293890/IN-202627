# Segmentación no lineal de hogares en el sector supermercado mediante Manifold Learning

Trabajo de teoría de Inteligencia de Negocio, curso 2026-27 (Universidad de Oviedo).

**Autores:** Fran (datos), Ringo (métodos), Óscar (segmentos)

## Datos
Descargar *dunnhumby – The Complete Journey* de Kaggle y copiar en `datos/` estos archivos:
`transaction_data.csv`, `product.csv`, `hh_demographic.csv`, `coupon_redempt.csv`.
La carpeta `datos/` no se sube al repositorio (los archivos superan el límite de GitHub).

## Ejecución
Ejecutar los notebooks en este orden:
1. `notebooks/01_datos.ipynb` → genera `salidas/hogares.csv` y `salidas/hogares_sin_escalar.csv`
2. `notebooks/02_metodos.ipynb` → genera `salidas/mapas.csv` y `salidas/metricas.csv`
3. `notebooks/03_segmentos.ipynb` → segmentos de hogares y figuras finales

## Requisitos
pip install -r requirements.txt