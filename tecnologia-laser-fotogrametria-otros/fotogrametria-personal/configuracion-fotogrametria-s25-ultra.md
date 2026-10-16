---
type: libro
title: "Guía Práctica de Fotogrametría - Samsung Galaxy S25 Ultra"
author: "(anonymous)"
categoria: "Tecnología láser, fotogrametría, otros"
paginas: 2
extraccion: "texto"
fuente: "local:E:/Biblioteca digital/Tecnología láser, fotogrametría, otros/Fotogrametría personal/Configuracion_Fotogrametria_S25_Ultra.pdf"
convertido: 2026-10-16
---

# Guía Práctica de Fotogrametría - Samsung Galaxy S25 Ultra

> Texto extraído de `Tecnología láser, fotogrametría, otros\Fotogrametría personal\Configuracion_Fotogrametria_S25_Ultra.pdf` (2 páginas, texto). El PDF original está en el disco E: (Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Guía de Fotogrametría Óptima - Samsung Galaxy S25 Ultra

Guía de Fotogrametría Móvil

Dispositivo: Samsung Galaxy S25 Ultra | Software: Agisoft Metashape

Este documento establece los parámetros de captura e instrucciones geométricas para digitalizar objetos
pequeños (~20 cm de altura) con la máxima fidelidad matemática en Agisoft Metashape. El objetivo principal
es anular los algoritmos de la fotografía computacional móvil y estandarizar la geometría de captura para
diversos tipos de materiales.

\1. Ajustes del Sensor (Modo Pro / Expert RAW)

Parámetro Valor Óptimo Justificación de Fotogrametría

Formato de Salida RAW + JPEG Evita el sobre-enfocado y reducción de ruido artificial que altera
texturas.

Selección de Lente Principal (1x) Mínima distorsión óptica. Evitar ultra gran angular y zooms digitales.

Resolución 50 Megapíxeles Balance ideal píxel por píxel entre nitidez pura y peso de
procesamiento.

Enfoque (Focus) Manual (MF) Bloqueado Si la distancia focal cambia, el software asume cámaras distintas y
falla.

Sensibilidad (ISO) ISO 50 o 100 Mínimo ruido digital. El grano genera puntos de coincidencia falsos.

Velocidad (Shutter) 1/250s o superior Previene el desenfoque por movimiento (motion blur) al disparar a
pulso.

Balance de Blancos Fijo (Manual / K) Mantiene la consistencia cromática. Evita saltos tonales en la malla.

HDR Automático DESACTIVADO Combina exposiciones alterando las sombras, falseando la
geometría.

Optimización de DESACTIVADO La Inteligencia Artificial local altera bordes y contrastes
Escena geométricos.

\2. Estrategia de Captura para un Objeto de 20 cm

Para garantizar una cobertura total del 100% libre de puntos ciegos y evitar nubes de puntos secundarias en
los fondos, se debe ejecutar una órbita semiesférica estricta estructurada en tres niveles de altura:

• Nivel Inferior (Ángulo Bajo - 15° a 20°): Ejecutar una órbita completa de 360° alrededor del objeto
tomando entre 24 y 30 fotografías (un disparo cada 12° a 15° aproximadamente). Este nivel captura las
bases, entrantes y concavidades inferiores.

Basado en las pautas oficiales de Agisoft Metashape Página 1 de 2

<!-- p. 2 -->

Guía de Fotogrametría Óptima - Samsung Galaxy S25 Ultra

• Nivel Medio (Ángulo de Vista - 45°): Elevar la posición de la cámara y realizar otra órbita completa de 360°
(24 a 30 fotografías). Captura las caras principales y perfiles generales.
• Nivel Superior (Ángulo Cenital - 75° a 90°): Desde una posición casi vertical superior, realizar disparos
cruzados e inclinados (10 a 15 fotografías) cubriendo las tapas y superficies planas horizontales del objeto.
• Solape Requerido: Mantener un solape mínimo del 70% al 80% entre fotos consecutivas. Cada detalle del
objeto debe aparecer nítido en al menos 3 imágenes independientes.

\3. Gestión del Fondo y Aislamiento de Superficies

El comportamiento óptico cambia según el material, por lo que aislar el fondo requiere técnicas adaptadas a la
naturaleza de la superficie:

• Materiales Opacos y Rugosos (Hormigón, Cerámica, Piedra): Son ideales para fotogrametría. El
principal problema es el fondo de la sala. Solución: Utilizar un plato giratorio manteniendo la cámara fija
sobre un trípode. Colocar un fondo infinito de cartulina negra mate. Metashape ignorará la cartulina por falta
de textura y procesará el objeto con velocidad.
• Materiales Reflectantes, Pulidos o Metálicos: Los brillos cambian de posición si te mueves, confundiendo
al software. Solución: Utilizar una luz completamente difusa (softboxes o un domo de luz translúcido
casero). Si el reflejo persiste, aplicar spray opacador lavable o talco finamente espolvoreado para dar
textura estática al objeto.
• Materiales Lisos o Monocromáticos Plásticos: Al carecer de vetas o rugosidad, el software no encuentra
puntos de emparejamiento. Solución: Proyectar un patrón de luz estructurada (como un patrón de puntos
con un proyector) durante la alineación, o generar ruido visual controlado (leves salpicaduras temporales de
pintura base agua o tiza líquida).

\4. Truco de Post-Procesamiento en Metashape

Si el fondo generó puntos no deseados en la alineación inicial, límpialo de la siguiente manera antes de
generar la geometría pesada: Ejecuta Align Photos de forma habitual. En la nube dispersa (Sparse Cloud), usa
la herramienta de lazo para seleccionar y borrar manualmente los puntos flotantes del entorno. Luego, ve a
Tools > Import > Import Masks y selecciona la opción 'From Sparse Cloud' aplicada a todas las cámaras.
Esto creará máscaras perfectas automáticas en tus fotos basándose solo en la silueta limpia del objeto.

Basado en las pautas oficiales de Agisoft Metashape Página 2 de 2
