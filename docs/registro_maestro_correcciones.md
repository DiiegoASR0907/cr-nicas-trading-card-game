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
| `exploradores_092_109.json` | HIS-092–HIS-109 | 18 | Pendiente |
| `lideres_espirituales_110_127.json` | HIS-110–HIS-127 | 18 | Pendiente |
| `bloque_final_128_144.json` | HIS-128–HIS-144 | 17 | Pendiente |
| **Total** | **HIS-001–HIS-144** | **144** | **91 integrados; 0 aprobados** |

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
