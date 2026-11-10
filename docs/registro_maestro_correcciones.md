# Registro maestro de correcciones — CRÓNICAS: ORÍGENES

**Propósito:** concentrar las discrepancias, decisiones documentales y cambios editoriales de los 144 personajes históricos en un único registro trazable.  
**Regla:** ninguna corrección se incorpora a un JSON sin respaldo suficiente. La inclusión de fuentes o la corrección de una descripción no equivale a aprobación editorial.  
**Estado de las ilustraciones:** suspendidas hasta completar la verificación y aprobación formal de los 144 registros.

## Flujo de trabajo

1. Resolver discrepancias históricas y cronológicas.
2. Sustituir fuentes inadecuadas y reforzar referencias primarias, institucionales y académicas.
3. Revisar clasificación y nivel de historicidad.
4. Corregir el JSON únicamente con evidencia suficiente.
5. Aprobar editorialmente cada ficha.

## Estados de seguimiento

- **Pendiente:** no se ha realizado la revisión de integración.
- **Resuelto documentalmente:** el dato y su formulación cuentan con respaldo suficiente para proponer una corrección.
- **Revisión comparativa:** requiere decisión transversal de clasificación o criterio común.
- **Pendiente de aprobación:** corrección integrada, pero ficha aún no aprobada.
- **Aprobado:** solo tras decisión editorial expresa.

La aprobación no se deriva automáticamente de la validación técnica del archivo.

## Alcance y avance

| Archivo | Códigos | Registros | Estado de integración |
|---|---|---:|---|
| `gobernantes_001_036.json` | HIS-001–HIS-036 | 36 | En curso |
| `guerreros_037_061.json` | HIS-037–HIS-061 | 25 | Pendiente |
| `sabios_cientificos_062_091.json` | HIS-062–HIS-091 | 30 | Pendiente |
| `exploradores_092_109.json` | HIS-092–HIS-109 | 18 | Pendiente |
| `lideres_espirituales_110_127.json` | HIS-110–HIS-127 | 18 | Pendiente |
| `bloque_final_128_144.json` | HIS-128–HIS-144 | 17 | Pendiente |
| **Total** | **HIS-001–HIS-144** | **144** | **1–6 en integración** |

---

# Archivo 1 — Gobernantes y Conquistadores (HIS-001–HIS-036)

## HIS-001 — Alejandro Magno

