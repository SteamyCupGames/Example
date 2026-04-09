# Ejemplo de Repositorio para Aprender GitHub

Este repositorio es un ejemplo educativo diseñado para enseñar a los estudiantes cómo utilizar GitHub de manera efectiva. Incluye un proyecto práctico de análisis espacial y detección de objetos utilizando YOLOv8, que sirve como caso de estudio para demostrar conceptos de control de versiones, colaboración y gestión de proyectos en GitHub.

## Descripción del Proyecto

El proyecto principal consiste en un notebook de Jupyter (`Análisis_Espacial_y_Detección_de_Objetos.ipynb`) que utiliza el modelo YOLOv8 Nano para detectar y contar objetos en tres imágenes representativas de lugares icónicos:

- Cruce de Shibuya (Japón)
- Times Square (Nueva York, EE.UU.)
- Gran Vía (Madrid, España)

El notebook incluye:
- Carga del modelo preentrenado YOLOv8n
- Una función personalizada para detectar objetos y generar resúmenes de conteo
- Análisis de resultados con métricas de precisión, recall y IoU (Intersection over Union)
- Visualizaciones de las detecciones realizadas

## Estructura del Repositorio

```
Example/
├── README.md                 # Este archivo
├── LICENSE                   # Licencia del proyecto
├── help.txt                  # Archivo de ayuda adicional
├── Data/                     # Carpeta con imágenes de prueba
│   ├── shibuya.jpg
│   ├── times_square.jpg
│   └── gran_via.jpg
└── Notebooks/
    ├── Análisis_Espacial_y_Detección_de_Objetos.ipynb
    └── yolov8n.pt            # Modelo preentrenado YOLOv8 Nano
```

## Requisitos Previos

- Python 3.8 o superior
- Jupyter Notebook o JupyterLab
- Bibliotecas: ultralytics, opencv-python, matplotlib, pillow

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/example.git
   cd example
   ```

2. Crea un entorno virtual (recomendado):
   ```bash
   python -m venv env
   source env/bin/activate  # En Windows: env\Scripts\activate
   ```

3. Instala las dependencias:
   ```bash
   pip install ultralytics opencv-python matplotlib pillow
   ```

## Uso

1. Abre Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Navega a la carpeta `Notebooks/` y abre `Análisis_Espacial_y_Detección_de_Objetos.ipynb`

3. Ejecuta las celdas del notebook paso a paso para ver la detección de objetos en las imágenes.

## Contribuciones

Este repositorio está diseñado para fines educativos. Si eres estudiante, puedes:
- Hacer un fork del repositorio
- Crear una rama para tus cambios
- Hacer commits descriptivos
- Abrir un pull request

Aprende sobre:
- Ramas (branches)
- Commits
- Pull requests
- Issues
- Gestión de conflictos

## Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## Recursos Adicionales

- [Documentación de GitHub](https://docs.github.com/)
- [Ultralytics YOLO](https://docs.ultralytics.com/)
- [Jupyter Notebook](https://jupyter.org/)
