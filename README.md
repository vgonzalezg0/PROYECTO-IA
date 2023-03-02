# PROYECTO RIESGO DE INCUMPLIMIENTO CREDITICIO

## Miembros del grupo
- Aura Molina, CC 1006510913, Ingeniería Industrial

- Valeria González Gonzalez, CC 1000099730, Ingeniería Industrial

- Maryely Isabel Rubio de la Cruz, CC 1116803015, Ingeniería Industrial

## Datos
Los datos del proyecto vienen de la competencia de Kaggle [Home Credit Default Risk](https://www.kaggle.com/competitions/home-credit-default-risk/overview), y se pueden hacer disponibles ejecutando desde cualquier notebook en Colab los siguientes comandos:

**1.** Iniciar sesión en Kaggle, generar New API Token y guardar este archivo

**2.** Leer el token de la API de kaggle para interactuar con su cuenta de kaggle
```python
from google.colab import files
files.upload()
```
**3.** Instalar la biblioteca Kaggle
```python
! pip install kaggle
```
**4.** Hacer un directorio llamado “.kaggle”
```python
! mkdir ~/.kaggle
```
**5.** Copiar el "kaggle.json" en este nuevo directorio
```python
! cp kaggle.json ~/.kaggle/
```
**6.** Asignar el permiso requerido para este archivo
```python
! chmod 600 ~/.kaggle/kaggle.json
```
**7.** Descargar el Dataset de la competencia
```python
! kaggle competitions download -c home-credit-default-risk
```
**8.** Descomprimir el Dataset
```python
! unzip home-credit-default-risk
```
