# qgis-ndvi-analisis-zonas-loteA1

![QGIS](https://img.shields.io/badge/QGIS-3.x-green?logo=qgis)
![Sentinel-2](https://img.shields.io/badge/Sensor-Sentinel--2-blue)
![Estado](https://img.shields.io/badge/Estado-Completo-brightgreen)

## Descripción

Delimitación de zonas de manejo por NDVI para un lote de cultivo (Lote A1),
desarrollado como ejercicio de un curso de QGIS en agricultura de precisión.
El flujo cubre cálculo raster, poligonización, disolución y estadísticas zonales.

## Vista previa

![Mapa NDVI Lote A1](outputs/LOTEA1_PAULINASARDI.png)

## Resultados

| Zona | NDVI medio | Área (ha) | Vigor  |
|------|------------|-----------|--------|
| 1    | 0,256      | 5,45      | Bajo   |
| 2    | 0,492      | 36,73     | Alto   |
| 3    | 0,431      | 15,91     | Medio  |

## Flujo de trabajo

1. Cálculo de NDVI — Calculadora Raster
2. Poligonizar raster → capa vectorial
3. Disolver 56 fragmentos en 3 zonas limpias
4. Estadísticas Zonales — NDVI medio por zona
5. Exportación de mapa desde Diseñador de impresión

## Herramientas y datos

- QGIS 3.x
- Google Satellite (capa base XYZ)
- Herramientas clave: Calculadora Raster, Poligonizar, Disolver, Estadísticas Zonales

## Autora

**Paulina Sardi** —  
[LinkedIn](https://www.linkedin.com/in/paulinasardi) · [GitHub](https://github.com/paulinasardi)
