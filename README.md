# Gráficos de impactos

Repositorio con un script para generar tres gráficas a partir de datos de cráteres de impacto.

Archivos principales

- `graficas_impactos.py`: script que crea una base de datos SQLite (`impactos.db`) (si no existe) y genera tres imágenes:
  - `grafico_diametro_edad.png`
  - `grafico_crateres_por_pais.png`
  - `grafico_ubicaciones_geograficas.png`
- `libreria.ipynb`: cuaderno asociado (opcional).

Requisitos

- Python 3.8+ (se probó con Python 3.14)
- Paquetes: `pandas`, `matplotlib`

Instalación rápida

```bash
py -m pip install pandas matplotlib
```

Uso

```bash
# Ejecutar el script para crear la base de datos y las gráficas
py graficas_impactos.py
```

Notas

- El script genera `impactos.db` en el mismo directorio; puedes borrarlo si no lo necesitas. 
- Si prefieres usar una base de datos externa, modifica `graficas_impactos.py` para apuntar a la fuente deseada.
