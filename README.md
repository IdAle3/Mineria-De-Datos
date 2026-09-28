#  Minería de Datos — Análisis de Crímenes en Chicago

Proyecto académico desarrollado para la materia de **Minería de Datos** de la Licenciatura en Ciencias Computacionales.

El proyecto consiste en el análisis de un conjunto de datos sobre **crímenes registrados en la ciudad de Chicago**, utilizando Python y diferentes técnicas de análisis, visualización, estadística y aprendizaje automático.

A lo largo de las prácticas se trabajó desde la **limpieza y preparación de los datos** hasta la implementación de modelos como **regresión lineal y K-Nearest Neighbors (KNN)**, con el objetivo de identificar patrones y obtener información relevante a partir de los datos.

---

##  Objetivo

El objetivo principal del proyecto fue aplicar las diferentes etapas de un proceso de minería de datos sobre un conjunto de datos real.

Durante el desarrollo se realizaron actividades como:

- Limpieza y transformación de datos.
- Análisis exploratorio.
- Estadística descriptiva.
- Visualización de datos.
- Identificación de patrones y tendencias.
- Análisis estadístico.
- Regresión lineal.
- Implementación de modelos de clasificación mediante KNN.
- Interpretación de los resultados obtenidos.

---

##  Dataset

El proyecto utiliza información relacionada con crímenes registrados en **Chicago**.

El conjunto de datos original contiene aproximadamente **1,456,714 registros**, por lo que para las diferentes prácticas se utilizaron versiones reducidas y procesadas del dataset.

Entre los archivos generados se encuentran:

- `Crimenes_Chicago_Resumido.csv` — versión reducida de aproximadamente 60,000 registros.
- `Crimenes_Chicago_Limpio_7000.csv` — conjunto de 7,000 registros después del proceso de limpieza y transformación.

Esto permitió trabajar con información más manejable sin perder las variables necesarias para los diferentes análisis realizados.

---

##  Tecnologías y herramientas

El proyecto fue desarrollado principalmente utilizando:

- **Python**
- **Pandas** — manipulación y análisis de datos.
- **Matplotlib** — generación de visualizaciones.
- **Seaborn** — visualización estadística.
- **Scikit-learn** — implementación de modelos de aprendizaje automático.
- **SciPy** — análisis estadístico.
- **Statsmodels** — modelos y pruebas estadísticas.
- **Git / GitHub** — control de versiones y documentación.

---

##  Desarrollo del proyecto

El análisis fue realizado de manera progresiva a través de diferentes prácticas.

###  Práctica 1 — Limpieza y preparación de datos

Se realizó el proceso de depuración y transformación del dataset original para obtener conjuntos de datos adecuados para las siguientes etapas del análisis.

**Contenido:**
- Dataset limpio de 7,000 registros.
- Dataset resumido de aproximadamente 60,000 registros.
- Script de limpieza y transformación.

---

###  Práctica 2 — Estadística descriptiva

Se aplicaron técnicas de estadística descriptiva para conocer las características principales de los datos e identificar el comportamiento de las variables.

También se trabajó con la representación y organización de la información mediante un diagrama ER.

---

###  Práctica 3 — Visualización de datos

Se construyeron diferentes gráficas para representar visualmente la información e identificar tendencias relacionadas con los crímenes registrados.

Las visualizaciones permitieron analizar aspectos como:

- Tipos de crimen.
- Distribución de los registros.
- Horarios.
- Distritos.
- Frecuencia de determinados delitos.

---

###  Práctica 4 — Análisis estadístico

Se profundizó en el análisis de los datos mediante nuevas visualizaciones y técnicas estadísticas para comparar variables y estudiar posibles relaciones entre ellas.

---

###  Práctica 5 — Regresión lineal

Se implementaron modelos de **regresión lineal** para estudiar relaciones entre variables y evaluar la capacidad de los datos para explicar o estimar determinados comportamientos.

Los resultados fueron representados mediante diferentes gráficas para facilitar su interpretación.

---

###  Práctica 6 — Modelo KNN

Se implementó el algoritmo **K-Nearest Neighbors (KNN)** como técnica de aprendizaje automático.

