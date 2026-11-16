# Archivo maestro de ilustraciones históricas — CRÓNICAS: ORÍGENES

Este directorio conserva las ilustraciones originales aprobadas para producción. La aprobación visual y la incorporación del archivo binario son controles separados: una imagen solo se considera archivada cuando el archivo existe en este repositorio y puede abrirse desde GitHub.

## Inventario inicial de pilotos aprobados

| Código | Personaje | Aprobación del usuario | Archivo previsto | Estado del archivo |
|---|---|---|---|---|
| HIS-110 | Siddhartha Gautama (Buda) | Aprobada | `HIS-110_buda.png` | Original recibido en esta conversación; validado localmente; pendiente de subir a GitHub |
| HIS-129 | Nelson Mandela | Aprobada; referencia conceptual principal | `HIS-129_nelson_mandela.png` | Original recibido en esta conversación; validado localmente; pendiente de subir a GitHub |
| HIS-130 | Rey Arturo | Aprobada | `HIS-130_rey_arturo.png` | Pendiente de recuperar el original y subirlo |
| HIS-001 | Alejandro Magno | Aprobada | `HIS-001_alejandro_magno.png` | Pendiente de recuperar el original y subirlo |
| HIS-002 | Julio César | Aprobada | `HIS-002_julio_cesar.png` | Original generado disponible en la sesión; pendiente de incorporación al repositorio |

## Recepción y comprobación de originales

| Código | Archivo recibido | Dimensiones | Formato | SHA-256 del original recibido |
|---|---|---:|---|---|
| HIS-129 | `217997.png` (identificado como Nelson Mandela) | 1404 × 1536 | PNG RGB | `397ca9d45dcb8eaa5fec8fe762cff552d8b9a70e26482b9881f9a8ae5dd0df7e` |
| HIS-110 | `221029.png` (identificado como Buda) | 1404 × 1536 | PNG RGB | `5719412d743a58e3088e4eaebb8f6d0708fb413a3a487fc3dade02485ee39b49` |

Los dos originales fueron abiertos y comprobados en esta sesión. Sus nombres de carga se conservarán como referencia de recepción; al archivarlos se usarán los nombres normalizados por código indicados en el inventario. **La comprobación local no equivale a una subida a GitHub.**

## Reglas de conservación

1. Conservar el archivo original aprobado; no reemplazarlo por una recreación.
2. No recortar, retocar, reescalar ni convertir el original sin registrar una nueva versión derivada.
3. Mantener los nombres de archivo vinculados al código HIS.
4. No marcar un archivo como archivado hasta comprobar que GitHub lo sirve y que puede descargarse/abrirse.
5. La plantilla de carta y los datos editoriales permanecen separados de las ilustraciones.

## Verificación al crear este registro

- Cinco pilotos constan como aprobados por el usuario.
- HIS-129 y HIS-110: originales recibidos y verificados localmente en esta sesión; todavía no incorporados como binarios al repositorio.
- Los estados de aprobación HIS-001 y HIS-002 fueron comprobados en `data/produccion/prompts_ilustracion_historicos_001_144.json`.
- Este registro crea el índice maestro, pero **no afirma que los cinco archivos binarios ya estén en GitHub**.
- No se han modificado la plantilla SVG ni los archivos históricos editoriales.

## Próximo paso de archivo

Recuperar los originales de HIS-110, HIS-129, HIS-130 y HIS-001 desde sus conversaciones/descargas, e incorporar también el PNG original de HIS-002. Después, verificar cada ruta en GitHub y actualizar este inventario con la ubicación y, cuando sea posible, el hash SHA-256 de cada archivo.
