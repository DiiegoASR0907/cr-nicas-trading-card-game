# Archivo maestro de ilustraciones históricas — CRÓNICAS: ORÍGENES

Este directorio conserva las ilustraciones originales aprobadas para producción. La aprobación visual y la incorporación del archivo binario son controles separados: una imagen solo se considera archivada cuando el archivo existe en este repositorio y puede abrirse desde GitHub.

## Inventario inicial de pilotos aprobados

| Código | Personaje | Aprobación del usuario | Archivo previsto | Estado del archivo |
|---|---|---|---|---|
| HIS-110 | Siddhartha Gautama (Buda) | Aprobada | `HIS-110_buda.png` | Original recibido en esta conversación; validado localmente; pendiente de subir a GitHub |
| HIS-129 | Nelson Mandela | Aprobada; referencia conceptual principal | `HIS-129_nelson_mandela.png` | Original recibido en esta conversación; validado localmente; pendiente de subir a GitHub |
| HIS-130 | Rey Arturo | Aprobada | `HIS-130_rey_arturo.png.jpeg` | Archivado en GitHub; 414061 bytes; blob `d6895393e50412a115776929110b9b12a8e76011` |
| HIS-001 | Alejandro Magno | Aprobada | `HIS-001_alejandro_magno.png` | Archivado en GitHub; 393336 bytes; blob `b37965cbb944ef6951b041f49d626c1b49f51892` |
| HIS-002 | Julio César | Aprobada | `HIS-002_julio_cesar.png` | Archivado en GitHub; 298356 bytes; blob `bb7e20abb8a9667ac05dd53d1ae64c4ecce99cea` |

## Archivos binarios comprobados en GitHub (rama main)

Los cinco archivos siguientes aparecen como objetos de tipo `file` en la carpeta del repositorio. Se registran sus tamaños y SHA de blob devueltos por GitHub. La API consultada confirma existencia y metadatos; no se ha realizado una decodificación visual binaria desde esta conexión.

| Código | Ruta exacta en GitHub | Tamaño (bytes) | Blob SHA |
|---|---|---:|---|
| HIS-001 | `HIS-001_alejandro_magno.png` | 393336 | `b37965cbb944ef6951b041f49d626c1b49f51892` |
| HIS-002 | `HIS-002_julio_cesar.png` | 298356 | `bb7e20abb8a9667ac05dd53d1ae64c4ecce99cea` |
| HIS-110 | `HIS-110_buda.jpg` | 451057 | `a041fcd696109c6f9be9c072f0ffa6e2a73cb004` |
| HIS-129 | `HIS-129_nelson_mandela.jpg` | 361236 | `0cfdf37c436300bf860ebf8db611b212b9b7f374` |
| HIS-130 | `HIS-130_rey_arturo.png.jpeg` | 414061 | `d6895393e50412a115776929110b9b12a8e76011` |

**Observación de nombre:** el archivo de Rey Arturo quedó cargado como `HIS-130_rey_arturo.png.jpeg` (doble extensión). GitHub lo reconoce como archivo; conviene renombrarlo posteriormente a `HIS-130_rey_arturo.jpeg` para mantener una extensión clara, sin cambiar sus bytes.

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
- Los cinco archivos binarios están presentes en `assets/ilustraciones/historicos/` en la rama `main`; tamaños y blob SHA registrados arriba.
- Los estados de aprobación HIS-001 y HIS-002 fueron comprobados en `data/produccion/prompts_ilustracion_historicos_001_144.json`.
- Los cinco originales están archivados en GitHub según el listado de contenidos de la rama `main`.
- No se han modificado la plantilla SVG ni los archivos históricos editoriales.

## Próximo paso de archivo

Corregir el nombre doble de HIS-130 si se desea y realizar una comprobación visual/descarga de los cinco archivos. Mantener los originales sin alteraciones.
