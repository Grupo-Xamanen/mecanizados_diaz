# Auditoría y Depuración de Recursos Gráficos - Mecanizados Díaz

Este informe detalla el estado de todas las imágenes del proyecto, clasificadas entre las que **realmente se usan**, las que están **alojadas externamente en la web**, y las que están **huérfanas/sin uso** listas para depurar.

---

## 1. Imágenes Alojadas en la Web (Externas) en `index.html`

Actualmente en `index.html` existen referencias que se cargan desde servidores externos:

### A. Fondos de Google CDN (`lh3.googleusercontent.com`)
* **ESTADO: RESUELTO (100% LOCAL)**
* Se reemplazaron las URLs externas de la sección `#tecnologia` y del banner final por la imagen local `plano_fondo.png`. Ya no existen dependencias de servidores de Google.

### B. Miniaturas de YouTube (`i.ytimg.com`)
* **12 portadas oficiales de videos:**
  * Todas las portadas de los videos cargan directamente desde la CDN de YouTube (`https://i.ytimg.com/vi/.../hqdefault.jpg`). Funcionan de manera nativa y son las miniaturas oficiales del canal.

---

## 2. Imágenes Locales ACTIVAS (En uso en `index.html`)

Estas imágenes **SÍ** se están usando en la web:

### En la Raíz:
| Archivo | Ubicación en la web |
| :--- | :--- |
| `logo.png` | Logotipo en el Header y Footer |
| `portada.png` | Fondo del Hero en versión Desktop |
| `estilo-hero.png` | Imagen superior del Hero en versión Mobile |
| `plano_fondo.png` | Fondo difuminado en `#servicios` y `#contacto` |
| `800MM1X1.png` | Foto del caso destacado (Engranaje Cónico) |
| `HAAS VF4_4EJE.png` | Slide 1 del carrusel de maquinaria (Haas completa) |
| `Fresado de 4 ejes continuos (Mecanizados de 4 ejes Continuos).png` | Slide 2 del carrusel de maquinaria (Fresado en acción) |

### En subcarpetas:
| Carpeta | Archivo | Ubicación |
| :--- | :--- | :--- |
| `PUNTO FOTOS MAQUINA/` | `20240712_171606 (1).jpg` | Tarjeta del Torno CNC Clever |
| `SECCIÓN DE TRABAJOS/` | `minera1.jpg`, `minera2.jpg` | Galería Minería |
| `SECCIÓN DE TRABAJOS/` | `petrolera1.jpeg` a `petrolera5.jpeg` (5 fotos) | Galería Petrolera |
| `SECCIÓN DE TRABAJOS/` | `produccionenserie1.jpg` a `produccionenserie5.jpeg` (5 fotos) | Galería Serie |
| `SECCIÓN DE TRABAJOS/` | `ingeneriainversa1.jpeg` a `ingeneriainversa4.jpeg` (4 fotos) | Galería Ing. Inversa |

---

## 3. Imágenes Locales NO UTILIZADAS (Huérfanas / Sobrantes)

Estas imágenes **NO** aparecen en ninguna parte del código HTML y pueden removerse o enviarse a una carpeta de respaldo:

### En la Raíz:
* `ENGRANAJE CÓNICO DE 800 MM 1 .jpg` (Foto original previa al recorte 1x1)
* `ENGRANAJE CÓNICO DE 800 MM 2.jpeg` (Foto original previa)
* `ENGRANAJECONICO.png` (Reemplazada por `800MM1X1.png`)
* `NUESTRA TECNOLOGIA.JPG` (Folleto de referencia enviado por el cliente)
* `NUESTROS TRABAJOS.jpg` (Folleto de referencia enviado por el cliente)
* `planoprincipal.png` (Copia redundante de `plano_fondo.png`)
* `tuercas.png` (Sin uso en la web)
* `tuercas_planos.jpg` (Sin uso en la web)

### En `PUNTO FOTOS MAQUINA/`:
* `ChatGPT Image 8 sept 2026, 01_53_23 p.m..png` (Copia de Fresado 4 ejes)
* `ChatGPT Image 8 sept 2026, 01_53_32 p.m..png` (Copia de Haas VF4)
* `pieza 2.jpg` (Sin uso en la web)

### En `SECCIÓN DE TRABAJOS/`:
* `2.png`
* `6.jpg`
* `Imagen de WhatsApp 2024-05-19 a las 20.34.20_47e3fcac.jpg`
* `Imagen18.jpg`
* `mecanizados_diaz_02_1x1.jpg`
* `nuestrostrabajos.jpeg`
* `tuercacnr.jpeg`
* 6 fotos adicionales de WhatsApp sin vincular.

---

## 4. Estado de la Organización (Completado)

* [x] **Carpeta `img/` creada y centralizada:**
  * 8 imágenes principales en `img/` (`logo.png`, `portada.png`, `estilo-hero.png`, `plano_fondo.png`, `800MM1X1.png`, `HAAS VF4_4EJE.png`, `Fresado de 4 ejes continuos...`, `torno_clever.jpg`).
  * 16 fotos de catálogo en `img/trabajos/`.
* [x] **Rutas en `index.html` actualizadas:** 100% de las 24 rutas locales probadas y verificadas con éxito.
* [x] **Carpeta `backup_descarte/`:** Contiene todos los archivos originales, folletos y fotos no utilizadas, manteniéndolos a salvo sin contaminar la raíz del proyecto.
* [x] **Fondos externos de Google CDN:** Eliminados y reemplazados por recursos locales.