- **JSON original:** 356–323 a. C.; rey de Macedonia desde 336 a. C.; derrotó al Imperio aqueménida y extendió la campaña hasta el noroeste del subcontinente indio.
- **Discrepancia / precisión:** no presentar la campaña como conquista de «India» en su totalidad. La fuerza macedonia cruzó el Indo, venció a Poros en el Hidaspes (326 a. C.) y se detuvo en el Hífasis/Beas ante la negativa del ejército a continuar hacia el este.
- **Decisión documental:** conservar fechas y ascenso de 336 a. C.; mantener la formulación geográfica acotada al noroeste del subcontinente. La descripción breve puede indicar que derrotó al Imperio aqueménida y llevó su campaña hasta el noroeste del subcontinente indio.
- **Fuentes:** Pierre Briant, *Encyclopaedia Iranica*, «Alexander the Great» (https://www.iranicaonline.org/articles/alexander-the-great-356-23-bc/); Albert Brian Bosworth, *Oxford Classical Dictionary*, «Alexander III of Macedon» (https://academic.oup.com/edited-volume/61673/chapter-abstract/548059801); fuentes antiguas a cotejar en la revisión final: Arriano, *Anábasis de Alejandro*; Diodoro Sículo, libro XVII; Plutarco, *Vida de Alejandro*.
- **Cambio JSON integrado:** no se cambia fecha; se añade bibliografía verificable y se conserva descripción acotada.
- **Estado:** resuelto documentalmente en esta pasada; pendiente de aprobación editorial.

## HIS-002 — Julio César

- **JSON original:** 100–44 a. C.; general y dirigente político romano; su carrera militar y concentración de poder contribuyeron a la crisis final de la República.
- **Discrepancia / precisión:** no atribuir a César, como individuo, toda la caída de la República. Su acumulación de poder, la guerra civil y su dictadura fueron decisivas, pero se insertan en una crisis institucional y social previa y colectiva.
- **Decisión documental:** conservar 100–44 a. C. y la formulación causal moderada «contribuyó a la crisis final». Los *Commentarii* son fuentes de primera persona y también obras de autorrepresentación y justificación política; deben contrastarse con Cicerón, Salustio y otras fuentes antiguas.
- **Fuentes:** T. P. Wiseman, *Oxford Dictionary of National Biography*, «Caesar (100–44 bc)» (https://academic.oup.com/oxford-dictionary-of-national-biography/reference/63486/reference-article-abstract/579736904); Kate Gilliver, *The Encyclopedia of War*, «Caesar, Gaius Julius (100–44 BCE)» (https://onlinelibrary.wiley.com/doi/10.1002/9781444338232.wbeow093); fuente primaria: *Commentarii de bello Gallico* y *Commentarii de bello civili*, contrastados con Cicerón y Salustio.
- **Cambio JSON integrado:** no se altera la cronología ni se añade una afirmación nueva; se incorporan fuentes académicas y primarias.
- **Estado:** resuelto documentalmente en esta pasada; pendiente de aprobación editorial.

## HIS-003 — Augusto

- **JSON original:** 63 a. C.–14 d. C.; primer emperador romano; recibió el título de Augusto en 27 a. C.; consolidó un nuevo sistema de gobierno tras las guerras civiles.
- **Discrepancia / precisión:** «primer emperador» y «fundador del Principado» son etiquetas historiográficas útiles, pero simplifican una transformación política gradual. La *Res Gestae* es una fuente primaria de autorrepresentación oficial, no un relato neutral.
- **Decisión documental:** conservar fechas y 27 a. C. como fecha de concesión del título. Para la tarjeta, «considerado convencionalmente el primer emperador romano» o una formulación equivalente evita presentar el título moderno como descripción constitucional exacta.
- **Fuentes:** Alison Cooley, *Oxford Classical Dictionary*, «Augustus, Roman emperor, 63 BCE–14 CE» (https://academic.oup.com/edited-volume/61673/chapter-abstract/548059949); *Res Gestae Divi Augusti*, texto y contextualización en Fordham University (https://sourcebooks.web.fordham.edu/ancient/14resgestae.asp).
- **Cambio JSON integrado:** no se cambia cronología; se añaden fuentes académica y primaria. La cautela sobre el carácter propagandístico ya está reflejada en la nota del registro.
- **Estado:** resuelto documentalmente en esta pasada; pendiente de aprobación editorial.

## HIS-004 — Leónidas

- **JSON original:** muerte en 480 a. C.; rey agíada de Esparta; dirigió la resistencia griega en Termópilas.
- **Discrepancia / precisión:** la batalla fue una derrota militar griega, aunque luego adquirió enorme valor simbólico. Heródoto enumera contingentes de varias ciudades: no combatieron solamente los 300 espartanos. Los 700 tespios y 400 tebanos aparecen entre los contingentes que permanecieron en el paso, con matices en el relato de Heródoto.
- **Decisión documental:** conservar la fecha de muerte y el cargo; formular el episodio como defensa aliada del paso bajo el mando espartano de Leónidas, sin reducir la fuerza a los 300.
- **Fuentes:** Heródoto, *Historias*, 7.201–233 (fuente antigua principal; traducción consultable en https://www.livius.org/sources/content/herodotus/herodotus-on-thermopylae/); Richard Evans, «Commemorating Thermopylae: The Andreia of Glorious Defeat as a Literary Construct» (Edinburgh University Press, 2020); HISTORY, «Leonidas» (https://www.history.com/articles/leonidas).
- **Cambio JSON integrado:** se refuerza la bibliografía; la biografía ya no afirma que solo combatieran los 300, por lo que no requiere cambio factual adicional.
- **Estado:** resuelto documentalmente en esta pasada; pendiente de aprobación editorial.

## HIS-005 — Temístocles

- **JSON original:** c. 524–459 a. C.; estadista y estratega ateniense; impulsó el desarrollo naval de Atenas y tuvo un papel decisivo en Salamina (480 a. C.).
- **Discrepancia / precisión:** la bibliografía especializada ofrece c. 524/523–c. 460/459 a. C.; el cargo de arconte en 493/2 y su papel en el desarrollo del Pireo y la ampliación de la flota en 483/2 son elementos concretos. La victoria de Salamina fue aliada y colectiva; no debe atribuirse a un único comandante.
- **Decisión documental:** normalizar a c. 524/523–c. 460/459 a. C. solo si el formato del catálogo admite rangos aproximados explícitos. Mantener una descripción sintética que destaque su impulso a la flota ateniense y su papel estratégico en Salamina. La clasificación actual «Guerreros y Generales» queda abierta a revisión transversal frente a Pericles y otros estadistas con funciones militares.
- **Fuentes:** Andrew Robert Burn / P. J. Rhodes, *Oxford Classical Dictionary*, «Themistocles, Athenian politician, c. 524–459 BCE» (https://academic.oup.com/edited-volume/61673/chapter-abstract/557491019); Sarah Bolmarcich, *The Encyclopedia of Ancient History* (https://onlinelibrary.wiley.com/doi/10.1002/9781444338386.wbeah04307); fuentes antiguas: Heródoto, *Historias*, libro VIII; Tucídides, *Historia de la guerra del Peloponeso*, I.138.
- **Cambio JSON integrado:** se normaliza la fecha a c. 524/523–c. 460/459 a. C. y se añaden referencias. No se cambia la categoría hasta completar revisión comparativa.
- **Estado:** fecha y descripción resueltas documentalmente; categoría en revisión comparativa; ficha pendiente de aprobación.

## HIS-006 — Pericles

- **JSON original:** c. 495–429 a. C.; dirigente político ateniense asociado con la democracia imperial, las grandes obras públicas y el auge cultural de Atenas.
- **Discrepancia / precisión:** las fechas son aproximadas y la evidencia biográfica antigua contiene tradiciones y evaluaciones retrospectivas. El discurso fúnebre transmitido por Tucídides no es una transcripción literal: el historiador explica en I.22 que reconstruye los discursos según lo que consideraba apropiado a cada situación. La democracia ateniense coexistía con un imperio sobre aliados y exclusiones de ciudadanía.
- **Decisión documental:** conservar c. 495–429 a. C.; mantener la asociación con el sistema democrático y el programa monumental, pero describir el contexto como democracia ateniense e imperio marítimo, sin idealizar el periodo. No citar el discurso como palabras literales verificadas.
- **Fuentes:** Ernst Badian, *Encyclopaedia Iranica*, «Pericles» (https://www.iranicaonline.org/articles/pericles/); Tucídides, *Historia de la guerra del Peloponeso*, II.35–46 y II.65; University of Bristol, «II.43: Context and Meaning» (https://www.bristol.ac.uk/classics/research/thucydides/ttt/context/); Stephen V. Tracy, *Pericles: A Sourcebook and Reader* (University of California Press, 2009).
- **Cambio JSON integrado:** se añaden fuentes académicas y primarias; la descripción se mantiene concisa y se precisa como asociación histórica, no como juicio celebratorio.
- **Estado:** resuelto documentalmente en esta pasada; pendiente de aprobación editorial.

## Resumen de decisiones del primer subbloque

| Código | Cronología | Fuentes | Descripción | Clasificación | Aprobación |
|---|---|---|---|---|---|
| HIS-001 | Conservar 356–323; precisar alcance oriental | Reforzadas | Adecuada; campaña acotada al noroeste del subcontinente | Mantener provisional | Pendiente |
| HIS-002 | Conservar 100–44 | Reforzadas | Adecuada; crisis republicana colectiva | Mantener provisional | Pendiente |
| HIS-003 | Conservar 63 a. C.–14 d. C. y título en 27 a. C. | Reforzadas | Matizar «primer emperador» como etiqueta convencional | Mantener provisional | Pendiente |
| HIS-004 | Conservar muerte en 480 a. C. | Reforzadas | Incluir coalición aliada; derrota convertida en símbolo | Mantener provisional | Pendiente |
| HIS-005 | Precisar rango c. 524/523–c. 460/459 | Reforzadas | Adecuada; victoria colectiva | Revisión comparativa | Pendiente |
| HIS-006 | Conservar c. 495–429 | Reforzadas | Matizar democracia imperial y discurso de Tucídides | Mantener provisional | Pendiente |

**Resultado:** 6 registros con revisión documental integrada; 0 aprobados todavía. Los estados originales de verificación se conservan.

## Próximos subbloques

Continuar en orden con HIS-007–HIS-012, luego HIS-013–HIS-018, HIS-019–HIS-024, HIS-025–HIS-030 y HIS-031–HIS-036. Al finalizar, integrar el archivo de 36 personajes, validar JSON y README y continuar con los cinco archivos restantes.
