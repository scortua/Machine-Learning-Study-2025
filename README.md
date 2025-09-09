# Machine Learning Study 2025

Repositorio de apoyo y ejercicios prácticos para el aprendizaje de Machine Learning (curso 2025).

Contenido: notebooks Jupyter, datasets de ejemplo y material didáctico organizado por temas y proyectos.

## Estructura principal del repositorio

- `2.Contexto/` — Material de contexto y lecturas sobre IA.
- `3.Preparacion/` — Notebooks de preparación de datos y fundamentos (NumPy, pandas, Matplotlib). Contiene además la carpeta `datasets/` con ejemplos (p. ej. `creditcard.csv`).
- `4.Librerias/` — Ejemplos y recursos de librerías auxiliares.
- `5.Machine Learning/` — Material general de ML y ejemplos.
- `6.Regresion/`, `8.Support Vector Machine SVM/`, `9.Arboles/`, `11.Clustering/`, `14.Redes Neuronales Deep Learning/` — Carpeta por técnica o familia de algoritmos con notebooks y visualizaciones.
- `7.Proyecto ML/` — Notebooks de proyectos aplicados y casos prácticos.
- `10.Seleccion Extraccion/` — Técnicas de extracción y selección de características.
- Notebooks sueltos y archivos de ejemplo en la raíz (`Mi_Primer_Desarrollo_IAGen.ipynb`, etc.).

> Nota: el archivo `.gitignore` está configurado para excluir algunos archivos pesados como `3.Preparacion/datasets/` y notebooks grandes; revisa `.gitignore` antes de añadir datasets al repo.

## Objetivo

Ofrecer un recorrido práctico y reproducible para aprender: exploración y limpieza de datos, ingeniería de características, selección de modelos, entrenamiento, evaluación y análisis de resultados mediante notebooks interactivos.

## Requisitos sugeridos

- Sistema: Windows, macOS o Linux.
- Python 3.8 o superior.
- Entorno para ejecutar notebooks: Jupyter Notebook o JupyterLab.
- Librerías (sugeridas): NumPy, pandas, scikit-learn, Matplotlib, Seaborn, SciPy, notebook.

Instalación rápida (PowerShell):

```powershell
python -m pip install --upgrade pip
pip install numpy pandas scikit-learn matplotlib seaborn scipy jupyter
```

Si prefieres, crea un entorno virtual antes de instalar:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt   # si existe
```

## Cómo usar los notebooks

1. Abre el repositorio en VS Code (con la extensión de Jupyter) o en JupyterLab.
2. Activa el entorno Python recomendado.
3. Abre el notebook que quieras y ejecuta las celdas en orden.
4. Si un notebook requiere datasets, mira en `3.Preparacion/datasets/` o lee la cabecera del notebook para instrucciones específicas.

## Datasets y archivos grandes

- Algunos datasets pueden estar excluidos por `.gitignore` (p. ej. `3.Preparacion/datasets/` o `datasets.rar`). Si faltan datos, busca archivos comprimidos en la carpeta `3.Preparacion/` o consulta las notas del notebook.
- Para datos sensibles o grandes, evita subirlos al repositorio; usa almacenamiento externo y apunta a la ruta local en los notebooks.

## Git y control de versiones

- Si necesitas reescribir historial para quitar datos o commits (por ejemplo eliminar un commit que contiene datos sensibles), haz una copia de la rama (`git branch backup-<branch>-before-rewrite`) antes de reescribir.
- Para eliminar un commit públicamente compartido, se recomienda `git revert` en lugar de `git push --force` para evitar problemas a otros colaboradores.

## Contribuciones

1. Crea una rama para tu cambio: `git checkout -b feature/mi-cambio`.
2. Haz commits atómicos y documenta el propósito.
3. Abre un pull request o comparte el patch.

Si quieres que añada un `requirements.txt`, instrucciones más detalladas por notebook o una versión en inglés del README, puedo generarlas.

---

Última actualización: 2025
