# Proyecto 4 – WDI Atlas Economy

Este proyecto construye un panel país-año (2010–2023) con indicadores WDI (Banco Mundial) y realiza:
- limpieza y preparación de datos
- análisis exploratorio (EDA)
- regresión OLS para explicar log(PIB per cápita)

> Nota: el enunciado original apuntaba a “comercio”, pero al no contar con un dataset público directo en el material, se usó WDI por reproducibilidad.

## Estructura
- `notebooks/`: notebook del flujo completo
- `src/`: scripts de descarga/limpieza
- `outputs/data/`: CSV finales
- `outputs/figures/`: figuras exportadas
- `report/`: informe en PDF