El objetivo fue explorar la posibilidad de clasificar registros utilizando características disponibles en el conjunto de datos y evaluar el comportamiento del modelo.

---

###  Prácticas 7, 8 y 9 — Análisis complementario

En las últimas prácticas se continuó trabajando con técnicas de minería y análisis de datos, complementando los resultados obtenidos en las etapas anteriores.

Cada práctica incluye sus respectivos scripts y visualizaciones para documentar el proceso realizado.

---

##  Principales resultados

El análisis permitió identificar diferentes patrones dentro de los registros estudiados.

Entre los resultados más relevantes se encontró una **distribución desigual de los crímenes**, tanto por tipo como por ubicación y horario. Esto permite identificar determinadas combinaciones de variables en las que existe una mayor concentración de registros.

La **hora del día** también mostró ser una variable relevante dentro de los análisis realizados, indicando que existen patrones temporales asociados con determinados tipos de crimen.

Los modelos de clasificación mostraron además que algunas características disponibles en el dataset contienen información suficiente para diferenciar ciertos tipos de delitos, demostrando cómo las técnicas de aprendizaje automático pueden utilizarse para encontrar patrones que no siempre son evidentes mediante una revisión directa de los datos.

---

##  Conclusiones

Este proyecto me permitió recorrer diferentes etapas de un proceso de minería de datos, comenzando con información sin procesar y avanzando hasta la aplicación de técnicas estadísticas y modelos de aprendizaje automático.

Los resultados muestran que variables como el **tipo de crimen, distrito y horario** permiten identificar patrones importantes dentro de los registros analizados.

Más que establecer relaciones causales, estos análisis permiten **detectar tendencias y concentraciones dentro de los datos**, proporcionando información que podría utilizarse como apoyo para análisis posteriores y para una toma de decisiones basada en evidencia.

A nivel técnico, el proyecto me permitió fortalecer mis conocimientos en **Python, manipulación de datos, visualización, estadística y machine learning**, además de practicar la interpretación y comunicación de resultados obtenidos a partir de un conjunto de datos real.

---

##  Estructura del repositorio

```text
Mineria-De-Datos/
│
├── Practica1/
│   ├── Crimenes_Chicago_Limpio_7000.csv
│   ├── Crimenes_Chicago_Resumido.csv
│   └── limpieza_ds.py
│
├── Practica2/
│   ├── Estadisticas.py
│   └── DIAGRAMA ER.png
│
├── Practica3/
│   ├── practica3.py
│   └── graficas/
│
├── Practica4/
│   ├── practica4.py
│   └── img/
│
├── Practica5/
│   ├── practica5.py
│   └── img/
│
├── Practica6/
│   ├── practica6.py
│   └── img/
│
├── Practica7/
├── Practica8/
└── Practica_9/
```

---

##  Ejecución

Para ejecutar los scripts del proyecto es necesario contar con **Python** instalado.

### 1. Clonar el repositorio

```bash
git clone https://github.com/IdAle3/Mineria-De-Datos.git
```

### 2. Acceder al repositorio

```bash
cd Mineria-De-Datos
```

### 3. Instalar las principales dependencias

```bash
pip install pandas matplotlib seaborn scikit-learn scipy statsmodels
```

### 4. Ejecutar una práctica

Por ejemplo:

```bash
python Practica3/practica3.py
```

Algunas prácticas utilizan archivos CSV incluidos dentro del repositorio, por lo que puede ser necesario verificar las rutas utilizadas dentro de cada script antes de su ejecución.

---

##  Habilidades desarrolladas

Este proyecto me permitió trabajar y reforzar habilidades relacionadas con:

- Preparación y limpieza de datos.
- Análisis exploratorio de datos.
- Visualización e interpretación de información.
- Estadística aplicada.
- Programación en Python.
- Uso de librerías especializadas en análisis de datos.
- Regresión.
- Clasificación mediante Machine Learning.
- Interpretación y comunicación de resultados.

---

##  Autora

**Idalia Delgado**  
Licenciatura en Ciencias Computacionales  
Universidad Autónoma de Nuevo León
