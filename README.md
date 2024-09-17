# Videos educativos de combinatoria utilizando Manim

Este repositorio contiene el código fuente utilizado para generar videos educativos sobre combinatoria empleando la herramienta Manim. Los videos fueron desarrollados como parte de un proyecto de tesis con el objetivo de ilustrar conceptos clave de combinatoria de manera visual, interactiva y accesible. Además, este proyecto busca proporcionar documentación clara que facilite a otros usuarios el aprovechamiento de Manim en la creación de contenido educativo.

Durante la creación del código, se aprovecharon diversas funcionalidades de Manim de manera variada. Estos distintos casos de uso de Manim son los que se busca documentar en este código.  El desarrollo sigue las convenciones de PEP 8 y los principios del libro Clean Code, lo que facilita que el código se pueda entender, mantener y reutilizar.

## Estructura del Proyecto

Este proyecto incluye cuatro archivos principales, cada uno correspondiente al código que genera las escenas para los videos educativos creados sobre combinatoria. A continuación, se listan los videos y sus enlaces a YouTube:
* Video1-PrincipioMultiplicacionYSuma [link video en YouTube](https://youtu.be/ePPxuT6K6Cg?si=6eOuTOtu87mKtMPv).
* Video2-Permutaciones [link video en YouTube](https://youtu.be/oKf17k7p4GM?si=P4w1DrE1km2NYksn).
* Video3-Combinaciones [link video en YouTube](https://youtu.be/DA367kQNuNk?si=XzI9QgGHI2b4ZcNS).
* Video4-TeoremaDelBinomio [link video en YouTube](https://youtu.be/7FfBGBBckDk?si=H_vxqvjx3WhKTDtO).

La estructura de los archivos es consistente para cada video:
```
<VideoX-titulo>
├── <nombre-archivo>.ipynb
├── imagenes
├── utiles
└── media
      ├── images
      ├── jupyter
      ├── Tex
      └── videos
```
* **<nombre-archivo>.ipynb"**: contiene el código fuente de las escenas utilizadas en el video, detallando cada parte de la animación.
* **imagenes**: carpeta que almacena todas las imágenes en formato SVG utilizadas en las animaciones.
* **utiles**: contiene funciones auxiliares que facilitan el desarrollo de las escenas y la animación..
* **media**: este directorio es automáticamente creado y contiene imágenes, videos y otros archivos generados por Manim y Jupyter.
  * **imagenes**: folder con imagenes generadas con Manim.
  * **jupyter**: contiene el caché de los videos generados desde el Jupyter Notebook.
  * **Tex**: archivos necesarios para manejar objetos LaTeX dentro de las animaciones.
  * **videos**: carpeta donde se almacenan los videos finales generados con Manim.

## Requisitos previos
* Python 3.8+
* Manim para Jupyter Notebooks
* Latex dependencies for Manim
* Un visor de videos como VLC o cualquier otro reproductor compatible con ```.mp4```
  
## Instalacion de Manim para Jupyter con Conda
