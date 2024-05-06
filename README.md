# Documentación de la Página Web

Este documento proporciona una guía básica sobre la estructura y el contenido de la página web construida con Astro.

## Contenido

1. [Introducción](#introducción)
2. [Estructura de Carpetas](#estructura-de-carpetas)
3. [Requisitos del Sistema](#requisitos-del-sistema)
4. [Instalación](#instalación)
5. [Uso](#uso)
6. [Contribución](#contribución)
7. [Licencia](#licencia)

## Introducción

La página web "Marmoleria Verona" es un proyecto construido con Astro, en donde tenemos la intencion de destacar los productos y servicios de la empresa, y reforzar la identidad de la marca de la misma.

## Estructura de Carpetas

La estructura de carpetas del proyecto es la siguiente:
```
|-- .astro/                # Carpeta de configuración de Astro
|-- components/            # Componentes reutilizables de Astro
|   |-- Header.astro       # Componente de encabezado
|   |-- Footer.astro       # Componente de pie de página
|-- public/                # Archivos públicos (imágenes, etc.)
|   |-- assets/               # Carpeta de imágenes
|          |-- bachas/               # Carpeta contenedora de img de bachas
|               |-- 100e/            # carpeta contenedora de bachas modelos 100e
|                   |-- image1.jpg          # Ejemplo de imagen
|               |-- 200/             # carpeta contenedora de bachas modelos 200
|                   |-- image1.jpg          # Ejemplo de imagen
|               |-- 300/             # carpeta contenedora de bachas modelos 300
|                   |-- image1.jpg          # Ejemplo de imagen
|       |-- image1.jpg          # Ejemplo de imagen
|       |-- image2.png          # Ejemplo de imagen
|-- layouts/               # Archivos de plantillas
|   |-- layout.astro/         # Archivo estructural de cada página
|-- src/                   # Archivos fuente del proyecto
|   |-- pages/             # Páginas principales del sitio
|       |-- index.astro    # Página de inicio
|       |-- about.astro    # Página "Acerca de"
|       |-- contact.astro  # Página de contacto
|-- package.json           # Archivo de configuración de npm
|-- README.md              # Documentación del proyecto
```
Las imagenes de las bachas, algunos modelos, cambian solo la profunidad, y se reciclan las imagenes de otras carpetas.

## Requisitos del Sistema

- Node.js (versión X.X.X o superior)
- Navegador web moderno (Google Chrome, Mozilla Firefox, Safari, etc.)

## Licencia

Todos los derechos reservados de Marmoleria Verona
Este proyecto está bajo la [Licencia MIT](LICENSE).

