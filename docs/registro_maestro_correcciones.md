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
| `gobernantes_001_036.json` | HIS-001–HIS-036 | 36 | Integración completada; pendiente de aprobación |
| `guerreros_037_061.json` | HIS-037–HIS-061 | 25 | Integración completada; pendiente de aprobación |
| `sabios_cientificos_062_091.json` | HIS-062–HIS-091 | 30 | Integración completada; pendiente de aprobación |
| `exploradores_092_109.json` | HIS-092–HIS-109 | 18 | Integración completada; pendiente de aprobación |
| `lideres_espirituales_110_127.json` | HIS-110–HIS-127 | 18 | Integración completada; pendiente de aprobación |
| `bloque_final_128_144.json` | HIS-128–HIS-144 | 17 | Integración completada; pendiente de aprobación |
| **Total** | **HIS-001–HIS-144** | **144** | **144 integrados; 0 aprobados** |

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


## HIS-007 — Darío I

- **JSON original:** c. 550–486 a. C.; rey aqueménida que reorganizó la administración imperial, desarrolló sistemas tributarios y promovió obras y comunicaciones.
- **Discrepancia / precisión:** distinguir vida y reinado: 522–486 a. C. La inscripción de Behistún es la versión real de Darío sobre su ascenso y las rebeliones; no es relato neutral. Darío fue el tercer gran rey aqueménida, no el fundador. No atribuirle la invención del sistema de satrapías.
- **Decisión:** conservar c. 550–486 a. C. y explicitar reinado 522–486 a. C. en la descripción. La ficha destaca consolidación imperial, obras e inscripción de Behistún, sin atribuir innovaciones administrativas no demostradas.
- **Fuentes:** Alireza Shapur Shahbazi, *Encyclopaedia Iranica*, «Darius I the Great» (https://www.iranicaonline.org/articles/darius-iii/); *Encyclopaedia Iranica*, «Bisotun iii. Darius's Inscriptions» (https://www.iranicaonline.org/articles/bisotun-iii/); Universidad de Göttingen, «Dareios I» (https://www.uni-goettingen.de/en/132403.html).
- **Cambio JSON integrado:** descripción precisa reinado y naturaleza de Behistún; fuentes académicas, inscripción y documentación institucional añadidas.
- **Estado:** resuelto documentalmente; pendiente de aprobación.

## HIS-008 — Ciro el Grande

- **JSON original:** c. 600/599–530 a. C.; fundador aqueménida; conquistó Media, Lidia y Babilonia.
- **Discrepancia / precisión:** las referencias académicas consultadas respaldan c. 600–530 a. C. como cronología convencional aproximada y la conquista de Babilonia en 539 a. C. El Cilindro de Ciro es una inscripción real de legitimación, restauración cultual y política de gobierno; no es una declaración moderna de derechos humanos.
- **Decisión:** normalizar a c. 600–530 a. C.; mantener su papel como fundador del Imperio aqueménida y precisar la fecha de Babilonia. No incorporar interpretaciones modernas del cilindro como si fueran su contenido literal.
- **Fuentes:** Muhammad A. Dandamayev, *Encyclopaedia Iranica*, «Cyrus II the Great» (https://www.iranicaonline.org/articles/cyrus-iiI/); Dandamayev, «The Cyrus Cylinder» (https://www.iranicaonline.org/articles/cyrus-iv/); British Museum, objeto 1880,0617.1941 (https://www.britishmuseum.org/collection/object/W_1880-0617-1941).
- **Cambio JSON integrado:** fecha aproximada simplificada a c. 600–530 a. C.; se añade Babilonia (539 a. C.) y bibliografía.
- **Estado:** resuelto documentalmente; pendiente de aprobación.

## HIS-009 — Jerjes I

- **JSON original:** c. 519–465 a. C.; hijo de Darío I; dirigió la invasión aqueménida de Grecia en 480 a. C.
- **Discrepancia / precisión:** el reinado está bien establecido entre 486 y 465 a. C.; la fecha de nacimiento c. 519 a. C. es aproximada y debe seguir marcada como tal. La campaña de 480–479 no sometió a las ciudades griegas: Salamina y Platea fueron derrotas persas decisivas para el fracaso de la invasión.
- **Decisión:** conservar el nacimiento aproximado del registro, explicitar reinado 486–465 a. C. y evitar presentar la campaña como conquista de Grecia. La narrativa debe contrastar fuentes griegas con documentación aqueménida.
- **Fuentes:** Ehsan Yarshater, *Encyclopaedia Iranica*, «Iranian History, Pre-Islamic Times» (https://www.iranicaonline.org/articles/iran-ii1-pre-islamic-times/); *Encyclopaedia Iranica*, «Greece i. Greco-Persian Political Relations» (https://www.iranicaonline.org/articles/greece-i/); Heródoto, *Historias*, libros VII–IX.
- **Cambio JSON integrado:** se reformula la biografía para indicar reinado y fracaso de la invasión; se añaden fuentes.
- **Estado:** resuelto documentalmente; pendiente de aprobación.

## HIS-010 — Ramsés II

- **JSON original:** c. 1303–1213 a. C.; faraón de la dinastía XIX; proyectos monumentales y conflicto con los hititas, especialmente Qadesh.
- **Discrepancia / precisión:** las cronologías de referencia del Metropolitan Museum y UCLA sitúan su reinado aproximadamente en 1279–1213 a. C.; el nacimiento c. 1303 a. C. puede conservarse como aproximado, pero debe distinguirse de las fechas de reinado. Qadesh (c. 1274 a. C.) no debe presentarse como victoria estratégica egipcia indiscutida: los relatos egipcios son propaganda real y el control de Qadesh permaneció en manos hititas. El tratado se acordó en el año 21 del reinado, c. 1258/1259 a. C.; no llamarlo sin matiz «el primer tratado de paz de la historia».
- **Decisión:** conservar vida c. 1303–1213 a. C.; añadir el reinado c. 1279–1213 a. C. y describir Qadesh junto al tratado posterior, sin proclamar victoria decisiva.
- **Fuentes:** Metropolitan Museum of Art, lista de gobernantes egipcios (https://www.metmuseum.org/toah/hd/phar/hd_phar.htm); UCLA Encyclopedia of Egyptology, cronología (https://uee.ucla.edu/chronology); James Henry Breasted, *Ancient Records of Egypt*, vol. III, tratado con los hititas (https://adfonteslibrary.org/work-egypt-breasted-ancient-records); James B. Pritchard (ed.), *Ancient Near Eastern Texts Relating to the Old Testament*, versiones egipcia e hitita del tratado.
- **Cambio JSON integrado:** descripción distingue reinado, Qadesh y tratado; se incorporan cronologías institucionales y fuentes del tratado.
- **Estado:** resuelto documentalmente; pendiente de aprobación.

## HIS-011 — Tutmosis III

- **JSON original:** c. 1481–1425 a. C.; faraón de la dinastía XVIII asociado con campañas en el Levante y expansión de la influencia egipcia.
- **Discrepancia / precisión:** las cronologías de UCLA, UCL y Metropolitan Museum sitúan habitualmente su reinado en c. 1479–1425 a. C. Hatshepsut actuó primero como regente del joven rey y después asumió titulatura real y gobernó como faraón junto a él; no reducir toda su relación a una regencia de 21 años sin matiz. Las inscripciones de Karnak son registros reales de campañas y donaciones, no informes neutrales.
- **Decisión:** corregir la fecha inicial a c. 1479 a. C. y conservar c. 1425 a. C. como final. La descripción indica que el reinado comenzó durante la regencia de Hatshepsut y destaca las campañas hasta el Éufrates.
- **Fuentes:** UCLA Encyclopedia of Egyptology, Chronology (https://uee.ucla.edu/chronology); UCL Digital Egypt, Thutmose III (https://www.ucl.ac.uk/museums-static/digitalegypt/chronology/thutmosisiii.html) y Hatshepsut (https://www.ucl.ac.uk/museums-static/digitalegypt/chronology/hatshepsut.html); Digital Karnak (https://digitalkarnak.ucsc.edu/browse-archive/).
- **Cambio JSON integrado:** fechas corregidas a c. 1479–1425 a. C.; descripción precisa el contexto de Hatshepsut; se añaden fuentes.
- **Estado:** resuelto documentalmente; pendiente de aprobación.

## HIS-012 — Cleopatra VII

- **JSON original:** 69–30 a. C.; última gobernante activa ptolemaica; alianzas políticas con Julio César y Marco Antonio.
- **Discrepancia / precisión:** la secuencia de corregencias es compleja: gobernó junto a su padre y hermanos en distintos periodos, y posteriormente con su hijo Ptolomeo XV Cesarión. Accio ocurrió en 31 a. C.; la anexión romana de Egipto se produjo en 30 a. C. La caracterización no debe reducirla a sus relaciones personales ni presentarla simplemente como amante de dos romanos.
- **Decisión:** conservar 69–30 a. C.; describirla como última soberana de la dinastía ptolemaica, destacar corregencias y alianzas políticas, y separar Accio (31) de la anexión (30).
- **Fuentes:** Christelle Fischer-Bovet, *Oxford Classical Dictionary*, «Cleopatra VII, 69–30 BCE» (https://academic.oup.com/edited-volume/61673/chapter-abstract/548065820); Fischer-Bovet, «Egypt, Ptolemaic» (https://academic.oup.com/edited-volume/61673/chapter-abstract/548206937); fuentes antiguas: Plutarco, *Vida de Antonio*; Dion Casio, *Historia romana*, libros 50–51; papiros y monedas ptolemaicas.
- **Cambio JSON integrado:** se precisan corregencias, alianzas, Accio y anexión romana; se añaden fuentes académicas y corpus primarios a cotejar.
- **Estado:** resuelto documentalmente; pendiente de aprobación.

## Resumen de HIS-007 a HIS-012

| Código | Decisión cronológica | Ajuste principal | Estado |
|---|---|---|---|
| HIS-007 | Conservar vida c. 550–486; reinado 522–486 | Behistún como autorrepresentación; no fundador ni inventor de satrapías | Pendiente de aprobación |
| HIS-008 | c. 600–530 | Babilonia 539; Cilindro no es carta moderna de derechos | Pendiente de aprobación |
| HIS-009 | Conservar nacimiento aproximado; reinado 486–465 | Invasión de Grecia fracasó | Pendiente de aprobación |
| HIS-010 | Conservar vida c. 1303–1213; reinado c. 1279–1213 | Qadesh y tratado posterior contextualizados | Pendiente de aprobación |
| HIS-011 | Corregir a c. 1479–1425 | Hatshepsut: regencia y posterior reinado como faraón | Pendiente de aprobación |
| HIS-012 | Conservar 69–30 | Corregencias; Accio 31 y anexión 30 | Pendiente de aprobación |

**Resultado del subbloque:** seis registros actualizados; todos continúan en `en_verificacion`; 0 aprobados. La categoría se conserva sin cambios en esta pasada.


## HIS-013 a HIS-036 — integración documental del primer archivo

### HIS-013 — Nabucodonosor II

- **Discrepancia y decisión documental:** Se mantiene la vida aproximada c. 634–562 a. C.; se explicita reinado 605–562. Se precisan Carquemis (605), Jerusalén (597 y 587/586) y sus obras en Babilonia, sin confundir los dos episodios de Jerusalén.
- **Fuentes:** Encyclopaedia Iranica: https://www.iranicaonline.org/articles/babylonia/babylonia-i/; Karen Radner et al., Encyclopaedia of the Bible and its Reception: https://research-portal.uu.nl/files/211129242/ebr.mainlemma_1292.pdf; crónica babilónica BM 21946.
- **Estado:** integrado; pendiente de aprobación editorial.

### HIS-014 — Sargón de Acad

- **Discrepancia y decisión documental:** La fecha original por siglo era demasiado amplia. Se adopta c. 2340–2285 a. C. como cronología aproximada, reconociendo variantes académicas. Se precisa su derrota de Lugalzagesi y la fundación del estado acadio; Acad aún no ha sido localizada.
- **Fuentes:** Ingo Schrakamp, Wiley: https://doi.org/10.1002/9781118455074.wbeoe395; Metropolitan Museum: https://www.metmuseum.org/essays/the-akkadian-period-ca-2350-2150-b-c; Amanda H. Podany, Oxford: https://academic.oup.com/book/28459/chapter-abstract/229049037.
- **Estado:** integrado; pendiente de aprobación editorial.

### HIS-015 — Gengis Kan

- **Discrepancia y decisión documental:** Se explicita el debate sobre su nacimiento (1162 o 1167); la unificación se formalizó en 1206. Se distingue la fundación del imperio de su expansión posterior por sus sucesores.
- **Fuentes:** David O. Morgan, Encyclopaedia Iranica: https://www.iranicaonline.org/articles/cengiz-khan/; Columbia University: https://afe.easia.columbia.edu/mongols/figures/figures.htm; The Secret History of the Mongols.
- **Estado:** integrado; pendiente de aprobación editorial.

### HIS-016 — Kublai Kan

- **Discrepancia y decisión documental:** Se diferencian su elección como Gran Kan (1260), la proclamación Yuan (1271) y la derrota final de la resistencia Song (1279). Se destaca su gobierno imperial desde China, no solo la conquista.
- **Fuentes:** Metropolitan Museum: https://www.metmuseum.org/zh/met-publications/the-world-of-khubilai-khan-chinese-art-in-the-yuan-dynasty; Columbia University: https://afe.easia.columbia.edu/mongols/pop/khubilai/kkhan_pop.htm; National Geographic: https://education.nationalgeographic.org/resource/kublai-khan/.
- **Estado:** integrado; pendiente de aprobación editorial.

### HIS-017 — Atila

- **Discrepancia y decisión documental:** Se explicita que gobernó primero junto a Bleda y luego en solitario (434–453). Se evita atribuirle como causa única la caída del Imperio romano occidental; la fecha exacta de su muerte tiene discusión académica.
- **Fuentes:** Peter Heather, Oxford Classical Dictionary: https://academic.oup.com/edited-volume/61673/chapter-abstract/548510661; Cameron Barnes, Oxford Bibliographies: https://academic.oup.com/reference/62399/reference-article-abstract/571721214; Péter Kovács (2023): https://doi.org/10.1556/072.2023.00007.
- **Estado:** integrado; pendiente de aprobación editorial.

### HIS-018 — Timur

- **Discrepancia y decisión documental:** Se mantiene 1336–1405 y se precisa su autoridad como emir, no como kan gengisida. Se contextualizan masacres, deportaciones y traslados de artesanos; no se presenta su dominio como unidad estable y homogénea.
- **Fuentes:** Ursula Nashashibi, Encyclopaedia Iranica sobre Ibn Arabshah: https://www.iranicaonline.org/articles/ajaeb-al-maqdur/; Beatrice Forbes Manz, The Rise and Rule of Tamerlane (1989); Encyclopaedia Britannica: https://www.britannica.com/biography/Timur.
- **Estado:** integrado; pendiente de aprobación editorial.

### HIS-019 — Saladino

- **Discrepancia y decisión documental:** Se conserva el nacimiento 1137/1138; se distinguen su ascenso en Egipto, el fin del califato fatimí (1171), la consolidación de poder en Siria y la victoria de Hattin y toma de Jerusalén (1187).
- **Fuentes:** Stephen R. Humphreys, Oxford Bibliographies: https://academic.oup.com/reference/62361/reference-article-abstract/554569932; Encyclopaedia Iranica: https://www.iranicaonline.org/articles/ayyubids/; Nicholas Morton, Oxford: https://academic.oup.com/book/33710/chapter-abstract/288307477.
- **Estado:** integrado; pendiente de aprobación editorial.

### HIS-020 — Ricardo Corazón de León

- **Discrepancia y decisión documental:** Se aclara que la Tercera Cruzada no recuperó Jerusalén. La tregua de Jaffa (1192) permitió el acceso de peregrinos cristianos, pero la ciudad permaneció bajo control de Saladino.
- **Fuentes:** John Gillingham, ODNB: https://academic.oup.com/oxford-dictionary-of-national-biography/reference/63486/reference-article-abstract/581907999; The Royal Family: https://www.royal.uk/richard-i; Stephen J. Spencer, English Historical Review: https://academic.oup.com/ehr/article-abstract/132/556/495/3897145.
- **Estado:** integrado; pendiente de aprobación editorial.

### HIS-021 — Guillermo el Conquistador

- **Discrepancia y decisión documental:** Se mantiene c. 1028–1087; se destaca su condición de duque de Normandía, la conquista de 1066 y la transformación aristocrática y administrativa del reino, evitando atribuir todos los cambios posteriores a un solo acontecimiento.
- **Fuentes:** David Bates, Yale University Press: https://academic.oup.com/yale-scholarship-online/book/15081; Emily Zack Tabuteau, Oxford Bibliographies: https://academic.oup.com/reference/62384/reference-article-abstract/555075362; George Garnett, Oxford: https://academic.oup.com/book/28390.
- **Estado:** integrado; pendiente de aprobación editorial.

### HIS-022 — Carlomagno

- **Discrepancia y decisión documental:** Se conserva c. 747/748–814; fue rey de los francos desde 768 y emperador desde 800. No debe denominarse sin matiz emperador del Sacro Imperio Romano Germánico, institución posterior.
- **Fuentes:** Thomas F. X. Noble, Oxford Bibliographies: https://academic.oup.com/reference/62384/reference-article-abstract/555061229; John France, Oxford Bibliographies: https://academic.oup.com/reference/62399/reference-article-abstract/571522380; Einhard, Vita Karoli Magni.
- **Estado:** integrado; pendiente de aprobación editorial.

### HIS-023 — Federico Barbarroja

- **Discrepancia y decisión documental:** Se normaliza a 1122–1190, rey alemán desde 1152 y emperador desde 1155. Murió ahogado en el río Saleph durante la Tercera Cruzada, no en combate.
- **Fuentes:** Hartmut Heinemann, Historisches Lexikon der Schweiz: https://hls-dhs-dss.ch/de/articles/029199/2009-10-15/; Ferdinand Opll, Friedrich Barbarossa (1990; 3.ª ed. 1998).
- **Estado:** integrado; pendiente de aprobación editorial.

### HIS-024 — Iván el Terrible

- **Discrepancia y decisión documental:** Se precisa que fue gran príncipe de Moscú desde 1533 y primer soberano moscovita coronado formalmente zar en 1547. Su reinado combinó expansión territorial, guerras y represión de la opríchnina.
- **Fuentes:** Alexander Filjushkin, Wiley: https://onlinelibrary.wiley.com/doi/10.1002/9781444338232.wbeow312; Isabel de Madariaga, Ivan the Terrible, Yale University Press (2005); crónicas rusas del siglo XVI.
- **Estado:** integrado; pendiente de aprobación editorial.

### HIS-025 — Pedro el Grande

- **Discrepancia y decisión documental:** Se distingue la coronación conjunta con Iván V (1682), la toma efectiva del poder en 1689 y la proclamación imperial de 1721. Se equilibra la valoración de sus reformas con la coerción estatal y el fortalecimiento de la servidumbre.
- **Fuentes:** Carol B. Stevens, Oxford Bibliographies: https://doi.org/10.1093/obo/9780195399301-0200; Jan Hennings, Wiley: https://doi.org/10.1002/9781118885154.dipl0220; Nicholas V. Riasanovsky, Oxford (1992): https://academic.oup.com/book/47776.
- **Estado:** integrado; pendiente de aprobación editorial.

### HIS-026 — Napoleón Bonaparte

- **Discrepancia y decisión documental:** Se distinguen primer consulado (1799–1804), primer imperio (1804–1814) y retorno durante los Cien Días de 1815. Se equilibran reformas administrativas y Código Civil con las guerras de expansión.
- **Fuentes:** PARES: https://pares.cultura.gob.es/ParesBusquedas20/catalogo/autoridad/47184; Assemblée nationale: https://www.assemblee-nationale.fr/dyn/histoire-et-patrimoine/consulat-et-premier-empire; Ministère de l’Intérieur: https://formation-civique.interieur.gouv.fr/fiches-par-thematiques/histoire-geographie-et-culture/les-regimes-politiques-depuis-1789/le-consulat-1799-1804/.
- **Estado:** integrado; pendiente de aprobación editorial.

### HIS-027 — Simón Bolívar

- **Discrepancia y decisión documental:** Se evita atribuirle en solitario la independencia de cinco países. Su liderazgo fue central en Venezuela, Nueva Granada y Quito; participó en las campañas del Perú y en el proceso de formación de Bolivia. Se destaca la Gran Colombia y el proyecto de unión republicana.
- **Fuentes:** Joshua Simon, Oxford Bibliographies: https://academic.oup.com/reference/62333/reference-article-abstract/554086224; Banrepcultural: https://enciclopedia.banrepcultural.org/Sim%C3%B3n_Bol%C3%ADvar; Carta de Jamaica (1815): https://revistas.upb.edu.co/index.php/derecho/article/view/5406.
- **Estado:** integrado; pendiente de aprobación editorial.

### HIS-028 — José de San Martín

- **Discrepancia y decisión documental:** Se distingue el cruce de los Andes (1817), las campañas de Chile y la expedición al Perú; proclamó la independencia peruana en 1821, pero no concluyó por sí solo toda la guerra en el territorio.
- **Fuentes:** Memoria Chilena: https://www.memoriachilena.gob.cl/602/w3-article-93425.html; Biblioteca Nacional Mariano Moreno: https://museo.bn.gov.ar/noticias/25-de-febrero-de-1778-nace-jose-de-san-martin; Biblioteca Nacional del Perú: https://www.gob.pe/institucion/bnp/noticias/851323-don-jose-de-san-martin-y-su-estrecha-relacion-con-la-bnp.
- **Estado:** integrado; pendiente de aprobación editorial.

### HIS-029 — George Washington

- **Discrepancia y decisión documental:** Se amplía la descripción para incluir su papel como comandante del Ejército Continental y primer presidente (1789–1797). Se incorpora el dato histórico de que fue propietario de personas esclavizadas, necesario para una representación equilibrada.
- **Fuentes:** Mount Vernon: https://www.mountvernon.org/george-washington/the-first-president; Smithsonian: https://www.americanhistory.si.edu/explore/exhibitions/american-presidency/online/resources/list-of-presidents; Library of Congress: https://www.loc.gov/collections/george-washington-papers/articles-and-essays/timeline/the-early-republic/.
- **Estado:** integrado; pendiente de aprobación editorial.

### HIS-030 — Abraham Lincoln

- **Discrepancia y decisión documental:** Se precisa que la Proclamación de Emancipación (1863) se aplicó a zonas en rebelión y no abolió por sí sola la esclavitud nacionalmente. La abolición constitucional llegó con la Decimotercera Enmienda, ratificada en 1865.
- **Fuentes:** U.S. National Archives: https://www.archives.gov/milestone-documents/emancipation-proclamation; Library of Congress: https://www.loc.gov/collections/abraham-lincoln-papers/articles-and-essays/abraham-lincoln-and-emancipation/timeline/; U.S. National Archives, 13th Amendment: https://www.archives.gov/milestone-documents/13th-amendment.
- **Estado:** integrado; pendiente de aprobación editorial.

### HIS-031 — Otto von Bismarck

- **Discrepancia y decisión documental:** Se precisan los cargos: primer ministro prusiano desde 1862, canciller de la Confederación Alemana del Norte desde 1867 y canciller imperial desde 1871 hasta 1890. La unificación se presenta como proceso colectivo bajo liderazgo prusiano.
- **Fuentes:** Otto-von-Bismarck-Stiftung: https://www.bismarck-stiftung.de/otto-von-bismarck/lebenslauf/; Deutsches Historisches Museum: https://www.dhm.de/lemo/biografie/otto-bismarck; German History in Documents and Images: https://germanhistorydocs.org/en/forging-an-empire-bismarckian-germany-1866-1890/bismarcks-putbus-dictations-on-germanys-future-constitution-october-november-1866.
- **Estado:** integrado; pendiente de aprobación editorial.

### HIS-032 — Qin Shi Huang

- **Discrepancia y decisión documental:** Se precisa la unificación de 221 a. C., la breve duración de Qin y las estandarizaciones administrativas. Se evita atribuirle la construcción completa de la Gran Muralla: conectó y amplió defensas preexistentes.
- **Fuentes:** Smithsonian National Museum of Asian Art: https://asia.si.edu/education/educator-resources/teaching-china-with-the-smithsonian/explore-by-dynasty/qin-dynasty/; Metropolitan Museum: https://www.metmuseum.org/de/essays/qin-dynasty-221-206-b-c; Age of Empires: Art of the Qin and Han Dynasties (Metropolitan Museum, 2017).
- **Estado:** integrado; pendiente de aprobación editorial.

### HIS-033 — Liu Bang

- **Discrepancia y decisión documental:** Se mantiene el nacimiento como discutido; se distingue la victoria sobre Xiang Yu, la fundación de Han y su reinado como Gaozu desde 202 a. C.
- **Fuentes:** Stanford Encyclopedia of Philosophy: https://plato.stanford.edu/entries/han-dynasty/; Smithsonian National Museum of Asian Art: https://asia.si.edu/education/educator-resources/teaching-china-with-the-smithsonian/explore-by-dynasty/qin-dynasty/; Sima Qian, Shiji, biografía de Gaozu.
- **Estado:** integrado; pendiente de aprobación editorial.

### HIS-034 — Tokugawa Ieyasu

- **Discrepancia y decisión documental:** Se precisa que Sekigahara (1600) no cerró toda resistencia: el clan Toyotomi fue derrotado en las campañas de Osaka (1614–1615). Ieyasu cedió el título de shōgun en 1605, pero conservó influencia.
- **Fuentes:** National Archives of Japan: https://www.archives.go.jp/exhibition/digital/ieyasu/contents3_01/; Tokugawa Art Museum: https://www.tokugawa-art-museum.jp/wp-content/uploads/2025/03/Tokugawa-Ieyasu_handout.pdf; National Diet Library of Japan: https://dl.ndl.go.jp/view/prepareDownload?itemId=info%3Andljp%2Fpid%2F14579796.
- **Estado:** integrado; pendiente de aprobación editorial.

### HIS-035 — Mehmed II

- **Discrepancia y decisión documental:** Se recuerda su primer reinado (1444–1446) siendo menor y su segundo reinado (1451–1481). La conquista de Constantinopla en 1453 fue seguida de reconstrucción, repoblación y reorganización imperial.
- **Fuentes:** Halil İnalcık, Cambridge History of Islam: https://www.cambridge.org/core/books/abs/cambridge-history-of-islam/rise-of-the-ottoman-empire/307404FFFFA9EAE1488260843074A62F; Abdurrahman Atçıl, Cambridge: https://www.cambridge.org/core/books/abs/scholars-and-sultans-in-the-early-modern-ottoman-empire/scholars-in-mehmed-iis-nascent-imperial-bureaucracy-14531481/525AA44454FF09B7347729B37C8EA811; Çiğdem Kafescioğlu, Penn State University Press: https://www.psupress.org/books/titles/978-0-271-02776-0.html.
- **Estado:** integrado; pendiente de aprobación editorial.

### HIS-036 — Suleimán el Magnífico

- **Discrepancia y decisión documental:** Se conserva 1494/1495–1566 porque las fuentes difieren sobre el nacimiento. Se refuerzan los hitos de expansión, poder naval, codificación legal y mecenazgo; «Magnífico» y «Legislador» se tratan como epítetos históricos.
- **Fuentes:** Güneş Işıksel, Wiley: https://doi.org/10.1002/9781118885154.dipl0267; Linda Komaroff y Suzan Yalman, Metropolitan Museum: https://www.metmuseum.org/pt/essays/the-age-of-suleyman-the-magnificent-r-1520-1566; Getty Research Institute, ULAN: https://www.getty.edu/vow/ULANFullDisplay?find=&nation=&role=&subjectid=500126202.
- **Estado:** integrado; pendiente de aprobación editorial.

## Revisión transversal de clasificación — HIS-001 a HIS-036

Se conservan las categorías actuales en esta pasada, respetando la distribución editorial aprobada. Leónidas y Temístocles permanecen en «Guerreros y Generales»; Pericles, Washington, Lincoln y Bismarck en «Líderes Políticos y Estadistas». Bolívar y San Martín tienen perfiles político-militares mixtos: se mantiene provisionalmente su ubicación en «Gobernantes y Conquistadores», pero quedan señalados para comparación con el criterio aplicado a los siguientes archivos. No se modificaron códigos, nombres ni categorías. La decisión definitiva se reserva para la revisión comparativa global.

**Cierre de integración del archivo:** HIS-001–HIS-036 cuentan con una pasada de integración documental y referencias ampliadas; 36/36 integrados, 0/36 aprobados. Todos continúan en `en_verificacion`. La validación estructural no constituye aprobación histórica.


# Archivo 2 — Guerreros y Generales (HIS-037–HIS-061)

## HIS-037 — Aníbal Barca

- **Discrepancia y decisión documental:** Se conserva c. 247 a. C.; muerte c. 183/182 a. C. Se añade su etapa política como sufete en 196 a. C. y se matizan ruta, cifras y pérdidas del cruce alpino.
- **Fuentes reforzadas:** Oxford Classical Dictionary; Oxford Bibliographies; Polibio, Historias.
- **Cambio JSON integrado:** fechas, biografía breve, hitos, curiosidad y bibliografía revisados; se conserva el estado `en_verificacion`.
- **Estado:** integrado; pendiente de aprobación editorial. En HIS-040, HIS-044 y HIS-061 persisten reservas historiográficas específicas.

## HIS-038 — Escipión el Africano

- **Discrepancia y decisión documental:** Se conserva 236–183 a. C. y se contextualiza Zama como victoria de fuerzas romanas y aliadas, con papel de Masinisa; se evita atribución individual exclusiva.
- **Fuentes reforzadas:** Oxford Classical Dictionary; Polibio, Historias X y XV; Tito Livio XXVI–XXX.
- **Cambio JSON integrado:** fechas, biografía breve, hitos, curiosidad y bibliografía revisados; se conserva el estado `en_verificacion`.
- **Estado:** integrado; pendiente de aprobación editorial. En HIS-040, HIS-044 y HIS-061 persisten reservas historiográficas específicas.

## HIS-039 — Belisario

- **Discrepancia y decisión documental:** Se conserva c. 500–565; se precisan África (533–534), campañas italianas desde 535 y toma de Rávena (540), sin sugerir que la guerra terminó allí. Procopio se identifica como fuente de perspectivas distintas.
- **Fuentes reforzadas:** Oxford Classical Dictionary; Procopio, Guerras e Historia secreta.
- **Cambio JSON integrado:** fechas, biografía breve, hitos, curiosidad y bibliografía revisados; se conserva el estado `en_verificacion`.
- **Estado:** integrado; pendiente de aprobación editorial. En HIS-040, HIS-044 y HIS-061 persisten reservas historiográficas específicas.

## HIS-040 — Sun Tzu

- **Discrepancia y decisión documental:** Se reemplaza la cronología biográfica afirmativa por figura tradicional de historicidad debatida; el texto se fecha probablemente en el siglo IV a. C. y se explica su formación gradual y los manuscritos de Yinqueshan.
- **Fuentes reforzadas:** Stephen Morillo, Encyclopedia of War; Scott Boorman, Cambridge University Press (2024); El arte de la guerra.
- **Cambio JSON integrado:** fechas, biografía breve, hitos, curiosidad y bibliografía revisados; se conserva el estado `en_verificacion`.
- **Estado:** integrado; pendiente de aprobación editorial. En HIS-040, HIS-044 y HIS-061 persisten reservas historiográficas específicas.

## HIS-041 — Guan Yu

- **Discrepancia y decisión documental:** Se corrige la muerte a 219 d. C.; se distingue el general histórico de la deificación posterior y de la representación novelística de Romance de los Tres Reinos.
- **Fuentes reforzadas:** Barend J. ter Haar, Oxford University Press (2017); Sanguozhi, biografía de Guan Yu.
- **Cambio JSON integrado:** fechas, biografía breve, hitos, curiosidad y bibliografía revisados; se conserva el estado `en_verificacion`.
- **Estado:** integrado; pendiente de aprobación editorial. En HIS-040, HIS-044 y HIS-061 persisten reservas historiográficas específicas.

## HIS-042 — Yue Fei

- **Discrepancia y decisión documental:** Se conserva 1103–1142; se contextualiza la ejecución bajo Gaozong y se separa la tradición del tatuaje de lealtad de lo documentalmente demostrable.
- **Fuentes reforzadas:** Yue Du, Journal of Chinese History/Cambridge (2023); Song Shi; Columbia University.
- **Cambio JSON integrado:** fechas, biografía breve, hitos, curiosidad y bibliografía revisados; se conserva el estado `en_verificacion`.
- **Estado:** integrado; pendiente de aprobación editorial. En HIS-040, HIS-044 y HIS-061 persisten reservas historiográficas específicas.

## HIS-043 — Miyamoto Musashi

- **Discrepancia y decisión documental:** Se mantiene c. 1584–1645; se distingue El libro de los cinco anillos como fuente de sus ideas, no como verificación de todos los duelos. Se advierte que las biografías detalladas son tardías.
- **Fuentes reforzadas:** National Diet Library of Japan; Go Rin no Sho; inscripción de Kokura (1654).
- **Cambio JSON integrado:** fechas, biografía breve, hitos, curiosidad y bibliografía revisados; se conserva el estado `en_verificacion`.
- **Estado:** integrado; pendiente de aprobación editorial. En HIS-040, HIS-044 y HIS-061 persisten reservas historiográficas específicas.

## HIS-044 — Hattori Hanzō

- **Discrepancia y decisión documental:** Se señala que Hanzō fue un nombre usado por varias generaciones. La identificación popular con Hattori Masanari (1542–1596) y su papel en 1582 no se presentan como hechos cerrados; se rebaja la certeza sobre la etiqueta ninja.
- **Fuentes reforzadas:** Nippon.com, entrevista a especialista; Samurai Museum; archivos japoneses pendientes de cotejo directo.
- **Cambio JSON integrado:** fechas, biografía breve, hitos, curiosidad y bibliografía revisados; se conserva el estado `en_verificacion`.
- **Estado:** integrado; pendiente de aprobación editorial. En HIS-040, HIS-044 y HIS-061 persisten reservas historiográficas específicas.

## HIS-045 — Juana de Arco

- **Discrepancia y decisión documental:** Se mantiene c. 1412–1431; se incorporan Orleans y Reims (1429), captura (1430), ejecución (1431) y anulación del proceso en 1456. Se evita atribuirle en solitario las victorias.
- **Fuentes reforzadas:** Proceso de 1431; British Library, registros del proceso de rehabilitación; International Joan of Arc Society.
- **Cambio JSON integrado:** fechas, biografía breve, hitos, curiosidad y bibliografía revisados; se conserva el estado `en_verificacion`.
- **Estado:** integrado; pendiente de aprobación editorial. En HIS-040, HIS-044 y HIS-061 persisten reservas historiográficas específicas.

## HIS-046 — El Cid

- **Discrepancia y decisión documental:** Se conserva 1099 como muerte y se marca el nacimiento como incierto (propuestas c. 1043–1054, c. 1048 frecuente). Se distingue documentación de archivo, Historia Roderici y Cantar de mio Cid.
- **Fuentes reforzadas:** Simon Barton, English Historical Review; Alberto Montaner; Historia Roderici.
- **Cambio JSON integrado:** fechas, biografía breve, hitos, curiosidad y bibliografía revisados; se conserva el estado `en_verificacion`.
- **Estado:** integrado; pendiente de aprobación editorial. En HIS-040, HIS-044 y HIS-061 persisten reservas historiográficas específicas.

## HIS-047 — Vercingétorix

- **Discrepancia y decisión documental:** Se elimina el intervalo especulativo de nacimiento; queda como desconocido y se conserva la ejecución en 46 a. C. Se contextualiza Alesia (52 a. C.) y la dependencia de César como fuente adversaria, contrastada con monedas.
- **Fuentes reforzadas:** James Thorne, Encyclopedia of Ancient History; Musée d’Archéologie nationale; César, De bello Gallico VII.
- **Cambio JSON integrado:** fechas, biografía breve, hitos, curiosidad y bibliografía revisados; se conserva el estado `en_verificacion`.
- **Estado:** integrado; pendiente de aprobación editorial. En HIS-040, HIS-044 y HIS-061 persisten reservas historiográficas específicas.

## HIS-048 — Arminio

- **Discrepancia y decisión documental:** Se mantiene c. 18/17 a. C.–21 d. C. como aproximación. Se añade el asesinato por su entorno y se rechaza la proyección de nacionalismo alemán moderno.
- **Fuentes reforzadas:** Tácito, Anales I–II; Veleyo Patérculo II.117–120; arqueología de Kalkriese.
- **Cambio JSON integrado:** fechas, biografía breve, hitos, curiosidad y bibliografía revisados; se conserva el estado `en_verificacion`.
- **Estado:** integrado; pendiente de aprobación editorial. En HIS-040, HIS-044 y HIS-061 persisten reservas historiográficas específicas.

## HIS-049 — Espartaco

- **Discrepancia y decisión documental:** Se eliminan fechas de nacimiento no conocidas; se conserva muerte en 71 a. C. y rebelión 73–71 a. C. Se contextualizan los grupos participantes y el carácter tardío de Plutarco y Apiano.
- **Fuentes reforzadas:** Andrew Lintott, Oxford Classical Dictionary; Plutarco, Vida de Craso; Apiano, Guerras civiles.
- **Cambio JSON integrado:** fechas, biografía breve, hitos, curiosidad y bibliografía revisados; se conserva el estado `en_verificacion`.
- **Estado:** integrado; pendiente de aprobación editorial. En HIS-040, HIS-044 y HIS-061 persisten reservas historiográficas específicas.

## HIS-050 — Hernán Cortés

- **Discrepancia y decisión documental:** Se conserva 1485–1547. La biografía ahora presenta la caída de Tenochtitlan (1521) como resultado de guerra prolongada, alianzas indígenas, epidemias y asedio. Se contrasta la autorrepresentación de las Cartas con testimonios nahuas.
- **Fuentes reforzadas:** Library of Congress, Cartas de relación y Códice Florentino XII; Javier Molina Villeta, Revista Complutense de Historia de América (2024).
- **Cambio JSON integrado:** fechas, biografía breve, hitos, curiosidad y bibliografía revisados; se conserva el estado `en_verificacion`.
- **Estado:** integrado; pendiente de aprobación editorial. En HIS-040, HIS-044 y HIS-061 persisten reservas historiográficas específicas.

## HIS-051 — Francisco Pizarro

- **Discrepancia y decisión documental:** Se corrige c. 1475 a 1478–1541 según autoridad archivística; se distingue la captura de Atahualpa (1532) de la conquista prolongada, con guerra sucesoria, alianzas y resistencias andinas.
- **Fuentes reforzadas:** PARES, Portal de Archivos Españoles; Library of Congress; Felipe Guaman Poma de Ayala, Nueva corónica y buen gobierno.
- **Cambio JSON integrado:** fechas, biografía breve, hitos, curiosidad y bibliografía revisados; se conserva el estado `en_verificacion`.
- **Estado:** integrado; pendiente de aprobación editorial. En HIS-040, HIS-044 y HIS-061 persisten reservas historiográficas específicas.

## HIS-052 — Pancho Villa

- **Discrepancia y decisión documental:** Se precisan 5-6-1878 a 20-7-1923; se conserva el nombre José Doroteo Arango Arámbula con cautela sobre relatos de juventud y cambio de nombre. Se contextualizan alianzas revolucionarias cambiantes.
- **Fuentes reforzadas:** INEHRM; Library of Congress, Chronicling America; Norma Sánchez, UAM/UNAM.
- **Cambio JSON integrado:** fechas, biografía breve, hitos, curiosidad y bibliografía revisados; se conserva el estado `en_verificacion`.
- **Estado:** integrado; pendiente de aprobación editorial. En HIS-040, HIS-044 y HIS-061 persisten reservas historiográficas específicas.

## HIS-053 — Emiliano Zapata

- **Discrepancia y decisión documental:** Se conserva 1879–1919; se atribuye el Plan de Ayala (28-11-1911) al proceso colectivo del zapatismo y a la colaboración de Otilio E. Montaño, no a autoría individual simplificada.
- **Fuentes reforzadas:** Archivo General de la Nación; Secretaría de la Defensa Nacional; Plan de Ayala, fuente primaria/Library of Congress.
- **Cambio JSON integrado:** fechas, biografía breve, hitos, curiosidad y bibliografía revisados; se conserva el estado `en_verificacion`.
- **Estado:** integrado; pendiente de aprobación editorial. En HIS-040, HIS-044 y HIS-061 persisten reservas historiográficas específicas.

## HIS-054 — Shaka Zulu

- **Discrepancia y decisión documental:** Se conserva c. 1787–1828; se advierte que nacimiento y detalles vitales son aproximados. Se evita atribuirle como causa única el Mfecane y se explicita la mezcla de testimonios coloniales y tradiciones orales.
- **Fuentes reforzadas:** John Laband, Encyclopedia of War; Elizabeth A. Eldredge, Cambridge University Press; estudio de testimonios orales zulúes.
- **Cambio JSON integrado:** fechas, biografía breve, hitos, curiosidad y bibliografía revisados; se conserva el estado `en_verificacion`.
- **Estado:** integrado; pendiente de aprobación editorial. En HIS-040, HIS-044 y HIS-061 persisten reservas historiográficas específicas.

## HIS-055 — Robert E. Lee

- **Discrepancia y decisión documental:** Se conserva 1807–1870; se explicita que comandó el Ejército de Virginia del Norte dentro de la Confederación esclavista y se vincula su memoria posterior a la Causa Perdida.
- **Fuentes reforzadas:** Library of Congress; National Archives, documentos de secesión; fuentes confederadas primarias.
- **Cambio JSON integrado:** fechas, biografía breve, hitos, curiosidad y bibliografía revisados; se conserva el estado `en_verificacion`.
- **Estado:** integrado; pendiente de aprobación editorial. En HIS-040, HIS-044 y HIS-061 persisten reservas historiográficas específicas.

## HIS-056 — Ulysses S. Grant

- **Discrepancia y decisión documental:** Se conserva 1822–1885; se precisa el mando supremo desde 1864, Appomattox (1865) y presidencia 1869–1877. Se separan carrera militar y presidencial.
- **Fuentes reforzadas:** National Archives, Papers of Ulysses S. Grant; Library of Congress; Personal Memoirs.
- **Cambio JSON integrado:** fechas, biografía breve, hitos, curiosidad y bibliografía revisados; se conserva el estado `en_verificacion`.
- **Estado:** integrado; pendiente de aprobación editorial. En HIS-040, HIS-044 y HIS-061 persisten reservas historiográficas específicas.

## HIS-057 — Georgy Zhukov

- **Discrepancia y decisión documental:** Se conserva 1896–1974; se precisan Khalkhin Gol, Moscú, Bagration y Berlín, atribuyendo resultados a operaciones colectivas y al Stavka, no a un solo comandante.
- **Fuentes reforzadas:** Geoffrey Roberts, Oxford Bibliographies; documentación militar y memorias de Zhukov.
- **Cambio JSON integrado:** fechas, biografía breve, hitos, curiosidad y bibliografía revisados; se conserva el estado `en_verificacion`.
- **Estado:** integrado; pendiente de aprobación editorial. En HIS-040, HIS-044 y HIS-061 persisten reservas historiográficas específicas.

## HIS-058 — George S. Patton

- **Discrepancia y decisión documental:** Se precisan fechas 11-11-1885 a 21-12-1945, campañas y avance del Tercer Ejército. Se añade la controversia de las bofetadas a soldados con agotamiento de combate (Sicilia, 1943) y el mando aliado.
- **Fuentes reforzadas:** National WWII Museum; U.S. Army Center of Military History; archivos militares estadounidenses.
- **Cambio JSON integrado:** fechas, biografía breve, hitos, curiosidad y bibliografía revisados; se conserva el estado `en_verificacion`.
- **Estado:** integrado; pendiente de aprobación editorial. En HIS-040, HIS-044 y HIS-061 persisten reservas historiográficas específicas.

## HIS-059 — Subutai

- **Discrepancia y decisión documental:** Se conserva c. 1175/1176–1248. Se aclara que fue uno de varios mandos de la campaña europea, junto con Batu y príncipes mongoles; se evitan cifras populares y explicaciones simplistas de 1242.
- **Fuentes reforzadas:** Stephen Pow y Jingjing Liao, Journal of Chinese Military History (2018); Cambridge History of the Mongol Empire; Yuan Shi.
- **Cambio JSON integrado:** fechas, biografía breve, hitos, curiosidad y bibliografía revisados; se conserva el estado `en_verificacion`.
- **Estado:** integrado; pendiente de aprobación editorial. En HIS-040, HIS-044 y HIS-061 persisten reservas historiográficas específicas.

## HIS-060 — Yi Sun-sin

- **Discrepancia y decisión documental:** Se conserva 1545–1598; se incorpora el Nanjung Ilgi como fuente primaria excepcional y se distingue la documentación histórica de reconstrucciones modernas del barco tortuga.
- **Fuentes reforzadas:** UNESCO Memory of the World; Academy of Korean Studies; Nanjung Ilgi.
- **Cambio JSON integrado:** fechas, biografía breve, hitos, curiosidad y bibliografía revisados; se conserva el estado `en_verificacion`.
- **Estado:** integrado; pendiente de aprobación editorial. En HIS-040, HIS-044 y HIS-061 persisten reservas historiográficas específicas.

## HIS-061 — Yasuke

- **Discrepancia y decisión documental:** Se eliminan fechas de nacimiento y muerte no documentadas; se limita la biografía a su presencia en Japón entre 1579 y 1582. No se afirma como hecho demostrado un rango formal de samurái ni un origen geográfico preciso.
- **Fuentes reforzadas:** Thomas Lockley (2019); Historiographical Institute, University of Tokyo; Luís Fróis y estudios académicos sobre sus fuentes.
- **Cambio JSON integrado:** fechas, biografía breve, hitos, curiosidad y bibliografía revisados; se conserva el estado `en_verificacion`.
- **Estado:** integrado; pendiente de aprobación editorial. En HIS-040, HIS-044 y HIS-061 persisten reservas historiográficas específicas.

**Revisión comparativa de clasificación:** se conserva provisionalmente «Guerreros y Generales» para el bloque, respetando la distribución aprobada. HIS-040 requiere tratamiento explícito como figura tradicional/autoría discutida; HIS-044 como identidad familiar compuesta; HIS-050 y HIS-051 son conquistadores y autoridades coloniales además de jefes militares; HIS-053 es también líder agrario y político; HIS-056 combina carrera militar y presidencia; HIS-054 fue asimismo gobernante. Estas dimensiones quedan señaladas para una decisión transversal al comparar las categorías de los 144.

**Cierre de integración:** 25/25 registros actualizados, 0/25 aprobados. Los registros permanecen en `en_verificacion`; la validación técnica del JSON no implica aprobación histórica ni autoriza ilustraciones.


---

# Archivo 3 — Sabios, Científicos e Inventores (HIS-062–HIS-091)

**Estado:** 30/30 integrados documentalmente; 0/30 aprobados. Todos permanecen en `en_verificacion`.

## HIS-062 — Imhotep

- **Discrepancia y decisión integrada:** Se conserva actividad aproximada en el siglo XXVII a. C.; las inscripciones confirman nombre y cargos, pero no expresan de forma explícita su autoría arquitectónica. Se distingue la tradición de su divinización posterior.
- **Fuentes reforzadas:** ARCE; The Metropolitan Museum of Art; UCL Digital Egypt.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-063 — Pitágoras

- **Discrepancia y decisión integrada:** Fechas convencionales aproximadas. No se atribuye con certeza el teorema al individuo: las biografías extensas son tardías y la tradición pitagórica abarca varias generaciones.
- **Fuentes reforzadas:** Stanford Encyclopedia of Philosophy; testimonios antiguos.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-064 — Sócrates

- **Discrepancia y decisión integrada:** Se normaliza nacimiento como 469/470 a. C.; se conserva 399 a. C. para la muerte. Se explica la ausencia de escritos propios y la diversidad de testimonios de Aristófanes, Jenofonte y Platón.
- **Fuentes reforzadas:** Stanford Encyclopedia of Philosophy; Platón; Jenofonte.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-065 — Platón

- **Discrepancia y decisión integrada:** Se conserva c. 427/428–347 a. C.; se incorpora Academia hacia 387 a. C. y se advierte que los diálogos son composiciones filosóficas, no transcripciones.
- **Fuentes reforzadas:** Stanford Encyclopedia of Philosophy; diálogos de Platón.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-066 — Aristóteles

- **Discrepancia y decisión integrada:** Se conserva 384–322 a. C.; se precisa la fundación del Liceo hacia 335 a. C. y se matiza la tutoría de Alejandro y la transmisión del corpus.
- **Fuentes reforzadas:** Stanford Encyclopedia of Philosophy; Internet Encyclopedia of Philosophy; obras de Aristóteles.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-067 — Arquímedes

- **Discrepancia y decisión integrada:** Se conserva c. 287–212 a. C. Se priorizan tratados conservados; las anécdotas del ¡Eureka!, espejos y últimas palabras se identifican como relatos posteriores.
- **Fuentes reforzadas:** MacTutor; tratados de Arquímedes; Plutarco.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-068 — Hipatia

- **Discrepancia y decisión integrada:** Se adopta c. 370–415 d. C. con nacimiento expresamente incierto. No se le atribuye un corpus matemático original conservado con certeza.
- **Fuentes reforzadas:** MacTutor; Sócrates Escolástico; cartas de Sinesio.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-069 — Avicena

- **Discrepancia y decisión integrada:** Se conserva 980–1037; se identifican El canon de la medicina y El libro de la curación como obras diferentes. Su autobiografía fue continuada por un discípulo.
- **Fuentes reforzadas:** Stanford Encyclopedia of Philosophy; Encyclopaedia Iranica; obras de Ibn Sina.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-070 — Al-Juarismi

- **Discrepancia y decisión integrada:** Se mantiene actividad c. 820–850 y origen incierto. Se describe su contribución a la sistematización del álgebra y al origen del término algoritmo, sin presentarlo como creador absoluto.
- **Fuentes reforzadas:** MacTutor; Roshdi Rashed; Al-jabr wa-l-muqabala.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-071 — Leonardo da Vinci

- **Discrepancia y decisión integrada:** Se conservan 1452–1519. Los cuadernos se describen como estudios y proyectos; no se afirma que construyera máquinas modernas que solo dibujó.
- **Fuentes reforzadas:** Science Museum Group; National Gallery of Art; cuadernos conservados.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-072 — Galileo Galilei

- **Discrepancia y decisión integrada:** Se conservan 1564–1642. Se precisa que perfeccionó el telescopio, no lo inventó; se incorpora Sidereus Nuncius (1610) y contexto del proceso de 1633.
- **Fuentes reforzadas:** Stanford Encyclopedia of Philosophy; Galileo Project; documentos históricos.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-073 — Johannes Kepler

- **Discrepancia y decisión integrada:** Se conservan 1571–1630. Se incorporan publicaciones de 1609 y 1619 y el papel esencial de los datos observacionales de Tycho Brahe.
- **Fuentes reforzadas:** NASA Science; MacTutor; obras de Kepler.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-074 — Isaac Newton

- **Discrepancia y decisión integrada:** Se sustituye 1642/1643 por 25-12-1642 (juliano) / 04-01-1643 (gregoriano). Se mantiene 1727 y se contextualiza la disputa del cálculo con Leibniz.
- **Fuentes reforzadas:** MacTutor; Royal Society; Principia y Opticks.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-075 — Nikola Tesla

- **Discrepancia y decisión integrada:** Se conservan 1856–1943 y se precisa Smiljan, entonces Imperio austríaco. Se destacan sistemas polifásicos y motor de inducción sin atribuirle toda la corriente alterna o la radio.
- **Fuentes reforzadas:** Encyclopaedia Britannica; Smithsonian; patentes de Tesla.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-076 — Thomas Edison

- **Discrepancia y decisión integrada:** Se conservan 1847–1931. Se describe el trabajo mediante laboratorio, equipos y comercialización; se evita el mito del inventor solitario de la lámpara o del cine.
- **Fuentes reforzadas:** National Park Service; Thomas A. Edison Papers, Rutgers; Smithsonian.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-077 — Marie Curie

- **Discrepancia y decisión integrada:** Se conservan 1867–1934. Se distingue el Nobel de Física 1903 compartido con Pierre Curie y Henri Becquerel del Nobel de Química 1911 individual; polonio y radio se atribuyen al trabajo conjunto con Pierre.
- **Fuentes reforzadas:** Nobel Prize 1903; Nobel Prize 1911; perfil histórico Nobel.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-078 — Charles Darwin

- **Discrepancia y decisión integrada:** Se conservan 1809–1882. Se incorporan viaje del Beagle, presentación conjunta con Alfred Russel Wallace en 1858 y El origen de las especies (1859).
- **Fuentes reforzadas:** Natural History Museum; Darwin Correspondence Project; Darwin Online.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-079 — Alan Turing

- **Discrepancia y decisión integrada:** Se conservan 1912–1954. Se separan aportes teóricos a la computación y trabajo en Bletchley Park; Enigma se presenta como esfuerzo colectivo.
- **Fuentes reforzadas:** Bletchley Park; Turing Digital Archive; artículo de 1936.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-080 — Albert Einstein

- **Discrepancia y decisión integrada:** Se conservan 1879–1955. Se destacan relatividad y efecto fotoeléctrico; se aclara que el Nobel de 1921 no fue concedido por la relatividad.
- **Fuentes reforzadas:** Nobel Prize 1921; Einstein Papers Project; American Institute of Physics.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-081 — Stephen Hawking

- **Discrepancia y decisión integrada:** Se conservan 1942–2018. Se incorpora colaboración con Penrose y se identifica la radiación de Hawking como predicción teórica no observada directamente en agujeros negros astrofísicos.
- **Fuentes reforzadas:** University of Cambridge; Communications in Mathematical Physics; trabajos Penrose-Hawking.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-082 — Jagadish Chandra Bose

- **Discrepancia y decisión integrada:** Se conservan 1858–1937. Se distinguen ondas milimétricas y fisiología vegetal; no se afirma que inventara la radio ni que demostrara conciencia en plantas.
- **Fuentes reforzadas:** Royal Society Archives AP/75/10 y AP/76/1; Bose Institute.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-083 — Aryabhata

- **Discrepancia y decisión integrada:** Se conserva 476 como nacimiento; la muerte pasa a c. 550 con nota de incertidumbre. Se fecha Aryabhatiya en 499 y se evita atribuirle sin matices la invención del cero.
- **Fuentes reforzadas:** MacTutor; Aryabhatiya; Encyclopaedia Britannica.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-084 — Zhang Heng

- **Discrepancia y decisión integrada:** Se conservan 78–139. Se usa sismoscopio para el instrumento descrito en fuentes antiguas; el original no se conserva y las piezas museísticas son reconstrucciones.
- **Fuentes reforzadas:** Smithsonian National Museum of American History; Hou Hanshu; Sleeswyk y Sivin.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-085 — Shen Kuo

- **Discrepancia y decisión integrada:** Se conservan 1031–1095. Se incorpora Mengxi bitan (c. 1088), la declinación magnética y observaciones geológicas; no se le atribuye la invención de la brújula.
- **Fuentes reforzadas:** Mengxi bitan; Joseph Needham; Encyclopaedia Britannica.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-086 — Benjamin Franklin

- **Discrepancia y decisión integrada:** Se conservan 1706–1790. Se destacan estudios eléctricos y pararrayos. La cometa se trata con cautela: no se afirma que Franklin recibiera directamente un rayo.
- **Fuentes reforzadas:** Library of Congress; Experiments and Observations on Electricity.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-087 — Johannes Gutenberg

- **Discrepancia y decisión integrada:** Se conserva c. 1400–1468. Se define su aporte como desarrollo europeo de tipos móviles metálicos; la impresión y los tipos móviles existían antes en Asia.
- **Fuentes reforzadas:** Library of Congress; UNESCO, Jikji; Biblia de Gutenberg.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-088 — Gregor Mendel

- **Discrepancia y decisión integrada:** Se conservan 1822–1884. Se incorporan presentación de 1865 y publicación de 1866; se contextualiza redescubrimiento c. 1900 y límites de las leyes mendelianas.
- **Fuentes reforzadas:** NHGRI; publicación original; Mendel Museum.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-089 — Niels Bohr

- **Discrepancia y decisión integrada:** Se conservan 1885–1962. Se fecha el modelo atómico en 1913 y el Nobel en 1922; se identifica como modelo histórico superado por la mecánica cuántica moderna.
- **Fuentes reforzadas:** Nobel Prize; Niels Bohr Institute; artículo original de 1913.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-090 — Michael Faraday

- **Discrepancia y decisión integrada:** Se conservan 1791–1867. Se precisan rotación electromagnética de 1821 e inducción de 1831; se reconoce la formalización matemática posterior de Maxwell.
- **Fuentes reforzadas:** Royal Institution; anillo de inducción y generador de Faraday; correspondencia.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.

## HIS-091 — Louis Pasteur

- **Discrepancia y decisión integrada:** Se conservan 1822–1895. Se incorpora vacunación de Joseph Meister el 6-07-1885 y la participación de Émile Roux, Charles Chamberland y Jacques-Joseph Grancher.
- **Fuentes reforzadas:** Institut Pasteur; Science History Institute.
- **Cambio JSON:** fechas, biografía sintética, 2–3 hitos, curiosidad y referencias sustituidas o ampliadas; se conserva `verification_status: en_verificacion`.
- **Estado:** integración documental completada; pendiente de aprobación editorial formal.


**Revisión comparativa de clasificación:** se conserva provisionalmente «Sabios, Científicos e Inventores» como categoría editorial amplia. Las fichas identifican las especialidades históricas concretas y evitan proyectar disciplinas modernas sin matiz. La categoría se revisará comparativamente al cerrar los seis archivos.

**Cierre de integración:** 30/30 registros actualizados; 0/30 aprobados. La validación técnica posterior no equivale a aprobación historiográfica ni autoriza ilustraciones.

 
## Integración transversal — HIS-092 a HIS-109 (Exploradores y Navegantes)

**Archivo:** `data/historicos/exploradores_092_109.json`  
**Informe:** `docs/auditoria_historica/exploradores_092_109_auditoria.md`  
**Resultado:** 18/18 integrados; 0/18 aprobados. Todos permanecen en `en_verificacion`.

### HIS-092 — Cristóbal Colón

- **Decisión integrada:** Navegante genovés que dirigió cuatro expediciones transatlánticas al servicio de la monarquía castellana entre 1492 y 1504. Sus viajes iniciaron un contacto transatlántico sostenido entre Europa y el Caribe, dentro de procesos de conquista, colonización, esclavización y desposesión de pueblos indígenas. Murió sin reconocer que las tierras alcanzadas formaban parte de un continente distinto de Asia. Los diarios originales no se conservan íntegros y su reconstrucción depende de copias, resúmenes y testimonios posteriores.
- **Hitos para tarjeta:** Zarpó en 1492 con la Niña, la Pinta y la nao Santa María; llegó a las Antillas en octubre. Realizó cuatro viajes transatlánticos entre 1492 y 1504. La Corona investigó su gobierno en La Española; las fuentes sobre esa administración deben leerse junto con las denuncias y la documentación colonial.
- **Fuentes reforzadas:** Biblioteca Nacional de España, «Viajes de Cristóbal Colón» (https://www.bne.es/es/colecciones/hispanoamerica/viajes-cristobal-colon); UCLA Center for Early Global Studies, «Repertorium Columbianum: fuentes contemporáneas de los cuatro viajes» (https://cegs.ucla.edu/repertorium-columbianum/); CSIC, «Estudios de historia americana: artículo sobre Colón y su época» (https://estudiosamericanos.revistas.csic.es/index.php/estudiosamericanos/article/view/749).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-093 — Américo Vespucio

- **Decisión integrada:** Mercader, navegante y cosmógrafo florentino vinculado a viajes ibéricos por las costas atlánticas de Sudamérica. Los textos atribuidos a él presentan problemas de autoría, transmisión y veracidad que impiden aceptar sin matices el número tradicional de expediciones. Sus escritos contribuyeron a la discusión cosmográfica europea sobre la existencia de tierras continentales distintas de Asia. En 1507 Martin Waldseemüller empleó el nombre America en su mapa, a partir de la forma latinizada Americus.
- **Hitos para tarjeta:** Trabajó en redes comerciales y navieras de Sevilla y Lisboa. Los viajes que se le atribuyen y la autenticidad de algunas cartas siguen siendo objeto de debate filológico e historiográfico. El mapa de Waldseemüller de 1507 es el primer uso cartográfico conocido del nombre America.
- **Fuentes reforzadas:** Library of Congress, «Recognizing and Naming America: Waldseemüller’s 1507 Map» (https://www.loc.gov/collections/discovery-and-exploration/articles-and-essays/recognizing-and-naming-america/); Ca’ Foscari University Press, «Amerigo Vespucci: The Historical Context of His Explorations and Scientific Contribution» (https://edizionicafoscari.unive.it/en/edizioni4/libri/978-88-6969-403-5/); Pietro T. Omodeo, Nuncius, «The Authenticity of Amerigo Vespucci’s Mundus Novus» (https://doi.org/10.1163/18253911-02902001).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-094 — Fernando de Magallanes

- **Decisión integrada:** Navegante portugués que dirigió inicialmente la expedición de cinco naves organizada por la monarquía hispánica en 1519 para alcanzar las islas de las especias navegando hacia el oeste. La flota atravesó el estrecho que recibió su nombre y entró en el Pacífico. Magallanes murió en Mactán, Filipinas, el 27 de abril de 1521, durante una intervención armada en un conflicto local. La nao Victoria regresó a España en 1522 bajo el mando de Juan Sebastián Elcano, completando la primera circunnavegación documentada.
- **Hitos para tarjeta:** La expedición partió en 1519 con cinco naves; solo la Victoria regresó a España. El paso fue llamado inicialmente estrecho de Todos los Santos. Magallanes murió en Mactán en 1521; Elcano y los supervivientes completaron la circunnavegación en 1522.
- **Fuentes reforzadas:** Mateo Martinić Beroš, Abriu, «Estudio sobre las fuentes primarias de la travesía del estrecho» (https://revistes.ub.edu/index.php/Abriu/article/view/abriu2019.8.4); Archivo General de Indias, PARES, «Declaración de Elcano, Albo y Bustamante sobre el viaje (18 de octubre de 1522)» (https://pares.cultura.gob.es/ParesBusquedas20/catalogo/description/122228); Junta de Andalucía, «Documentos de Magallanes y Elcano y culminación de la circunnavegación» (https://www.juntadeandalucia.es/organismos/culturapatrimoniohistoricoydeporte/areas/cultura/archivos/archivos-consejeria/archivo-real-chancilleria/arcgr-recomienda/paginas/exposicion-magallaneselcanochanchilleria-2022.html).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-095 — Vasco da Gama

- **Decisión integrada:** Navegante portugués cuya expedición de 1497–1499 estableció una ruta marítima directa entre Portugal y la costa de Malabar, en India, rodeando África. Su llegada a Calicut en 1498 fue un hito de la expansión portuguesa en el océano Índico, cuyas redes comerciales y conocimientos náuticos ya estaban desarrollados por sociedades africanas, árabes, persas e indias. Las expediciones portuguesas posteriores recurrieron a la coerción naval y la violencia para imponer intereses comerciales y políticos. Fue nombrado virrey en 1524 y murió ese mismo año en Cochin.
- **Hitos para tarjeta:** Zarpó de Lisboa en julio de 1497 y llegó a Calicut en mayo de 1498. Su primera expedición se conoce, entre otras fuentes, por un diario anónimo atribuido tradicionalmente a un participante. Fue nombrado virrey de la India portuguesa en 1524 y murió en Cochin ese año.
- **Fuentes reforzadas:** UNESCO, Memoria del Mundo, «Diario del primer viaje de Vasco da Gama a la India, 1497–1499» (https://www.unesco.org/es/memory-world/journal-first-voyage-vasco-da-gama-india-1497-1499); Cambridge University Press / Hakluyt Society, «A Journal of the Voyage of Vasco da Gama in 1497–99» (https://www.cambridge.org/core/books/journal-of-the-first-voyage-of-vasco-da-gama-14971499/journal-of-the-voyage-of-vasco-da-gama-in-149799/B47DC1671D3BD096377C4ACEA8DB083D); Stefania Elena Carnemolla, Medicina nei Secoli, «Estudio del relato de Álvaro Velho y el primer viaje» (https://rosa.uniroma1.it/rosa01/medicina_nei_secoli/article/view/904).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-096 — Marco Polo

- **Decisión integrada:** Mercader veneciano que viajó por rutas euroasiáticas junto con su padre Niccolò y su tío Maffeo, según la tradición biográfica y el relato conocido como Il Milione. La obra fue redactada en colaboración con Rustichello de Pisa durante el cautiverio de ambos en Génova y circuló en múltiples versiones manuscritas. Describe la corte de Kublai Kan y diversas regiones de Asia, pero combina experiencias, información recibida y recursos literarios; la fiabilidad de episodios concretos debe evaluarse por separado.
- **Hitos para tarjeta:** La tradición sitúa su partida hacia Asia en 1271 y su regreso a Venecia en 1295. Su relato describe la corte de Kublai Kan y rutas comerciales del Imperio mongol. El texto se asocia a Rustichello de Pisa y presenta una compleja transmisión manuscrita.
- **Fuentes reforzadas:** David Jacoby, Mediterranean Historical Review, «Marco Polo, His Close Relatives, and His Travel Account» (https://www.tandfonline.com/doi/full/10.1080/09518960601030134); The Mariners’ Museum, «Marco Polo: contexto biográfico y viajes» (https://exploration.marinersmuseum.org/subject/marco-polo/); Encyclopaedia Britannica, «Marco Polo: mercader y autor del relato de viajes» (https://www.britannica.com/biography/Marco-Polo).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-097 — Zheng He

- **Decisión integrada:** Almirante de la dinastía Ming, nacido Ma He, que dirigió siete grandes expediciones navales entre 1405 y 1433 durante los reinados de Yongle y Xuande. Las flotas recorrieron el sudeste asiático y el océano Índico hasta puertos de India, Arabia y África oriental. Sus misiones combinaron diplomacia, comercio, relaciones tributarias y demostración del poder estatal Ming; no fueron viajes privados ni deben describirse como una versión de la exploración europea.
- **Hitos para tarjeta:** Dirigió siete expediciones navales entre 1405 y 1433. Las inscripciones de Liujiagang y Changle de 1431 ofrecen testimonios vinculados a las expediciones. Las cifras extraordinarias sobre el tamaño de los llamados barcos del tesoro siguen discutidas y no deben presentarse como datos seguros.
- **Fuentes reforzadas:** Edward L. Dreyer, Smithsonian Libraries, «Zheng He: China and the Oceans in the Early Ming Dynasty, 1405–1433» (https://www.si.edu/object/siris_sil_843382); Hong Kong Museum of History, «Sailing West: Admiral Zheng He’s Voyages» (https://hk.history.museum/en/web/mh/exhibition/2006_past_07.html); Dolors Folch, National Geographic, «Seven Voyages of Zheng He» (https://www.nationalgeographic.com/history/history-magazine/article/china-zheng-he-naval-explorer-sailed-treasure-fleet-east-africa).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-098 — Leif Erikson

- **Decisión integrada:** Explorador nórdico conocido por las sagas islandesas, que lo relacionan con viajes desde Groenlandia hacia tierras llamadas Vinland. La arqueología confirma presencia nórdica en L’Anse aux Meadows, Terranova, en el siglo XI; un estudio dendrocronológico fechó actividad allí en 1021. Esa evidencia no demuestra por sí sola que Leif encabezara personalmente todos los viajes narrados. Las sagas fueron escritas generaciones después y ofrecen versiones distintas de los episodios.
- **Hitos para tarjeta:** Las sagas principales que lo mencionan son la Saga de los groenlandeses y la Saga de Erik el Rojo. L’Anse aux Meadows es el único asentamiento nórdico confirmado en América del Norte. Un estudio de anillos de árboles estableció presencia nórdica en el sitio en 1021.
- **Fuentes reforzadas:** Nature, «Evidence for European presence in the Americas in AD 1021» (https://www.nature.com/articles/s41586-021-03972-8); UNESCO World Heritage Centre, «L’Anse aux Meadows National Historic Site» (https://whc.unesco.org/en/list/4); Parks Canada, «L’Anse aux Meadows National Historic Site» (https://parks.canada.ca/lhn-nhs/nl/meadows).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-099 — James Cook

- **Decisión integrada:** Oficial naval y cartógrafo británico que comandó tres expediciones por el Pacífico entre 1768 y 1779. Sus diarios y levantamientos cartográficos registraron Nueva Zelanda, la costa oriental de Australia y numerosas islas desde una perspectiva europea, dentro de proyectos científicos y de expansión imperial. En el segundo viaje cruzó el círculo polar antártico, sin avistar el continente. Murió en Kealakekua Bay, Hawái, el 14 de febrero de 1779, durante un enfrentamiento que causó también numerosas muertes hawaianas y británicas.
- **Hitos para tarjeta:** En Tahití observó el tránsito de Venus de 1769 como parte de un programa científico internacional. Cartografió Nueva Zelanda y la costa oriental de Australia en 1769–1770. En su segundo viaje cruzó el círculo polar antártico; murió en Hawái durante su tercera expedición.
- **Fuentes reforzadas:** National Museum of Australia, «Cook’s journal: transcripciones del viaje del Endeavour» (https://www.nma.gov.au/exhibitions/endeavour-voyage/cooks-journal); National Library of Australia, «James Cook and his voyages: colecciones y diarios» (https://www.library.gov.au/research/guides-and-resources/guides-selected-collections/james-cook-and-his-voyages); National Museum of Australia, «Timeline of Cook and Forster voyages» (https://www.nma.gov.au/explore/features/cook_forster/background/timeline).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-100 — Roald Amundsen

- **Decisión integrada:** Explorador polar noruego que encabezó la expedición de la Gjøa, primera travesía completa del Paso del Noroeste realizada por una misma expedición y embarcación entre 1903 y 1906. En 1911 dirigió la expedición que alcanzó el Polo Sur geográfico el 14 de diciembre, antes que el equipo de Robert Falcon Scott. Su trabajo ártico dependió de observaciones científicas y de conocimientos prácticos inuit sobre vestimenta, desplazamiento y adaptación al entorno. Desapareció en 1928 durante una misión aérea de rescate en el Ártico.
- **Hitos para tarjeta:** La Gjøa completó el Paso del Noroeste entre 1903 y 1906, tras varias invernadas. Alcanzó el Polo Sur el 14 de diciembre de 1911 con un equipo que utilizó esquís y trineos de perros. Desapareció en junio de 1928 durante la búsqueda de la expedición de Umberto Nobile.
- **Fuentes reforzadas:** Fram Museum, «The Gjøa Expedition (1903–1906)» (https://frammuseum.no/en/polar-history/expeditions/the-gjoa-expedition-1903-1906/); Amundsen Museum, «Gjøa Expedition: crew, local Inuit participation and expedition records» (https://amundsen.mia.no/en/expeditions/gjoa-expedition/); Royal Museums Greenwich, «Roald Amundsen North-West Passage expedition 1903–06» (https://www.rmg.co.uk/stories/maritime-history/roald-amundsen-north-west-passage-expedition-1903-06).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-101 — Ernest Shackleton

- **Decisión integrada:** Explorador polar anglo-irlandés que dirigió la Expedición Imperial Transantártica de 1914–1917. El Endurance quedó atrapado en el mar de Weddell y fue destruido por el hielo en 1915, antes de que comenzara el cruce continental previsto. Shackleton y cinco compañeros navegaron desde isla Elefante hasta Georgia del Sur para pedir ayuda; los 28 integrantes de la partida del Endurance sobrevivieron. La partida del mar de Ross, perteneciente a la misma expedición, perdió tres hombres.
- **Hitos para tarjeta:** El Endurance quedó atrapado en el hielo en 1915 y se hundió antes de iniciar el cruce de la Antártida. Shackleton y cinco compañeros cruzaron en el James Caird desde isla Elefante hasta Georgia del Sur. Los 28 integrantes de la partida del Endurance sobrevivieron; tres miembros de la partida del mar de Ross murieron.
- **Fuentes reforzadas:** Library of Congress, «South: The Story of Shackleton’s Last Expedition» (https://www.loc.gov/item/20001604/); Scott Polar Research Institute, «Endurance expedition: historical collections and records» (https://www.spri.cam.ac.uk/); Royal Museums Greenwich, «Ernest Shackleton and the Endurance expedition» (https://www.rmg.co.uk/stories/topics/ernest-shackleton).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-102 — Ibn Battuta

- **Decisión integrada:** Jurista y viajero marroquí que salió de Tánger en 1325 para peregrinar a La Meca y viajó durante casi tres décadas por regiones de África, Oriente Próximo, Asia central, India y el sudeste asiático. La Rihla fue dictada por Ibn Battuta por encargo del sultán meriní Abu Inan y redactada por el secretario Ibn Juzayy, que terminó su trabajo en 1355–1356. No es un diario de campo continuo: combina memoria, convenciones literarias, información recibida y experiencia personal; algunos tramos del itinerario siguen debatidos.
- **Hitos para tarjeta:** Partió de Tánger el 14 de junio de 1325 para realizar la peregrinación a La Meca. Sirvió como juez en el sultanato de Delhi y visitó diversas cortes del mundo islámico. La Rihla fue dictada y editada por Ibn Juzayy por encargo del sultán Abu Inan.
- **Fuentes reforzadas:** Library of Congress, «Ibn Battuta’s Rihla: manuscrito y edición digital» (https://www.loc.gov/item/2021666192/); Islam Museum, «The Rihla of Ibn Battuta: composición y papel de Ibn Juzayy» (https://islam.museum/en/work/rihla-ibn-battuta/); University of California, Berkeley ORIAS, «The Travels of Ibn Battuta: itinerario y contexto» (https://orias.berkeley.edu/node/163).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-103 — David Livingstone

- **Decisión integrada:** Médico, misionero y explorador escocés que recorrió regiones del África austral y central. Entre 1852 y 1856 atravesó el continente de oeste a este con apoyo de guías, comunidades y redes africanas. Llegó en 1855 a Mosi-oa-Tunya, conocida por pueblos locales, y difundió el nombre colonial Victoria Falls. Su última expedición, iniciada en 1866, investigó regiones vinculadas a los grandes lagos y las fuentes del Nilo. Su oposición al comercio esclavista coexistió con una misión cristiana y una visión victoriana del comercio y la expansión europea.
- **Hitos para tarjeta:** Atravesó África austral de oeste a este entre 1852 y 1856. Llegó a Mosi-oa-Tunya en 1855 y popularizó el nombre Victoria Falls. Sus diarios de la última expedición (1866–1873) documentan sus viajes por África central.
- **Fuentes reforzadas:** Library of Congress, «The Last Journals of David Livingstone, 1865–1873» (https://www.loc.gov/item/17009532/); South African History Online, «David Livingstone: biografía crítica» (https://sahistory.org.za/people/david-livingstone); University of Glasgow, «David Livingstone: manuscritos y colecciones digitalizadas» (https://www.gla.ac.uk/myglasgow/archivespecialcollections/digitisedcollections/provenance/davidlivingstone/).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-104 — Vasco Núñez de Balboa

- **Decisión integrada:** Conquistador castellano que en 1513 encabezó una expedición a través del istmo de Panamá y fue el primer europeo del que se conserva registro de haber avistado el océano Pacífico desde ese istmo. La expedición dependió de guías, informantes, cargadores y alianzas indígenas. La toma de posesión del llamado Mar del Sur fue una reivindicación imperial castellana, no un descubrimiento del océano ni una transferencia de soberanía reconocida por los pueblos de la región. Fue ejecutado en Acla en 1519 por orden de Pedrarias Dávila tras un conflicto político.
- **Hitos para tarjeta:** Encabezó en 1513 la expedición castellana que llegó al Pacífico desde el istmo de Panamá. La travesía dependió de guías y aliados indígenas, cuya participación debe reconocerse. Fue ejecutado en Acla en 1519 por orden de Pedrarias Dávila.
- **Fuentes reforzadas:** HISTORY, «Vasco Núñez de Balboa: expedition of 1513 and execution» (https://www.history.com/articles/vasco-nunez-de-balboa); The Mariners’ Museum, «Vasco de Balboa: biography and exploration» (https://exploration.marinersmuseum.org/subject/vasco-de-balboa/); PARES, Archivo General de Indias, «Royal instructions concerning assets after the condemnation of Balboa» (https://pares.cultura.gob.es/ParesBusquedas20/catalogo/description/376025).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-105 — Álvar Núñez Cabeza de Vaca

- **Decisión integrada:** Explorador, funcionario y cronista castellano que sobrevivió al desastre de la expedición de Pánfilo de Narváez, iniciada en 1527 y desarticulada tras naufragios y dispersión en 1528. Cabeza de Vaca y otros tres supervivientes alcanzaron asentamientos españoles en Nueva España en 1536, después de años entre distintas comunidades indígenas. Su Naufragios, publicado en 1542, es un testimonio excepcional sobre esas sociedades y experiencias, pero fue redactado para la Corona y refleja intereses y categorías coloniales. Más tarde fue gobernador del Río de la Plata.
- **Hitos para tarjeta:** Fue uno de los cuatro supervivientes que llegaron a Nueva España en 1536. Naufragios se publicó en 1542 y relata la expedición de Narváez y los años de supervivencia. Posteriormente fue gobernador del Río de la Plata y entró en conflicto con autoridades coloniales.
- **Fuentes reforzadas:** Smithsonian Libraries and Archives, «Relación / Naufragios de Álvar Núñez Cabeza de Vaca: edición histórica» (https://www.si.edu/es/object/relation-alvar-nunez-cabeca-de-vaca-translated-spanish-buckingham-smith%3Asiris_sil_260155); Library of Congress, «Naufragios: registro bibliográfico y documentación» (https://www.loc.gov/item/04008076/); Oxford Dictionary of National Biography / American National Biography, «Álvar Núñez Cabeza de Vaca: referencia biográfica» (https://academic.oup.com/american-national-biography/reference/63042/reference-article-abstract/570515360).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-106 — Richard Francis Burton

- **Decisión integrada:** Explorador, traductor, orientalista y oficial británico conocido por sus viajes por Asia, África y Oriente Próximo. En 1853 peregrinó a La Meca bajo identidad musulmana y disfraz, según sus propios escritos. En 1857–1858 dirigió con John Hanning Speke una expedición a África oriental que llegó al lago Tanganica; Speke continuó hacia el lago Victoria, que propuso como fuente del Nilo. Burton fue un prolífico escritor y traductor, pero sus obras deben leerse críticamente por sus intervenciones editoriales y los marcos orientalistas y coloniales del siglo XIX.
- **Hitos para tarjeta:** Realizó la peregrinación a La Meca en 1853 bajo identidad y vestimenta musulmanas. La expedición con John Hanning Speke llegó al lago Tanganica en 1858. Publicó traducciones influyentes, entre ellas Las mil y una noches, acompañadas de notas e intervenciones editoriales.
- **Fuentes reforzadas:** Royal Asiatic Society Archives, «Richard Francis Burton: archivo biográfico y colecciones» (https://www.royalasiaticarchives.org/index.php/richard-burton); National Portrait Gallery, «Sir Richard Francis Burton: biografía y referencias» (https://www.npg.org.uk/collections/search/personExtended/mp00673/sir-richard-francis-burton?tab=biography); Royal Asiatic Society, «Richard Francis Burton (1821–1890)» (https://royalasiaticsociety.org/richard-francis-burton-1821-1890/).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-107 — John Cabot

- **Decisión integrada:** Navegante de origen italiano, conocido como John Cabot en Inglaterra, que obtuvo apoyo de Enrique VII para explorar el Atlántico norte. En 1497 realizó una travesía desde Bristol en el Matthew y llegó a una costa de Norteamérica, cuya localización exacta sigue debatida. La documentación contemporánea incluye cartas de comerciantes y diplomáticos, pero no se conserva un relato escrito por Cabot. Emprendió otra expedición en 1498; su destino final no está documentado. Sus viajes fueron utilizados después por Inglaterra para reivindicaciones territoriales.
- **Hitos para tarjeta:** Recibió cartas patentes de Enrique VII en 1496 para explorar bajo bandera inglesa. Llegó a una costa norteamericana en 1497 a bordo del Matthew; el punto exacto de desembarco es debatido. Una nueva expedición partió en 1498 y se desconoce el destino de Cabot.
- **Fuentes reforzadas:** Dictionary of Canadian Biography, «John Cabot: contemporary documentation and debated landfall» (https://www.biographi.ca/en/bio/101.html); The National Archives (UK), «John Cabot: letters patent of Henry VII» (https://www.nationalarchives.gov.uk/education/resources/significant-people-collection/john-cabot/); University of Bristol, Maritime History, «First Letters Patent granted by Henry VII to John Cabot, 5 March 1496» (https://www.bristol.ac.uk/Depts/History/Maritime/Sources/1496cabotpatent.htm).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-108 — Bartolomeu Dias

- **Decisión integrada:** Navegante portugués que dirigió la expedición de 1487–1488 que rodeó el extremo meridional de África y alcanzó aguas del océano Índico desde el Atlántico. El viaje demostró para la navegación portuguesa la continuidad marítima alrededor del continente y preparó la ruta que Vasco da Gama seguiría hacia India. La denominación Cabo das Tormentas se asocia a la expedición; la tradición atribuye a Juan II el nombre Cabo da Boa Esperança. Dias acompañó a la flota de Cabral en 1500 y murió durante la travesía.
- **Hitos para tarjeta:** Rodeó el extremo meridional de África en 1488. La expedición llamó al cabo Cabo das Tormentas; la monarquía portuguesa difundió el nombre Cabo da Boa Esperança. Acompañó a la expedición de Pedro Álvares Cabral en 1500 y murió en el naufragio de la flota.
- **Fuentes reforzadas:** Marinha Portuguesa, «Bartolomeu Dias: expedición y paso al Índico» (https://www.marinha.pt/en/a-marinha/historia/servir-portugal/Pages/default.aspx); HISTORY, «Bartolomeu Dias: expedición de 1487–1488» (https://www.history.com/articles/bartolomeu-dias); Visit Portugal, «Cronología de las navegaciones portuguesas» (https://www.visitportugal.com/en/NR/exeres/31ADBA57-48F6-470C-94C6-5C42F44486AF).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-109 — Francisco de Orellana

- **Decisión integrada:** Conquistador castellano que, tras separarse de la expedición de Gonzalo Pizarro, descendió el río Napo y el Amazonas hasta el Atlántico entre 1541 y 1542. La separación, sus motivos y las acusaciones posteriores fueron objeto de controversia entre los participantes. Gaspar de Carvajal, integrante de la expedición, redactó una relación que constituye una fuente primaria esencial, aunque situada en una perspectiva colonial. La travesía recorrió regiones habitadas por sociedades indígenas con redes fluviales y políticas propias. Orellana organizó una segunda expedición y murió en 1546.
- **Hitos para tarjeta:** Descendió el Napo y el Amazonas entre 1541 y 1542 tras separarse de Gonzalo Pizarro. Gaspar de Carvajal dejó una relación del viaje, fuente primaria que requiere lectura crítica. La expedición recorrió territorios densamente habitados; la mención de mujeres guerreras no demuestra una sociedad idéntica a las amazonas clásicas.
- **Fuentes reforzadas:** Smithsonian Libraries and Archives, «Relación del nuevo descubrimiento del Río Grande de las Amazonas (1541–1542)» (https://www.si.edu/object/relacion-del-nuevo-descubrimiento-del-rio-grande-de-las-amazonas-1541-1542-fray-gaspar-de-carvajal%3Asiris_sil_452582); Biblioteca de la Casa de la Cultura Ecuatoriana, «Relación del nuevo descubrimiento del río grande de las Amazonas» (https://biblioteca.casadelacultura.gob.ec/bib/59264); Encyclopaedia Britannica, «Francisco de Orellana: expedición amazónica» (https://www.britannica.com/biography/Francisco-de-Orellana).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

**Balance global de integración transversal tras este archivo:** 109/144 registros integrados (75,69 %), 35 pendientes de integración y 0/144 aprobados. La fase de examen individual sigue siendo 144/144; no debe confundirse con aprobación.


## Integración transversal — HIS-110 a HIS-127 (Líderes Espirituales y Religiosos)

**Archivo:** `data/historicos/lideres_espirituales_110_127.json`  
**Informe:** `docs/auditoria_historica/lideres_espirituales_110_127_auditoria.md`  
**Resultado:** 18/18 integrados; 0/18 aprobados. Todos permanecen en `en_verificacion`.

### HIS-110 — Siddhartha Gautama (Buda)

- **Decisión integrada:** Maestro ascético del clan Shakya cuya enseñanza dio origen a la comunidad budista. Las tradiciones sitúan su despertar en Bodh Gaya y su actividad docente en la llanura del Ganges. La fecha exacta de su vida sigue debatida: las cronologías tradicionales y las reconstrucciones modernas difieren, y los discursos atribuidos a él fueron transmitidos oralmente antes de su fijación escrita. La ficha distingue al maestro histórico de las biografías hagiográficas desarrolladas posteriormente.
- **Hitos para tarjeta:** La tradición sitúa su despertar en Bodh Gaya y su primera enseñanza en el Parque de los Ciervos, en Sarnath. La comunidad monástica temprana fue esencial para preservar y transmitir las enseñanzas atribuidas al Buda. No existe una fecha biográfica consensuada; «siglo V a. C.» es una aproximación académica, no una fecha exacta.
- **Fuentes reforzadas:** Oxford Bibliographies, «Gotama, the Historical Buddha» (https://academic.oup.com/reference/62340/reference-article-abstract/554143156); Oxford Bibliographies, «History of the Buddhist Canon» (https://academic.oup.com/reference/62340/reference-article-abstract/554134298); University of New England, «A Discussion on the Determination of the Date of the Historical Buddha» (https://researchers.une.edu.au/en/publications/a-discussion-on-the-determination-of-the-date-of-the-historical-b-5/).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-111 — Confucio

- **Decisión integrada:** Pensador y maestro del estado de Lu, conocido como Kongzi o Maestro Kong. Las fuentes antiguas lo asocian con la enseñanza de la virtud, los ritos, el aprendizaje, las obligaciones familiares y el buen gobierno. Las Analectas reúnen diálogos y dichos transmitidos por discípulos y generaciones posteriores; no son un libro redactado y cerrado por Confucio. El confucianismo posterior seleccionó, comentó y transformó esa herencia durante siglos.
- **Hitos para tarjeta:** La tradición sitúa su actividad docente en el estado de Lu, durante el periodo de Primaveras y Otoños. Las Analectas contienen materiales de transmisión diversa y no pueden tratarse como transcripción literal de sus palabras. Su autoridad fue reinterpretada por escuelas y gobiernos chinos posteriores, especialmente durante la época imperial.
- **Fuentes reforzadas:** Stanford Encyclopedia of Philosophy, «Confucius» (https://plato.stanford.edu/entries/confucius/); Internet Encyclopedia of Philosophy, «Confucius» (https://iep.utm.edu/confucius/); Stanford Encyclopedia of Philosophy, «Confucius — textual traditions and Analects» (https://plato.stanford.edu/archives/sum2020/entries/confucius/).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-112 — Lao Tsé

- **Decisión integrada:** Figura tradicional asociada al Daodejing, uno de los textos centrales del pensamiento daoísta. La obra reflexiona sobre el Dao, la virtud, la espontaneidad y el gobierno no coercitivo. No está demostrado que todo el texto proceda de un solo autor llamado Laozi: manuscritos de Guodian y Mawangdui muestran versiones y agrupaciones anteriores al texto recibido. La biografía del archivero que abandona China pertenece a la tradición y no puede verificarse como relato biográfico.
- **Hitos para tarjeta:** Los manuscritos de Guodian, depositados hacia 300 a. C., contienen pasajes que hoy forman parte del Daodejing. Los manuscritos de Mawangdui, hallados en una tumba sellada en 168 a. C., conservan otra organización textual. El Daodejing fue transmitido y editado en versiones distintas; la división actual en 81 capítulos no es universal ni necesariamente original.
- **Fuentes reforzadas:** Stanford Encyclopedia of Philosophy, «Laozi — textual traditions and manuscripts» (https://plato.stanford.edu/entries/laozi/); Oxford University Press, «The Daode Jing: A Guide — Livia Kohn» (https://academic.oup.com/book/41504); Cambridge University Press, «Early Daoist Philosophy: The Dao De Jing as a Metaphysical Treatise» (https://www.cambridge.org/core/books/abs/an-introduction-to-chinese-philosophy/early-daoist-philosophy-the-dao-de-jing-as-a-metaphysical-treatise/DBD3F495C2B976BBE8E1E2423BE9FC8A).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-113 — Zoroastro

- **Decisión integrada:** Profeta y maestro religioso asociado al zoroastrismo. Los Gathas, himnos en avéstico antiguo preservados en el Avesta, son la fuente textual más próxima a su pensamiento y se asocian tradicionalmente con Zarathustra. La datación de su vida depende de argumentos lingüísticos e históricos y no cuenta con sincronismos externos firmes: se han propuesto cronologías muy distintas, incluida una fecha cercana a 1000 a. C. y otra alrededor de 600 a. C. Su lugar de origen tampoco está establecido con precisión.
- **Hitos para tarjeta:** Los Gathas constituyen el núcleo más antiguo del Avesta y la fuente central para estudiar su pensamiento. La datación de Zarathustra se debate entre propuestas muy distantes; c. 1000 a. C. es una hipótesis, no una fecha segura. La tradición relaciona su enseñanza con Ahura Mazda, la verdad y la elección moral.
- **Fuentes reforzadas:** Encyclopaedia Iranica, «Zoroaster: General Survey» (https://www.iranicaonline.org/articles/zoroaster-ii-general-survey/); Encyclopaedia Iranica, «Zoroaster in the Avesta» (https://www.iranicaonline.org/articles/zoroaster-iii-zoroaster-in-the-avesta/); Wiley / Prods Oktor Skjærvø, «The Gathas, a Forgotten Masterpiece» (https://onlinelibrary.wiley.com/doi/10.1002/9781118635193.ctwl0020).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-114 — Mahavira

- **Decisión integrada:** Maestro espiritual jaina conocido también como Vardhamana y considerado por la tradición el vigésimo cuarto tirthankara de la era actual. Su enseñanza ascética destacó la no violencia, la verdad, la no apropiación y el desapego. La tradición jaina le atribuye un papel decisivo en la organización de la comunidad de monjes, monjas y laicos; no debe describirse como fundador absoluto de una religión que se considera mucho más antigua. Las fechas tradicionales difieren de varias reconstrucciones históricas modernas.
- **Hitos para tarjeta:** La tradición jaina lo considera el vigésimo cuarto tirthankara y lo vincula con la consolidación de la comunidad jaina. Los textos tempranos jainas, como el Ācārāṅga y el Kalpa Sūtra, transmiten episodios de su vida, pero su redacción y transmisión requieren crítica textual. Sus fechas tradicionales 599–527 a. C. no son universalmente aceptadas por la investigación moderna.
- **Fuentes reforzadas:** Routledge Encyclopedia of Philosophy, «Mahāvīra (6th–5th century BC)» (https://www.rep.routledge.com/articles/biographical/mahavira-6th-5th-century-bc/v-1); Harvard University, «A Timeline of South Asian History — Bibliography» (https://timelinesouthasianhistory.hsites.harvard.edu/bibliography); Oxford History of Historical Writing, «Historical traditions in early India» (https://culturahistorica.org/wp-content/uploads/2020/05/thapar-historical-traditions-early-india.pdf).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-115 — Moisés

- **Decisión integrada:** Figura fundacional de las tradiciones judía, cristiana e islámica. En la Biblia hebrea aparece como líder del Éxodo, mediador de la alianza y transmisor de la Ley; el Corán también lo presenta como profeta. La investigación histórica estudia la formación de las tradiciones mosaicas y la composición del Pentateuco, pero no dispone de una biografía contemporánea independiente que confirme los episodios bíblicos ni permita fijar fechas de nacimiento o muerte. La importancia religiosa de Moisés debe distinguirse de lo que puede establecerse históricamente.
- **Hitos para tarjeta:** La tradición bíblica lo vincula con el Éxodo, la alianza del Sinaí y la transmisión de la Ley. El Pentateuco es una colección textual de composición y redacción complejas, no un testimonio unitario contemporáneo. No existe consenso histórico que permita fijar una cronología biográfica de Moisés o verificar de manera independiente todos los episodios del Éxodo.
- **Fuentes reforzadas:** Oxford Scholarship Online, «Moses and the Exodus — James K. Hoffmeier» (https://academic.oup.com/book/25374/chapter-abstract/192467684); Society of Biblical Literature, «Bible Odyssey: Moses» (https://www.bibleodyssey.org/people/main-articles/moses/); Encyclopaedia Britannica, «Moses: Hebrew prophet» (https://www.britannica.com/biography/Moses-Hebrew-prophet).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-116 — Abraham

- **Decisión integrada:** Patriarca central de las tradiciones judía, cristiana e islámica. El Génesis lo presenta como Abram, llamado a dejar su tierra y establecerse en Canaán, y como antepasado de una promesa y alianza. La investigación puede estudiar la antigüedad, geografía y formación de las tradiciones patriarcales, pero no dispone de evidencia contemporánea concluyente que identifique al Abraham individual ni confirme los acontecimientos narrados. Debe describirse como figura fundacional de tradición, no como biografía históricamente comprobada.
- **Hitos para tarjeta:** El Génesis sitúa sus relatos entre Mesopotamia y Canaán, dentro de narraciones sobre parentesco, migración y alianza. Las tradiciones sobre Abraham contienen elementos de distintas épocas y no pueden fecharse como una biografía unitaria. Su figura es central para las genealogías religiosas de judaísmo, cristianismo e islam.
- **Fuentes reforzadas:** Oxford Scholarship Online, «Historical Memories in the Patriarchal Narratives — Ronald Hendel» (https://academic.oup.com/book/10720/chapter/158790336); Oxford Scholarship Online, «Remembering Abraham — Ronald Hendel» (https://academic.oup.com/book/10720/chapter/158789824); My Jewish Learning, «Abraham as a Historical Figure — P. Kyle McCarter» (https://www.myjewishlearning.com/article/abraham/).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-117 — San Pablo

- **Decisión integrada:** Pablo de Tarso fue un misionero y escritor judío del siglo I, y una de las figuras mejor documentadas del cristianismo primitivo. Sus cartas auténticas, escritas aproximadamente entre los años 50 y 60 d. C., son anteriores a los evangelios conservados. Siete cartas suelen aceptarse ampliamente como auténticas; otras atribuidas a Pablo son discutidas. Sus escritos muestran su trabajo entre comunidades judías y no judías y deben cotejarse críticamente con Hechos de los Apóstoles, una narración posterior y de autor distinto.
- **Hitos para tarjeta:** Romanos, 1–2 Corintios, Gálatas, Filipenses, 1 Tesalonicenses y Filemón son las siete cartas ampliamente aceptadas como auténticas. Sus cartas son algunos de los textos cristianos más antiguos conservados, anteriores a los evangelios canónicos. Hechos de los Apóstoles y las cartas paulinas ofrecen testimonios de naturaleza distinta y no siempre coinciden en detalles cronológicos.
- **Fuentes reforzadas:** Oxford Bibliographies, «Pauline Chronology — Mark Reasoner» (https://academic.oup.com/reference/62341/reference-article-abstract/554103486); American Bible Society, «Letters of Paul: chronology and disputed authorship» (https://www.americanbible.org/engage/bible-resources/articles/letters-of-paul/); Oxford Bibliographies, «Paul — early Christian writings and chronology» (https://academic.oup.com/reference/62341/reference-article-abstract/554098508).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-118 — San Agustín

- **Decisión integrada:** Aurelius Augustinus, obispo de Hipona en el norte de África romana, fue filósofo y teólogo de la Antigüedad tardía. Sus Confesiones combinan memoria personal, interpretación bíblica y reflexión filosófica; La ciudad de Dios respondió a debates religiosos y políticos de su tiempo. Participó en controversias con maniqueos, donatistas y pelagianos, y sus ideas sobre gracia, pecado y autoridad tuvieron una influencia duradera. Debe situarse en las redes intelectuales africanas y mediterráneas de su época.
- **Hitos para tarjeta:** Fue obispo de Hipona y escribió Confesiones y La ciudad de Dios, dos obras influyentes de la Antigüedad tardía. Su trayectoria intelectual estuvo marcada por el maniqueísmo, el neoplatonismo y su conversión al cristianismo. Sus controversias con donatistas y pelagianos influyeron en debates posteriores sobre gracia, Iglesia y autoridad.
- **Fuentes reforzadas:** Stanford Encyclopedia of Philosophy, «Augustine of Hippo» (https://plato.stanford.edu/entries/augustine/); Stanford Encyclopedia of Philosophy, «Augustine of Hippo — works and editions» (https://plato.stanford.edu/entries/augustine/index.html); Encyclopaedia Britannica, «Saint Augustine: bishop and theologian» (https://www.britannica.com/biography/Saint-Augustine).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-119 — Tomás de Aquino

- **Decisión integrada:** Fraile dominico, filósofo y teólogo que desarrolló una síntesis escolástica de la filosofía aristotélica y la teología cristiana. Trabajó con textos y comentarios transmitidos por tradiciones griegas, árabes y judías, además de fuentes latinas y patrísticas. Escribió la Summa contra gentiles y la Summa theologiae, esta última inconclusa al detenerse su trabajo en 1273. Su trayectoria se conoce mediante sus obras y testimonios posteriores, cuyas anécdotas hagiográficas requieren cautela.
- **Hitos para tarjeta:** La Summa theologiae fue escrita entre aproximadamente 1267 y 1273 y quedó inconclusa tras la tercera parte. Sus comentarios y síntesis filosóficas se apoyaron en traducciones y debates intelectuales de autores griegos, árabes y judíos. Murió en la abadía de Fossanova el 7 de marzo de 1274.
- **Fuentes reforzadas:** Stanford Encyclopedia of Philosophy, «Thomas Aquinas — life and works» (https://plato.stanford.edu/entries/aquinas/); Oxford Scholarship Online, «Chronological List of Aquinas’s Writings» (https://academic.oup.com/edited-volume/28242/chapter/213362059); Internet Encyclopedia of Philosophy, «Thomas Aquinas — biography and works» (https://iep.utm.edu/thomas-aquinas/).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-120 — Martín Lutero

- **Decisión integrada:** Teólogo y fraile agustino alemán cuya crítica a las indulgencias y reflexión sobre la justificación contribuyeron al inicio de la Reforma protestante. Las 95 tesis de 1517 fueron concebidas como invitación a una disputa académica; el relato del gesto dramático de clavarlas personalmente en la puerta de la iglesia se consolidó en la memoria posterior y es debatido. La Reforma fue un proceso colectivo y transnacional. Su legado incluye escritos antijudíos virulentos, especialmente los publicados en 1543, que deben mencionarse críticamente.
- **Hitos para tarjeta:** Las 95 tesis de 1517 cuestionaron la predicación y práctica de las indulgencias y convocaron a debate teológico. La difusión de sus escritos dependió de imprentas, aliados políticos y movimientos religiosos más amplios. En 1543 publicó escritos antijudíos que promovían medidas violentas contra comunidades judías; forman parte central de su legado problemático.
- **Fuentes reforzadas:** Library of Congress, «Martin Luther as Priest, Heretic and Outlaw: Luther the Priest» (https://guides.loc.gov/martin-luther-priest-heretic-outlaw/luther-the-priest); English Historical Review / Oxford Academic, «Luther’s Ninety-Five Theses and the Origins of the Reformation Narrative» (https://doi.org/10.1093/ehr/cex224); Theology Today, «Martin Luther and the Jews: Context and Content» (https://journals.sagepub.com/doi/10.1177/0040573617721911).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-121 — Juan Calvino

- **Decisión integrada:** Teólogo y reformador francés cuya Institución de la religión cristiana se convirtió en una exposición influyente de la teología reformada. Desarrolló gran parte de su labor en Ginebra, donde participó en la organización de la iglesia y en debates con las autoridades civiles. La disciplina eclesiástica, las Ordenanzas de 1541 y el caso de Miguel Servet en 1553 muestran las tensiones entre autoridad religiosa y gobierno urbano. Calvino tuvo participación en la controversia y defendió el castigo de la herejía, aunque no fue juez civil único ni dictó por sí solo la sentencia.
- **Hitos para tarjeta:** La primera edición de la Institución de la religión cristiana apareció en 1536 y fue ampliada en ediciones posteriores. Las Ordenanzas Eclesiásticas de 1541 organizaron la vida de la iglesia ginebrina en interacción con los consejos civiles. Miguel Servet fue ejecutado en Ginebra en 1553 tras un proceso civil; Calvino intervino en la controversia y defendió su condena.
- **Fuentes reforzadas:** Cambridge University Press, «Geneva and Calvin, 1541–64» (https://www.cambridge.org/core/books/abs/christian-polity-of-john-calvin/geneva-and-calvin-154164/93EAAFA927ACD005162D2329186262B2); Verbum et Ecclesia, «The question of Calvin’s involvement in the trial of Servetus» (https://verbumetecclesia.org.za/index.php/ve/article/view/1216); Universidade de São Paulo, «Study of Geneva’s Ecclesiastical Ordinances and Consistory» (https://revistas.usp.br/revhistoria/en/article/view/214575).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-122 — Guru Nanak

- **Decisión integrada:** Guru Nanak fue maestro espiritual, poeta y figura fundacional del sijismo, reconocido como el primero de los diez Gurús humanos en la tradición sij. Sus himnos, incorporados al Guru Granth Sahib, enseñan la devoción a un Dios único, la igualdad, el servicio y la vida honesta. Las janamsakhis narran episodios de su vida y viajes, pero son relatos devocionales redactados posteriormente y no deben tratarse como registros contemporáneos. Los primeros manuscritos de sus composiciones forman parte de una historia textual compleja.
- **Hitos para tarjeta:** Sus composiciones poéticas forman parte del Guru Granth Sahib, escritura sagrada sij. La tradición vincula su comunidad con Kartarpur, donde se desarrolló una temprana forma de vida comunitaria sij. Los primeros manuscritos y pothis permiten estudiar la transmisión de sus himnos antes de la compilación del Adi Granth.
- **Fuentes reforzadas:** Oxford Scholarship Online, «A Survey of Early Manuscripts — Pashaura Singh» (https://academic.oup.com/book/10787/chapter-abstract/158919311); Oxford Academic, «Guru Nanak and his first successors — Eleanor Nesbitt» (https://doi.org/10.1093/actrade/9780198745570.003.0002); Stanford Encyclopedia of Philosophy, «Sikh Philosophy — Janamsakhi traditions» (https://plato.stanford.edu/entries/sikh-philosophy/).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-123 — Teresa de Ávila

- **Decisión integrada:** Religiosa carmelita, escritora y reformadora castellana que impulsó, junto con colaboradores, la reforma descalza del Carmelo y fundó conventos. Sus obras —entre ellas Libro de la vida, Camino de perfección y Las moradas— son centrales para la literatura mística en español. El Libro de la vida fue redactado a petición de sus confesores y revisado; su manuscrito fue retenido por la Inquisición hasta 1586. Su familia tenía ascendencia conversa, dato relevante para comprender el contexto social de la España del siglo XVI.
- **Hitos para tarjeta:** Fundó conventos reformados y participó en la reorganización de la rama descalza del Carmelo. Escribió Libro de la vida, Camino de perfección y Las moradas, obras centrales de la mística española. Fue canonizada en 1622 y declarada doctora de la Iglesia católica en 1970.
- **Fuentes reforzadas:** Oxford Bibliographies, «Teresa of Avila — Elizabeth T. Howe» (https://academic.oup.com/reference/62416/reference-article-abstract/555951626); Oxford Scholarship Online, «Teresa of Avila — Robert S. Miola» (https://academic.oup.com/book/48685/chapter-abstract/420805458); Yale University, «The Life of Saint Teresa of Avila: A Biography» (https://news.yale.edu/2019/07/01/life-saint-teresa-avila-biography).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-124 — Francisco de Asís

- **Decisión integrada:** Predicador de Asís y fundador del movimiento de los Hermanos Menores, asociado a la pobreza voluntaria, la fraternidad y el servicio. La regla franciscana definitiva recibió aprobación papal en 1223 y Francisco fue canonizado en 1228. En 1219 cruzó las líneas durante la Quinta Cruzada y se entrevistó con el sultán al-Malik al-Kamil en Egipto. El encuentro está atestiguado por fuentes cercanas, pero los detalles y su interpretación posterior como diálogo interreligioso moderno deben tratarse con cautela.
- **Hitos para tarjeta:** La Regla definitiva de los Hermanos Menores recibió aprobación papal en 1223. En 1219 se reunió con el sultán al-Malik al-Kamil durante el sitio cruzado de Damieta. Fue canonizado por Gregorio IX en 1228, dos años después de su muerte.
- **Fuentes reforzadas:** Cambridge University Press, «Francis and the encounter with the sultan (1219) — Steven J. McMichael» (https://www.cambridge.org/core/books/abs/cambridge-companion-to-francis-of-assisi/francis-and-the-encounter-with-the-sultan-1219/6BC5313CF40FF8620CD2F07432D90824); Cambridge University Press, «The Friar and the Sultan: Francis of Assisi’s Mission to Egypt — John Tolan» (https://www.cambridge.org/core/journals/european-review/article/abs/friar-and-the-sultan-francis-of-assisis-mission-to-egypt/9DDB3996FE485ECBBB10B61121706F40); Vatican City State, «Saint Francis of Assisi: chronology and canonization» (https://www.vaticanstate.va/en/component/content/article/4-october-saint-francis-of-assisi-patron-saint-of-italy.html).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-125 — Maimónides

- **Decisión integrada:** Moisés ben Maimón, conocido como Maimónides o Rambam, fue filósofo, jurista y médico judío nacido en Córdoba. Su Mishné Torá sistematizó la ley judía y su Guía de los perplejos, concluida hacia 1190, examinó la relación entre filosofía aristotélica y tradición religiosa. Tras la conquista almohade de Córdoba en 1148, su familia abandonó al-Ándalus y pasó por el norte de África antes de establecerse en Egipto. También escribió tratados médicos y ejerció como médico en El Cairo.
- **Hitos para tarjeta:** Nació en Córdoba en 1138 y murió en Fustat, Egipto, en 1204. La Mishné Torá es una extensa sistematización de la ley judía cuya recepción generó debates rabínicos. La Guía de los perplejos, terminada hacia 1190, dialoga con la filosofía aristotélica y la tradición judía.
- **Fuentes reforzadas:** Stanford Encyclopedia of Philosophy, «Maimonides — life, works and medical writings» (https://plato.stanford.edu/entries/maimonides/); Jewish Encyclopedia, «Moses Maimonides: biography and medical works» (https://www.jewishencyclopedia.com/articles/10320-moses-ben-maimon); National Library of Medicine, «Maimonides and medieval medicine» (https://www.nlm.nih.gov/exhibition/islamic_medical/islamic_07.html).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-126 — Patanjali

- **Decisión integrada:** Sabio tradicional asociado a los Yoga Sutras, texto que sistematiza una vía de disciplina mental, concentración y liberación. La datación de la obra y la identidad de su autor son debatidas; estudios filológicos han propuesto que el Pātañjalayogaśāstra, incluidos los sutras y su comentario, tomó forma hacia finales del siglo IV o alrededor del año 400 d. C. No hay base suficiente para identificar sin matices a este Patanjali con el gramático del Mahābhāṣya o con autores de obras médicas.
- **Hitos para tarjeta:** Los Yoga Sutras sistematizan conceptos y prácticas de una tradición de yoga anterior al texto. Una propuesta filológica sitúa la composición del Pātañjalayogaśāstra alrededor de 380–400 d. C. La identificación del autor de los Yoga Sutras con el gramático Patanjali no está demostrada.
- **Fuentes reforzadas:** Sahapedia / Philipp A. Maas, «The Pātañjalayogaśāstra alias the Yogasūtra and the Yogabhāṣya» (https://www.sahapedia.org/patanjalayogasastra-alias-yogasutra-and-yogabhasya); Internet Encyclopedia of Philosophy, «Yoga Sutras of Patanjali» (https://iep.utm.edu/yoga/); Journal of Indian Philosophy, «Ethical Causality and Rebirth in the Pātañjalayogaśāstra and Abhidharmakośabhāṣya» (https://doi.org/10.1007/s10781-024-09574-8).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

### HIS-127 — Nagarjuna

- **Decisión integrada:** Monje y filósofo budista indio, figura principal de la escuela Madhyamaka. Su obra más importante, la Mūlamadhyamakakārikā, desarrolla una filosofía de la vacuidad y del surgimiento dependiente, cuestionando que los fenómenos posean una esencia independiente. Se le atribuyen otros tratados con distintos grados de aceptación; la existencia de autores posteriores llamados Nāgārjuna y la atribución de textos a autoridades prestigiosas complican la delimitación de su corpus. Los datos biográficos seguros son escasos y su origen en el sur de India es probable, no definitivo.
- **Hitos para tarjeta:** La Mūlamadhyamakakārikā es la obra central asociada a Nāgārjuna y a la filosofía Madhyamaka. Su análisis de la vacuidad cuestiona la existencia inherente o independiente de los fenómenos; no equivale a afirmar que nada existe. La atribución de otros textos a Nāgārjuna debe evaluarse individualmente, pues no hay un corpus único aceptado sin reservas.
- **Fuentes reforzadas:** Stanford Encyclopedia of Philosophy, «Nāgārjuna — life and works (revised 2026)» (https://plato.stanford.edu/entries/nagarjuna/); Internet Encyclopedia of Philosophy, «Nagarjuna» (https://iep.utm.edu/nagarjun/); Stanford Encyclopedia of Philosophy Archive, «Nāgārjuna — works and attribution» (https://plato.stanford.edu/archives/fall2023/entries/nagarjuna/).
- **Estado:** integrado documentalmente; pendiente de aprobación editorial formal.

**Balance global de integración transversal tras este archivo:** 127/144 registros integrados (88,19 %), 17 pendientes de integración y 0/144 aprobados. La fase de examen individual permanece completada para 144/144; no debe confundirse con aprobación.


# Archivo 6 — Bloque final (HIS-128–HIS-144)

| Código | Personaje | Decisión de integración y cautela que permanece |
|---|---|---|
| HIS-128 | Cuauhtémoc | Se mantiene el nacimiento aproximado; se refuerza la ejecución en 1525 y la falta de identificación concluyente de los restos de Ichcateopan. La conquista se presenta como conflicto entre coalición hispano-indígena y Tenochtitlan. |
| HIS-129 | Nelson Mandela | Se precisa la diferencia entre elecciones del 27 de abril e investidura del 10 de mayo de 1994; se contextualizan MK, Rivonia y el carácter colectivo de la transición. |
| HIS-130 | Rey Arturo | Se conserva como legendario/semihistórico debatido; Geoffrey de Monmouth es fuente literaria medieval, no testigo de los siglos V–VI. |
| HIS-131 | Merlín | Se distingue la tradición galesa de Myrddin de la construcción literaria artúrica del siglo XII; no se le atribuye biografía histórica comprobada. |
| HIS-132 | Robin Hood | Se reemplazan referencias generales por Oxford Bibliographies y Cambridge; se conserva como figura de baladas medievales sin identidad civil demostrada. |
| HIS-133 | Beowulf | Se incorpora el catálogo de la British Library: el Nowell Codex se copió a fines del X o inicios del XI; no se confunde fecha del manuscrito con fecha de composición. |
| HIS-134 | Sigfrido | Se refuerza la distinción entre Sigfrido/Siegfried y Sigurd y las capas de las tradiciones germánica y nórdica. |
| HIS-135 | Gilgamesh | Se conserva c. 2700 a. C. solo como hipótesis; la Lista Real Sumeria combina mito, memoria política e información histórica. |
| HIS-136 | Mulan | Se distingue la referencia temprana atribuida a una compilación del siglo VI, hoy perdida, de la versión conservada en antología Song y de adaptaciones posteriores. |
| HIS-137 | Ragnar Lodbrok | Se retira FamilySearch como fuente inadecuada; se incorpora debate académico, incluida la posición que defiende una base histórica, sin convertirla en consenso. |
| HIS-138 | Ivar el Deshuesado | Se incorpora Oxford DNB; se separan las referencias a un caudillo del siglo IX de su genealogía sagaria y de las interpretaciones del sobrenombre. |
| HIS-139 | Väinämöinen | Se refuerza la diferencia entre poesía oral finesa/carelia y compilación editorial del Kalevala de 1835 y 1849. |
| HIS-140 | Roland | Se incorpora Einhard y bibliografía sobre Roncesvalles; se advierten variantes de transmisión del nombre Hruodland y la reelaboración épica posterior. |
| HIS-141 | Cúchulainn | Se amplían los testimonios CELT sobre los relatos del ciclo del Úlster; se mantiene como héroe literario sin fechas personales. |
| HIS-142 | William Tell | Se incorpora el registro del manuscrito White Book of Sarnen; la primera documentación escrita conocida de la leyenda es tardomedieval, no prueba de historicidad. |
| HIS-143 | Lady Triệu | Se retira la referencia sobre las hermanas Trưng. Se incorpora bibliografía histórica sobre Vietnam; 248 se mantiene como núcleo tradicional del levantamiento, mientras que la biografía individual y el año de nacimiento quedan sujetos a cautela. |
| HIS-144 | Fionn mac Cumhaill | Se incorpora el catálogo académico Early Fenian Corpus y bibliografía especializada; se trata como héroe literario de un corpus estratificado. |

## Hallazgos transversales y asuntos que pasan a aprobación editorial

1. El bloque contiene personajes históricos documentados, figuras con posible referente histórico y héroes literarios o míticos. La categoría compartida no debe borrar esos grados de evidencia.
2. La fecha de un manuscrito conservado no equivale a la fecha de composición de la obra ni a la época narrada.
3. Las fuentes tardías y la memoria nacional son valiosas para estudiar la recepción cultural, pero no sustituyen testimonios contemporáneos.
4. Ragnar Lodbrok y Lady Triệu requieren especial atención a las diferencias entre interpretaciones historiográficas y tradición posterior.
5. En Roland, la mención de Hruodland debe cotejarse con variantes manuscritas de la tradición carolingia.
6. Los tres hitos por ficha son síntesis para la tarjeta; el expediente interno conserva las reservas y bibliografía.
