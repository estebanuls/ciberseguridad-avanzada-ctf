# Desafíos CTF — Ciberseguridad Avanzada

Resolución de los desafíos CTF que montaron los distintos grupos del electivo. Cada carpeta tiene el informe
de un reto con su proceso, los comandos usados y las capturas de evidencia dentro del mismo informe.

El desafío de **Wireshark no va**, porque ese lo creé yo para el curso; me toca resolver los de los demás.

## Estado de los desafíos

| Desafío | Estado | Flag(s) | Informe |
| --- | --- | --- | --- |
| file / strings — La evidencia perdida | ✅ Resuelto | `FLAG{ELF_DESCUBIERTO}` · `FLAG{STRINGS_ENCONTRO_LA_EVIDENCIA}` | [Abrir](strings-file/informe.md) |
| Netcat — El registro perdido | ✅ Resuelto | `FLAG{consulta_el_servicio_2026}` (puerto 4646) | [Abrir](netcat/informe.md) |
| John the Ripper / Hashcat | ✅ Resuelto | zip: `Panda123` · hash: `Zebras42` | [Abrir](john-hashcat/informe.md) |
| ExifTool — Operación Anatidae | ✅ Resuelto | `FLAG{SM-S918B_-29.9027_-71.2520_Adobe Photoshop 25.0 (Windows)}` | [Abrir](exiftool/informe.md) |
| Gobuster — ORION-7 | ✅ Resuelto | `FLAG{n4d4_3st4_0cult0}` (3 fragmentos) | [Abrir](gobuster-orion7/informe.md) |
| Inyección SQL — Laboratorio 2 niveles | ✅ Resuelto | `AULA{BUSQUEDA_ALTERADA}` · `AULA{LOGIN_SIN_CLAVE}` | [Abrir](inyeccion-sql/informe.md) |
| Burp Suite — La FLAG perdida | ⏳ Pendiente (es gráfico) | método listo; falta capturar `CTF{...}` | (se sube cuando esté) |

## Cómo está organizado

- Cada reto tiene su carpeta con su `informe.md`; las capturas se ven dentro del informe.
- Los informes están escritos con el proceso real: qué hice, qué comando usé y qué me devolvió.
- Cada informe cubre lo que pide la pauta: introducción, análisis, herramientas, metodología, evidencias,
  pistas usadas, la flag, el análisis del proceso y la parte ética.
