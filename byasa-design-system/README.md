# BYASA

Sistema de diseño de BYASA, empresa mexicana de soluciones de pesaje industrial, empaque, paletizado y robótica industrial. Atiende industrias como alimentos, farmacéutica, química y manufactura.

Fuente: brand book de BYASA (generado con Pomelli), logotipos entregados por la dirección, fichas de producto y reglas dictadas por la dirección. Todo valor marcado como "propuesta" no sale del brand book ni de una instrucción de la dirección.

## Esencia de marca

- Valores: mejora continua, satisfacción del cliente, calidad, profesionalismo.
- Estética: precisión de trabajo pesado, acentos en rojo de seguridad, realismo de planta, flujo sistemático, rigor técnico.
- Tono de voz: profesional, técnico, autoritativo, confiable.
- Slogan oficial: "La Mejor Forma de Pesar". Escribirlo así en piezas de texto. Los archivos de logotipo muestran el lema en minúsculas ("la mejor forma de pesar."), tal como fueron diseñados; no se alteran.

## Color

Colores oficiales del logotipo: rojo y gris.

| Token | Valor | Uso |
| --- | --- | --- |
| `cardinal-red` | #C73039 | Rojo oficial. Ícono, acentos, prefijo "b-" de las submarcas, llamadas a la acción. |
| `byasa-gray` | #8B8E92 | Gris oficial del logotipo. Valor medido en el archivo del logo; solo para logotipo, filetes y elementos grandes (contraste 3.3:1 sobre blanco). |
| `onyx-black` | #333333 | Texto y titulares. |
| `chalk-white` | #F2F3F5 | Fondo de página y relieve. |
| `pure-white` | #FFFFFF | Superficies elevadas y texto sobre rojo o negro. |

Reglas:
- El rojo se usa como acento, no como fondo de grandes superficies de texto corrido. Texto blanco sobre `cardinal-red` cumple 4.5:1 (5.4:1).
- Nunca usar otro rojo. Los archivos originales usaban #EF5047 (principal) y #E7392F / #EF463B (submarcas); las versiones de este sistema están recoloreadas a #C73039.

## Tipografía

Raleway es la tipografía primaria (Google Fonts). La escala (display, h1 a h3, body, small, label) es una propuesta; el brand book solo define la familia.

### Regla de las submarcas "b-"

En el nombre de una submarca, "b-" (incluido el guion):

1. va siempre en `cardinal-red` (#C73039);
2. va siempre 2 puntos por encima del tamaño del resto de las letras.

Ejemplo: en "b-weight", si "b-" mide 16 px, "weight" mide 14 px. Estilos: `submarca-prefijo` (16 px) y `submarca-nombre` (14 px); para otros tamaños, mantener siempre la diferencia de 2.

## Logotipo

- Espacio libre: 40 px por cada lado.
- Tamaño mínimo: 100 px de ancho (1.04 in). Por debajo se pierde legibilidad.
- Usar siempre los archivos de `assets/Logos/`; no redibujar el ícono ni el logotipo.
- Fondos oscuros: usar `byasa-logo-horizontal-fondo-oscuro`.
- `byasa-logo-horizontal-blanco` (All White): solo para elementos donde el logotipo no se puede integrar de la mejor manera. La versión con rojo y gris sigue siendo la principal.

## Submarcas

Cada línea lleva el prefijo "b-" en `cardinal-red`, el nombre en negro y un pictograma de línea:

- b-weight: carrito con cajas y báscula
- b-feeding: embudo y empaque
- b-container: caja
- b-packaged: tarima con rollo
- b-service: mano con engrane y llave
- b-check: bolsa de peso con sello de verificación
- b-design: engrane y lápiz
- b-connected: globo terráqueo
- b-robotech: brazo robótico y chip
- b-automated: brazo robótico, banda transportadora y chip

Las submarcas acompañan al logotipo de BYASA; no lo sustituyen. Los archivos de `assets/Submarcas/` están recoloreados a `cardinal-red`; los originales sin modificar están en `assets/Originales/`.

## Pendientes

- Los logotipos recoloreados son una corrección provisional. Pedir a diseño la reexportación oficial con #C73039.
- No se recibió versión en blanco de las submarcas para fondos oscuros.
- El archivo All White trae el ícono solo como contorno fino; confirmar que es el archivo final.
- El brand book cita "Somos BYASA, somos usted"; la dirección indicó que el slogan oficial es "La Mejor Forma de Pesar". Actualizar el brand book.
- El gris #8B8E92 se midió en el logotipo; confirmar el valor oficial con diseño.
- Escala tipográfica general, espaciados y radios son propuestas sin respaldo en el brand book.
