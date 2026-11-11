# Shin Megami Tensei: Digital Devil Saga — Traducción al español

[![Invítame a un café en Ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/johanderohan)

Ficha del proyecto, capturas y más traducciones al castellano en **[Parches en Castellano](https://parchesencastellano.com/traducciones/playstation-2/shin-megami-tensei-digital-devil-saga)**.

Traducción al **español de España** de *Shin Megami Tensei: Digital Devil Saga* (PlayStation 2, 2005),
el RPG de Atlus en el que las tribus del Junkyard luchan por llegar al Nirvana tras despertar a sus
demonios, y que nunca salió en español.

Se ha traducido **desde la versión americana en inglés** (no desde el japonés), con una biblia de
términos propia para personajes, tribus, lugares, habilidades, mantras y objetos.

La traducción se reparte como **parche**: no incluye el juego. Necesitas tu propia copia de la
versión USA para aplicarlo.

## Estado

Última versión: **[v1.0 — Primera versión](../../releases/tag/v1.0)**.

| Parte | Estado |
|---|---|
| Diálogos, escenas con subtítulos y PNJ | Traducidos (4.246 textos únicos, revisados) |
| Menús, ayudas, tutoriales, terminales del Karma, tarjeta de memoria | Traducidos |
| Habilidades, mantras, objetos, enemigos, razas, lugares | Traducidos (unas 1.840 cadenas de tablas) |
| Órdenes y mensajes de combate, resultados, subida de nivel | Traducidos |
| Texto dentro de imágenes | 278 rótulos rehechos (menús, combate, resultados, mapa, terminales, guardado, título, nombres de zona) |
| Caracteres españoles | **á é í ó ú ü ñ Á É Í Ó Ú Ü Ñ ¡ ¿** en la fuente del juego |
| Revisión durante una partida | Parcial (ver abajo) |

Decisiones de traducción: se conservan **Junkyard**, los nombres de las tribus (los Embryon, los
Vanguards…) y los nombres de habilidades propios de la saga (Bufu, Dia, Zio…); las siglas son
**PS / PM / PA / NV**; las altitudes van en metros.

Se mantienen a propósito en inglés el logotipo, los vídeos (con algún rótulo incrustado), el aviso
legal del arranque, los créditos, los carteles del decorado y el rótulo «DVILIZE» del panel de
combate. Las cabeceras del panel («LVCHAR», «GRVPO», «HVIR») usan la letra original del juego, que
dibuja la U como V.

### Comprobaciones y trabajo pendiente

Se ha jugado en emulador (PCSX2) desde el arranque en frío y con partida nueva:

- título, Ajustes con todas sus opciones y ayudas, y las escenas iniciales con sus subtítulos;
- la base de los Embryon: conversaciones, menú, mapa, Terminal grande del Karma, guardado, reinicio
  y carga de la partida;
- la base de los Vanguards hasta el primer combate con su tutorial, cofres e interruptores,
  y los terminales pequeño y grande (Teletransporte, Recuperar);
- una decena de combates: las cuatro páginas de órdenes con sus ayudas, habilidades, objetos,
  Analizar, cambio a forma humana y vuelta a demonio, relevo, huida, refuerzos enemigos, victoria,
  resultados y subidas de nivel con reparto de puntos;
- los menús Habil., Objeto, Equipar, Combo, Mantra, Estado y Grupo.

Varias pantallas (carga, menú Mantra, combate y resultados) se han comparado con las mismas del
original en inglés cargando la misma partida. Una auditoría automática comprueba en la imagen final
los directorios del disco, todos los bloques de texto, los límites de cada cuadro, la fuente y los
parches del ejecutable. El parche se ha aplicado sobre el ISO USA original y el resultado coincide
byte a byte con la imagen probada.

**No se ha jugado el juego entero**: solo las primeras horas. No se han visto en pantalla la tienda
del Vendedor, la descarga de mantras, el mapa del mundo, el resto de mazmorras y jefes ni el final.
Esos textos están traducidos y medidos con la fuente del juego, pero sin comprobar en partida.
**No se ha probado en una PS2 real.** La traducción y su revisión se han hecho con asistencia de IA,
sin revisores humanos independientes.

Si encuentras un texto cortado, en inglés o un error, abre una incidencia con una captura.

## Cómo aplicar el parche

1. Descarga el parche `.xdelta` de la sección **[Releases](../../releases)**.
2. Consigue tu copia del juego en versión **USA** (SLUS-20974), como imagen ISO completa.
3. **Comprueba que tu copia es la correcta** antes de nada:

   | | |
   |---|---|
   | Archivo | `Shin Megami Tensei - Digital Devil Saga (USA).iso` |
   | Tamaño | 4.539.547.648 bytes |
   | MD5 | `ae4330140ef56f9eb1c689b9bb383401` |
   | SHA-1 | `f022cc27d2c333db64f1f1a46b312aafc5ce632e` |

   ```bash
   md5sum "Shin Megami Tensei - Digital Devil Saga (USA).iso"     # Linux
   md5 "Shin Megami Tensei - Digital Devil Saga (USA).iso"        # macOS
   CertUtil -hashfile "Shin Megami Tensei - Digital Devil Saga (USA).iso" MD5   # Windows
   ```

   Si no coincide, el parche fallará o dará un resultado corrupto.
4. Aplica el parche con una de estas herramientas:
   - **Windows**: [Delta Patcher](https://github.com/marco-calautti/DeltaPatcher/releases)
   - **Linux / macOS**: `xdelta3 -d -s "Shin Megami Tensei - Digital Devil Saga (USA).iso" shin-megami-tensei-digital-devil-saga-traduccion-es-v1.0.xdelta "Shin Megami Tensei - Digital Devil Saga (ES).iso"`
5. Comprueba que el ISO resultante tiene MD5 **`cacbb5b590a292d2649843f2635cdc51`** (mismo tamaño que
   el original).
6. Carga el ISO resultante en tu emulador (PCSX2) o en tu método habitual para PS2.

Aplica el parche sobre el **ISO USA original**, no sobre uno ya traducido.

No se ha probado a continuar con partidas guardadas con la versión inglesa: empieza una partida nueva.

## Aviso

Este proyecto es una traducción hecha por afición, sin ánimo de lucro y sin relación alguna con
Atlus ni con SEGA. Aquí no se distribuye el juego ni ninguna parte de él: solo un parche que
modifica una copia que ya tengas.

Si eres el titular de los derechos y quieres que retire esto, abre una incidencia y lo hago.
