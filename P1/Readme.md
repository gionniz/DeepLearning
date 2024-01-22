# Detección de Rostros Reales y Falsos con Redes Neuronales Convolucionales (CNN) en PyTorch
**Practica de la asignatura de Aprendizaje Automatico II - Curso 2023/2024**

### Link
El **codigo** y el **material** utilizado està disponibile en github y alos siguientes enlaces:  

Codigo  
[GitHub - gionniz](https://github.com/gionniz/DeepLearning/P1 "GitHub gionniz")

### Autores
Trabajo realizado por:
- **Giovanni Sgambato** y **Agata Cavigioli**

## Descripcion
En este proyecto, hemos desarrollado una red neuronal convolucional (en varias configuraciones) con la capacidad de clasificar entre imágenes de rostros reales y falsificados por expertos.
Se realizaron 2 intentos de modelo con diferentes arquitecturas, en particular, con un número diferente de capas convolucionales, y varias pruebas de transformaciones en fase de pre-procesamiento, para luego evaluar las diferencias de rendimiento.
Para este ejercicio, se utilizò un notebook en google colab con un entorno python y runtime T4 gpu. 
La metodologia aplicada se compone de diferentes etapas:
1) Pre-procesamiento de Datos 
2) Arquitectura del Modelo
3) Entrenamiento
4) Evaluacion

**Regularizacion**
En todas la fases, para intentar minimizar el sobreajuste, haciendo que nuestros algoritmos generalicen bien y la red performe correctamente, hemos utilizado varias tecnicas de regularizacion que se aplican al modelo o los datos, como:
DropOut, arreglando parametros como el decaimiento de pesos, batch normalization, y data augmentation.

# Fuentes y tecnologías utilizadas
- [Conda](https://docs.conda.io/en/latest/)
- NumPy
- scikit-learn
- Matplotlib
- PyTorch

# Contenidos del repositorio
- codigo, tambien diponible y funcionante direcatmente en Colab https://colab.research.google.com/drive/18Ph5HcQ09lnyFJVNiKgO5sJ4gWXemQTo#scrollTo=14FSutu42D6U 
- memoria de trabajo .pdf

