---
layout: post
title: "Cómo instalar LaTeX"
---

LaTeX es un sistema de composición de textos, orientado a la creación de documentos escritos que presenten una alta calidad tipográfica. 

## Windows
Para instalar LaTeX necesitas instalar dos componentes:

* Una distribución de LaTeX ([MiKTeX](https://miktex.org/download)). 

* Un editor de texto ([TeXstudio](https://www.texstudio.org),[TeXnicCenter](https://www.texniccenter.org) entre otros ). Para escribir tus documentos.

El proceso de instalación dura alrededor de una hora aproximadamente.

Descargar el archivo [protext](https://ctan.math.illinois.edu/systems/windows/protext/)

Nota: El archivo protext contiene todos los archivos que se necesitan para instalar LaTeX(MikTeX y TeXstudio).

1. Descomprimir el archivo protext-3.2, extrayendo todos los archivos.

2. Doble clik en Setup, selecionar Language: English

3. Click en MiKTeX: Install
  1. Click en _I accept the MiKTeX conditions_
  2. Click en Next
  3. Click en Next
  4. Click en Next
  5. Click en Next
  6. Click en Start
  7. Click en Next
  8. Click en Next
  9. Click en Close

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
Descargar el archivo [MacTeX](http://tug.org/mactex/mactex-download.html). 
Después de la descarga, haga doble clic en MacTeX.pkg para instalarlo. Siga las instrucciones sencillas. La instalación en un Macintosh reciente toma unos diez minutos. MacTeX instala TeX Live (la distribución de Tex) y el editor TeXShop.

Para probar que la instalación se haya hecho correctamente:
1. Crear una carpeta en el escritorio 
2. Abrir TeXShop y pegar lo siguiente:

```
\documentclass{article}

\usepackage[utf8]{inputenc}

\begin{document}

Mi primer documento en LaTeX.

\end{document}
```

## Online
Trabaja desde cualquier lugar, sin necesidad de instalar nada, accede a tu trabajo desde cualquier parte del mundo con 
[Overleaf](https://es.overleaf.com)

Overleaf contiene una gran variedad de plantillas de diferente índole como tesis, artículos, posters, trípticos, presentaciones(beamer) y muchos más. Hay diversas Universidades alrededor del mundo con plantillas predefinidas para tesis y presentaciones en Overleaf, una simple búsqueda como *thesis templates overleaf* en **Google** dará como resultado una galería de plantillas([templates](https://es.overleaf.com/latex/templates)).
