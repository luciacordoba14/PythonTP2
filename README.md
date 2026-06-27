# Trabajo Práctico 2: Swing o no swing, esa es la cuestión

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

3. Correr las notebooks que se encuentran en la carpeta `notebooks` en orden