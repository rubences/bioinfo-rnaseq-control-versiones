# bioinfo-rnaseq-control-versiones

Repositorio de ejemplo para la asignatura **Introducción a la Programación Científica**. El proyecto propone un flujo de trabajo sencillo para el análisis de expresión génica a partir de datos de RNA-Seq, con énfasis en el control de versiones, la organización del proyecto y la documentación reproducible.

## Objetivo

Organizar un proyecto de bioinformática en GitHub para analizar un conjunto de muestras de RNA-Seq, dejando separadas las carpetas de datos, scripts y resultados, y registrando los cambios mediante commits descriptivos.

## Estructura del proyecto

```text
bioinfo-rnaseq-control-versiones/
├── README.md
├── LICENSE
├── .gitignore
├── data/
│   ├── raw/
│   └── processed/
├── scripts/
├── results/
│   └── figures/
└── docs/
```

## Instrucciones de uso

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/rubences/bioinfo-rnaseq-control-versiones
   cd bioinfo-rnaseq-control-versiones
   ```
2. Añadir los archivos del proyecto en las carpetas correspondientes.
3. Registrar cambios mediante commits descriptivos.
4. Subir los cambios a GitHub.

## Comandos principales utilizados

```bash
git init
git branch -M main
git add .
git commit -m "Initial commit: project structure and documentation"
git remote add origin https://github.com/rubences/bioinfo-rnaseq-control-versiones.git
git push -u origin main
```

## Ejemplos de commits adecuados

- `docs: add project README and objectives`
- `chore: create initial folder structure`
- `feat: add first RNA-Seq preprocessing script`
- `results: add exploratory expression plots`

## Licencia

Este proyecto se distribuye bajo licencia **MIT**.
