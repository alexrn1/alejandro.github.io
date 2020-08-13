---
layout: post
title: "Cómo instalar LaTeX"
---

LaTeX es un sistema de composición de textos, orientado a la creación de documentos escritos que presenten una alta calidad tipográfica. 
Para instalar LaTeX necesitas instalar dos componentes:

* Una distribución de LaTeX (MiKTeX). 

* Un editor de texto ([TeXstudio] <https://www.texstudio.org>,[TeXnicCenter]<https://www.texniccenter.org> entre otros ). Para escribir tus documentos.

El proceso de instalación dura alrededor de una hora aproximadamente.


## Windows

Descargar el archivo [protext] <https://ctan.math.illinois.edu/systems/windows/protext/>

1. Descomprimir el archivo protext-3.2

2. Doble clik en Setup, selecionar Language: English

3. Click en MiKTeX: Install
  1. Click en _I accept the MiKTeX conditions_
  2. Click Next
  3. Click Next
  4. Click Next
  5. Click Next
  6. Click Start
  7. Click Next
  8. Click Next
  9. Click Close

4. Click en TeXstudio: Install
  1. Install
  2. Close

5. Exit proTeXt


Para probar que la instalación se haya hecho correctamente:
1. Crear una carpeta en el escritorio 
2. Abrir TeXstudio y pegar lo siguiente
```
\documentclass{article}
\usepackage[utf8]{inputenc}

\begin{document}

Mi primer documento en LaTeX.

\end{document}
```

## MacOS

## Online
Trabaja desde cualquier lugar, sin necesidad de instalar nada, accede a tu trabajo desde cualquier parte del mundo con 
[Overleaf]<https://es.overleaf.com>

Overleaf contiene una gran variedad de plantillas de diferente indole como tesis, artículos, posters, tripticos, presentaciones(beamer) y muchos más. Además Overleaf es usado por millones de estudiantes y académicos alrededor del mundo.
