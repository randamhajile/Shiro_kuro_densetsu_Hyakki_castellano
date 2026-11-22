# *La Leyenda de la luz y la oscuridad - Hyakki* en castellano (MSX)
Traducción completa al castellano del juego *Shiro to kuro no densetsu: Hyakki hen* (Soft Wing, 1985) de MSX en su versión de disquete.
El repositorio **no incluye el juego**: solo el parche IPS que convierte el juego al idioma castellano, con instrucciones para aplicarlo.
## Capturas

Versión traducida (v1.0) en openMSX, con un Sony HB-F500 (MSX2 japonés).

| | |
|---|---|
| ![Pantalla de título](capturas/cover.jpg) | ![Pantalla de título](capturas/captura_1.png)  |
| Portada del juego | Pantalla de título |
| ![Pantalla de título](capturas/captura_1.png) | ![Primera aparición de Hyakki](capturas/captura_2.png) |
| Pantalla de título | Primera aparición de Hyakki |
| ![Espacio en rojo](capturas/captura_3.png) | ![Belgarder](capturas/captura_4.png) |
| Espacio en rojo | Belgarder |

## Qué necesitas

El juego correspondiente a la recopilación de la saga en formato DSK, exactamente este:

| | Valor |
| --- | --- |
| Nombre habitual | `Legend of White and Black Compilation - Hyakki-Hen (1991)(Soft Studio WING).dsk` |
| Tamaño | 737 280 bytes |
| CRC32 | `962ffefe` |
| MD5 | `8628015bd2155e7b6f17b5c83497468b` |
| SHA-1 | `9ff194aa42cf4a5e5381a7ccae0153bfc51ebb38` |

El parche es [`releases/SKD_Hyakki_ES_v1.0.ips`](releases/SKD_Hyakki_ES_v1.0.ips), también disponible en la página de la release v1.0.

## Cómo aplicar el parche

Elige una de estas formas:


**Con Floating IPS o Lunar IPS** (Windows): «Apply Patch», elige el `.ips` y después el DSK en japonés. Trabaja sobre una copia, porque Lunar IPS modifica el fichero elegido.


El resultado debe ser este:

| | Valor |
| --- | --- |
| Tamaño | 737 280 bytes |
| CRC32 | `7142002c` |
| MD5 | `617e8ff81543642f2f9f0a15177b8366` |
| SHA-1 | `152c013a8cbb4efaa21c25f4621356bb71568ee2` |

## Qué hay en el repositorio

- `releases/LLO_Hyakki_ES_v1.0.ips`: el parche.
- `docs/`: solución, notas técnicas y otros datos.

**No se incluyen ni el disquete original ni el traducido.**

## Pruebas

- Partida completa terminada por randamhajile, aplicando la solución que se encuentra en la carpeta docs/.

## Créditos

* **Juego original:** 白と黒の伝説［百鬼編］ (Shiro to kuro no densetsu: Hyakki hen), Soft Studio Wing, 1985.
* **Traducción inicial y corrección de bugs:** Claude.
* **Traducción final, revisión y edición:** randamhajile.
