# da_proyecto_eda_python
- Proyecto EDA: Campañas de marketing de un banco portugués
- Proyecto del Módulo 8 (Python for data) | Data&Analytics v3 | thePower
- **Objetivo**:Analizar qué factores se asocian a la contratación de un depósito a plazo (`y`).


## SESION 01
- **Sesión 1:** creación del repositorio, estructura de carpetas, entorno virtual y datos en bruto.
- **Notas:** Solamente se ha instalado pandas (con numpy), matplotlib y seaborn.

**Resumen de la sesión 01**  
- Repositorio: creado en GitHub como público, con README y .gitignore de Python, y clonado en local.
- Estructura: carpetas data/raw, data/processed, notebooks, src y reports/figures, más src/utils.py.
- Entorno: .venv creado y activado, con pandas, numpy, matplotlib y seaborn instalados.
- Dependencias: requirements.txt generado con pip freeze.
- Datos: bank-additional.csv y customer-details.xlsx guardados en data/raw/, sin modificar.
- Git: autenticación resuelta y primer commit subido, con un borrador de README.

**Resumen de la sesión 02**
- Objetivo: cargar e inspeccionar los datos sin limpiar nada.
- CSV: cargado (comprobando el separador) y revisado con shape, info, describe, nulos, duplicados, nunique y categorías de las columnas de texto.
- Excel: 3 hojas cargadas con sheet_name=None (diccionario de DataFrames), comparando dimensiones, columnas, nulos y duplicados.
- Claves: revisados tipo y formato de id_ (CSV) e ID (Excel) de cara al merge.
- Entregable: lista de problemas detectados en Markdown, que será el guion de limpieza.
- Git: commit y push con el notebook 01.