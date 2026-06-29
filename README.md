# Trabajo Práctico 2: Swing o no swing, esa es la cuestión

Este trabajo tiene como objetivo el desarrollo de un proyecto de *machine learning* para estimar la probabilidad de que un bateador haga *swing* ante un determinado lanzamiento, en un partido de *baseball*. 

El conjunto de datos corresponde a temporadas de baseball, con información sobre cada lanzamiento y variables que informan sobre tipo de lanzamiento, distancias, velocidad, entre otras. El desafío principal radica en la definición de la variable respuesta, que se encuentra categorizada, pero se requiere en forma dicotómica que indique si el bateador realizó o no un *swing*.

Las notebooks incluidas en este repositorio permiten reproducir todo el flujo de trabajo del proyecto, desde el análisis exploratorio y el preprocesamiento de los datos hasta la construcción, comparación y evaluación de distintos modelos de clasificación, finalizando con la generación de las predicciones del modelo seleccionado. 

### Estructura

```text
.
├── .gitignore
├── .python-version
├── README.md
├── NOTAS.md
├── pyproject.toml
├── notebooks
│   ├── 01-AnalisisDescriptivo.ipynb
│   ├── 02-ParticionDatos.ipynb
│   ├── 03-AjusteXGBoost.ipynb
│   ├── 04-RegresionLogistica.ipynb
│   ├── 05-ComparacionModelos.ipynb
│   └── 06-PrediccionesFinales.ipynb    
└── uv.lock
```

## Instrucciones

1.  Clonar el repositorio

    ```bash
    git clone https://github.com/luciacordoba14/PythonTP2.git
    cd PythonTP2
    ```

2.  Instalar dependencias con `uv`

    Este proyecto usa `uv` para administrar Python y las dependencias. Ejecutar:

    ```bash
    uv sync
    ```

3. Crear una carpeta llamada Datos que contenga los dos conjuntos de datos: termporada1.parquet y temporada2.parquet

4. Correr las notebooks que se encuentran en la carpeta `notebooks` en orden. Importante: Debe seleccionarse el entorno virtual recién creado (uv: pythontp2) como Kernel antes de correr la primera celda, para que detecte las librerías instaladas.