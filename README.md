# Laboratorio_Batall-nChocoboyo
# Laboratorio: Batallón Chocoboyo - Técnicas de Render
Laboratorio colaborativo enfocado en la comparación de rendimiento y calidad visual de técnicas de renderizado en gráficos por computadora (Unidad 4).
---

## Integrantes del Equipo

* **Brenda Jiménez García** (Líder del proyecto) - Implementación de Scanline y rasterización de triángulos con z-buffer y sombreado plano.
* **José Enrique Arroyo Sánchez** - Implementación de Ray Tracing.
* **Emerson Avila Ceja** - Implementación de Ambient Occlusion.
* **Barbara Montserrat Juárez Pedro** - Implementación de Comparación de Tabla de tiempos.
* **Uriel Zaid Cruz Juárez** - Implementación de Antialiacing.
---

##  Capturas de las Tres Técnicas

### 1. Scanline (Rasterización de triángulos con z-buffer y sombreado plano)
<img width="777" height="495" alt="image" src="https://github.com/user-attachments/assets/03983fe0-05dd-41dc-bccf-ca7f6baf1ebd" />

### 2. Ray Tracing
<img width="780" height="485" alt="image" src="https://github.com/user-attachments/assets/06e99c96-abf9-4c1f-900d-bbe19e894ee0" />

### 3. Ambient Occlusion
<img width="778" height="486" alt="image" src="https://github.com/user-attachments/assets/28d58d41-42e4-41c6-82cd-dced952508b8" />

---

## Tabla de Tiempos y Rendimiento
<img width="1257" height="762" alt="image" src="https://github.com/user-attachments/assets/5de5c64f-e565-4c46-a6e5-1c56179e3224" />

<img width="1261" height="788" alt="image" src="https://github.com/user-attachments/assets/31341398-d844-45c0-8e6c-87e9e0cac318" />

<img width="1261" height="846" alt="image" src="https://github.com/user-attachments/assets/2f1b6a11-369d-4e47-b028-243e54409c22" />

---

## Conclusión: Calidad contra Tiempo

Tras realizar el análisis comparativo entre las tres técnicas implementadas en el laboratorio, se concluye que:
* **Scanline** ofrece una velocidad sumamente eficiente ideal para aplicaciones en tiempo real (como videojuegos estilo retro o de acción rápida), sacrificando detalles lumínicos complejos.
* **Ray Tracing** proporciona una calidad visual sobresaliente y realista, pero demanda una mayor cantidad de recursos computacionales y un tiempo de procesamiento elevado.
* **Ambient Occlusion** se posiciona como un punto de equilibrio intermedio excelente, mejorando drásticamente la percepción de volumen y profundidad en las esquinas y oclusiones de los objetos sin el costo computacional total de un trazado de rayos completo.
<img width="1257" height="585" alt="image" src="https://github.com/user-attachments/assets/212fef99-03ba-48de-977b-f069b1f3788a" />
