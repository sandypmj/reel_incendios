# reel_incendios

Reel de 58 segundos sobre las personas que viven cerca de incendios forestales en Perú, narrado con la voz de mi mamá clonada con IA.

**Fuente de los datos:** [tablero de personas que viven cerca de incendios](https://claude.ai/artifact/UsyGgMV7ysFBEDzzrW5DeU)

## Archivos

- Video: `reel.mp4`
- Posts para Instagram/Facebook, X y LinkedIn: `posts.md`
- Subtítulos: `reel.srt`
- Portada: `portada.png`

## Nota sobre la entrega

No pude asistir a la clase anterior por cruces con responsabilidades laborales, así que no realicé el primer ejercicio. Para entregar este segundo ejercicio en el plazo propuesto, opté por esta alternativa: usé como fuente el tablero indicado arriba y la voz de mi mamá para el clon.

## Qué corregí del guion

- Usé «viven cerca» y no «afectadas»: el tablero mide quién está a 5 km o menos del fuego, no quién sufrió daños.
- La cifra depende de qué se cuente como incendio: 235,952 personas con los incendios probables, 2.66 millones si se cuentan todos los focos de calor.
- Quité «en tiempo real» y los números de emergencia, porque no están en la fuente.

## Problemas técnicos que resolví

- La grabación de 19 s era casi todo silencio y el clon producía ruido. Lo arreglé recortándola al tramo con voz.
- El control de calidad fallaba porque Whisper escribe los números con dígitos. Lo arreglé pasando las cifras a palabras antes de comparar.
