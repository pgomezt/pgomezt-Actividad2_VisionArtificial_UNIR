# Actividad2_VisionArtificial_UNIR
Repositorio con codigo python para la Actividad 2

Autores:
  - Mijael Montaño
  - Yileny Chitiva
  - Edwin Torrado
  - Paulo Gomez

# 🧪 Filtros Espaciales y Morfológicos – Visión Artificial

Este repositorio contiene un sistema interactivo desarrollado en Jupyter Notebook para la exploración, combinación y análisis de técnicas de **mejora de imágenes** mediante filtros **espaciales** y **morfológicos**.  
Fue construido como parte de una actividad académica para el curso de **Visión Artificial** (UNIR).

## 🎯 Objetivos del proyecto

- Aplicar filtros espaciales y morfológicos a imágenes reales en escala de grises.
- Permitir la **combinación secuencial de filtros** en tiempo real.
- Visualizar el efecto de cada filtro sobre la imagen y su histograma.
- Facilitar la exploración mediante una interfaz interactiva basada en `ipywidgets`.

## 🛠️ Tecnologías utilizadas

- Python 3.x  
- OpenCV (`cv2`)  
- NumPy  
- Matplotlib  
- ipywidgets  
- Jupyter Notebook

## 🔍 Filtros implementados

### Filtros espaciales (E):

- Brillo (slider)
- Contraste (slider)
- Gamma (slider)
- Logaritmo (checkbox)
- Media (checkbox)
- Negativo (checkbox)
- Sobel (checkbox + kernel)
- Scharr (checkbox)
- Laplaciano (checkbox + kernel)

### Filtros morfológicos (M):

- Erosión (checkbox + kernel)
- Dilatación (checkbox + kernel)
- Apertura (checkbox + kernel)
- Cierre (checkbox + kernel)
- Top-hat (checkbox + kernel)
- Black-hat (checkbox + kernel)
- Gradiente morfológico (checkbox + kernel)

Además, es posible seleccionar el **tipo de elemento estructurante** (`cuadrado`, `cruz`, `elipse`) para los filtros morfológicos.

## 🖼️ Visualización

El sistema muestra:
- La imagen original y la imagen transformada, lado a lado.
- El histograma de ambas imágenes, para análisis cuantitativo.
- La actualización es en tiempo real y puede combinar múltiples filtros a la vez.

## 🚀 Cómo usar

1. Clona el repositorio o descarga el archivo `.ipynb`.
2. Abre el notebook en Jupyter o VSCode.
3. Reemplaza la ruta de imagen en la celda correspondiente:

```python
ruta_imagen = 'ruta/a/tu/imagen.jpg'
```

4. Ejecuta todas las celdas.
5. Usa los sliders y checkboxes para experimentar.

## 📁 Estructura del proyecto

```
Filtros/
├── Filtros_Completo_Interactivo_E_M.ipynb
├── README.md
├── ejemplos/
│   └── ejemplo1.png
├── utils/
│   └── calculos_metrica.py  # (si se añaden métricas como PSNR)
```

## 📄 Créditos y licencia

Proyecto desarrollado por [Tu Nombre]  
Universidad Internacional de La Rioja – Visión Artificial – 2025  
Este repositorio es solo para fines educativos.  
Licencia: [MIT License](LICENSE)
