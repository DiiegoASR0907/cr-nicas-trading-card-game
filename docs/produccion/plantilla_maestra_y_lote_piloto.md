# Producción — plantilla maestra y lote piloto

**Colección:** CRÓNICAS — ORÍGENES  
**Estado:** inicio de producción autorizado por aprobación editorial global del usuario  
**Alcance aprobado:** 144 registros históricos y semihistóricos  
**Formato final:** 63 × 88 mm, vertical

## 1. Decisión editorial de producción

La aprobación es global: no se realizará una ronda obligatoria de 144 aprobaciones individuales. Se conservan en cada ficha las notas y cautelas documentales para no convertir hipótesis o tradiciones en hechos demostrados. El campo `verification_status` describe la cautela documental y no se modifica por la aprobación de producción. Se añade `production_status: aprobado_produccion` para reflejar la decisión editorial.

## 2. Sistema de diseño maestro

- **Formato:** 63 × 88 mm terminado; 3 mm de sangrado por lado (archivo de arte: 69 × 94 mm).
- **Orientación:** vertical.
- **Estética:** oscura, épica y cinematográfica; ilustración pictórica de alto detalle.
- **Paleta:** carbón y negro azulado como base; oro envejecido para marcos, jerarquía y ornamentos; plata solo como acento secundario.
- **Tipografía:** serif de alta legibilidad para nombres y texto; versales espaciadas para etiquetas. Evitar fuentes excesivamente ornamentales en los datos.
- **Anverso:** categoría, código, nombre, época/fechas, ilustración dominante y síntesis breve.
- **Reverso:** tres hitos destacados, curiosidad opcional, referencias abreviadas y espacio opcional para QR al expediente documental.
- **Texto:** breve y verificable. No imprimir biografías largas ni estadísticas de combate. No añadir atributos o reglas de juego que no estén aprobados.
- **Diferenciación:** el mismo marco y retícula para todo el bloque; símbolos, tratamiento del fondo y pequeños acentos pueden variar por categoría. Las cartas legendarias no deben parecer fotografías históricas.
- **Seguridad:** mantener texto y elementos esenciales dentro del área segura; sangrado y guías se excluyen del arte final.

## 3. Lote piloto

Se preparan tres cartas con perfiles distintos:

| Código | Personaje | Función de prueba |
|---|---|---|
| HIS-129 | Nelson Mandela | Personaje histórico contemporáneo; retrato realista y tratamiento sobrio |
| HIS-110 | Siddhartha Gautama (Buda) | Personaje histórico antiguo con cronología debatida; iconografía cultural respetuosa |
| HIS-130 | Rey Arturo | Figura legendaria; tratamiento épico-literario sin presentarlo como retrato histórico comprobado |

El contenido de prueba está en `data/produccion/lote_piloto_historicos.json`. La plantilla editable anverso/reverso está en `assets/plantillas/cronicas_origenes_plantilla_maestra.svg`.

## 4. Criterios para evaluar el piloto

1. Lectura clara del nombre, época y síntesis a tamaño físico real.
2. La ilustración debe dominar el anverso sin ocultar la identidad.
3. El reverso debe ordenar tres hitos y la curiosidad sin saturación.
4. Marcos, márgenes, numeración y tipografía deben coincidir en las tres cartas.
5. Los rasgos visuales deben respetar época, cultura y naturaleza histórica/legendaria.
6. Las referencias completas permanecen en JSON; el QR es opcional y solo se activará cuando exista una ruta estable al expediente.
7. Ninguna carta se considera lista para imprenta hasta validar resolución, sangrado, perfil de color y pruebas físicas.

## 5. Flujo de producción

**Plantilla maestra → lote piloto de 3 → ajuste de identidad visual → producción por bloques → control de calidad → exportación para impresión.**

No se declara cerrada la producción completa hasta validar las 144 cartas en conjunto.
