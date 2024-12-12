# De la Lengua de Even
## Fonética
### Inventario Fonético
El inventario fonético de X cuenta con 26 sonidos, de los cuales doce son vocálicos, diferenciados entre largos y cortos, y catorce consonánticos:
  + Vocales: */a/, /e/, /i/, /y/, /o/, /u/*
  + Consonantes: */k/, /d/, /l/, /n/, /m/, /p/, /t/, /r/, /ɾ/, /s/, /ʃ/, /θ/, /ɸ/, /v/, /ʔ/, /ɦ/*
Las vocales cortas pueden *iotizarse*, esto es, pronunciar una */i/* extremadamente corta precediendo a la vocal, notado con una diéresis (*/ä/*). Estas vocales actúan igualmente como vocales cortas o semilargas.
NOTA: Debe destacarse que los grupos */ʃ/ /θ/*, */ɸ/ /v/*, y */ʔ/ /ɦ/* coexisten, pero se usan en diferentes registros, los primeros en el X más clásico y refinado y los segundos en el más popular.

### Fonotácticas
Se permiten los siguientes grupos cónsonanticos y diptongos:
  + Grupos consonánticos dobles: geminadas (*/kk/, /ll/, /nn/, /mm/, /ss/*), */lt/, /nt/, /rt/* (rara vez), cualquiera seguida de */ʔ/* o */ɦ/*, */mn/*, */nm/* (rara vez)
  + Diptongos: (siempre son de **vocales cortas** y decrecientes) */ae/, /ea/, /ei/, /ai/, /eo/, /eu/*, así como las formas *iotizadas* */aë/, /eä/, /eö/*.

Las sílabas podrán ser formadas en su núcleo por cualquier vocal o diptongo.

El ataque silábico admite cualquier consonante excepto los grupos */ll/, /kk/, /lt/, /rt/* o los que se compongan con */ʔ/* o */ɦ/*. Al inicio de palabra se restringe además */p/* y cualquier grupo. Puede prescindirse de él.

La coda silábica admite cualquier consonante o grupo y puede omitirse. Al final de palabra quedan restringidos los grupos.

En resumen la fonotáctica de la lengua de Even para una **raíz** se condensa (más o menos) en esta *expresión regular*:

```regex
^[kdlnmtrɾsʃθɸv]?(?:[aäeëioöuüyÿ]|ae|aë|ea|eä|ei|ai|eo|eö|eu)(?:[kdlnmptrɾsʃθɸvʔɦ]|kk|ll|nn|mm|ss|lt|nt|rt|mn|nm|[kdlnmptrɾsʃθɸv]ʔ|[kdlnmptrɾsʃθɸv]ɦ)?(?:(?:[kdlnmptrɾsʃθɸv]|nn|mm|ss|nt|mn|nm)?(?:[aäeëioöuüyÿ]|ae|aë|ea|eä|ei|ai|eo|eö|eu)(?:[kdlnmptrɾsʃθɸvʔɦ]|kk|ll|nn|mm|ss|lt|nt|rt|mn|nm|[kdlnmptrɾsʃθɸv]ʔ|[kdlnmptrɾsʃθɸv]ɦ)?)*(?:[kdlnmptrɾsʃθɸv]|nn|mm|ss|nt|mn|nm)?(?:[aäeëioöuüyÿ]|ae|aë|ea|eä|ei|ai|eo|eö|eu)?[kdlnmptrɾsʃθɸvʔɦ]?$
```

NOTA: Las fonotácticas solo afectan a las raíces.

#### Cambios fonéticos

## Morfología

### El Sustantivo
En X las raíces son invariables e independientes

#### Género
X carece de género, pero como manera de distinguir entre *identidades personales* varios títulos o posposiciones se pueden agregar al conjunto del sustantivo

#### Número
X posee tres números: el singular, el dual, y el plural.
  + El singular se forma añadiendo un sufijo vacío
  + El dual añade "ei" a la raíz
  + El plural se forma según la declinación

#### Caso
X cuenta con nueve casos divididos en siete declinaciones:
  + Nominativo
  + Acusativo
  + Genitivo
  + Locativo
  + Ablativo
  + Alativo
  + Dativo
  + Vocativo
  + Etéreo
La tabla de declinación es la que sigue:

|                 | I    | II   | III  | IV   | V      | VI      | VII     |
|-----------------|------|------|------|------|--------|---------|---------|
| Nominativo (pl) | s    | i    | y    | äs   | ës     | tenitel | alt     |
| Acusativo       | kīa  | ān   | īm   | ë    | tāri   | enel    | lariel  |
| Genitivo        | ae   | ī    | nūs  | eä   | kaeri  | nōlen   | dariel  |
| Locativo        | kīe  | tis  | üm   | ën   | estis  | vāl     | edhel   |
| Ablativo        |      |      |      |      |        |         |         |
| Alativo         | kīes | tish | ümus | ëris | estish | vālish  | edheles |
| Dativo          |      |      |      |      |        |         |         |
| Vocativo        |      |      |      |      |        |         |         |
| Etéreo          |      |      |      |      |        |         |         |

### El Verbo
Los verbos en X se agrupan en siete conjugaciones, y pueden indicar tiempo, modo y persona. Existen ciertas partículas que modifican levemente el significado de la oración al completo y se colocan dentro del verbo. El aspecto lo determina una preposición, el modificador de aspecto.

Por lo general, los verbos se construyen añadiendo al infinitivo de presente activo (la única forma no personal que existe) un *término verbal* (separado en la forma romanizada por un apóstrofe)

El término verbal se construye de la siguiente manera (aunque literariamente hay autores que juegan con él):
  + Partículas intraverbales.
  + Persona.
  + Modo.
  + Tiempo (según la conjugación)

#### Aspecto
El aspecto se indica mediante una preposición, y existen cuatro:
  + Imperfecto: sin preposición.
  + Perfecto: *ār*.
  + Contínuo: *nō*.
  + Etéreo auxiliar: *nai*, suele marcar siempre al subjuntivo, al tiempo etéreo y ha derivado en un recurso literario.

####  Tiempo
Existen cuatro tiempos:
  + *Caet*, el pasado.
  + *Caen*, el presente.
  + *Caep*, el futuro.
  + *Cael*, el tiempo **Eterno**, que indica una acción eterna, sin principio ni final.

#### Modo
Existen cinco modos:
  + Indicativo: no se indica.
  + Subjuntivo: *nai* (+ *-d-*).
  + Imperativo: *-r-*.
  + Condicional: *-s-*.
  + Etéreo (un modo especial surgido de la tradición poética y utilizado para contar historias): *nai* (a veces *lai*) (+ *-dārel-*).

#### Persona
Los verbos pueden hacer referencia a cuatro personas:
  + *A*, la primera.
  + *E*, la segunda.
  + *I*, la tercera.
  + *y*, la tercera en femenino (solo en algunos mundos, donde existen varios géneros), y reverencial.

#### Conjugación
En X existen siete conjugaciones diferentes que se suelen usar para distintos propósitos:
  + I: es una conjugación sencilla, se usa en historiografía y ciencia sobre todo.
  + II: sus usos son sumamente parecidos a los de I, pero es la más usada coloquialmente.
  + III: es una conjugación un poco más elaborada, que se usa en contextos de formalidad media (cuando alguien no conoce al interlocutor, por ejemplo).
  + IV: es una conjugación literaria sobre todo, aunque se puede usar en un contexto formal y distinguido.
  + V: es la conjugación poética por excelencia.
  + VI: es una conjugación poco usada fuera del ámbito familiar.
  + VII: es la conjugación más refinada y aristocrática, y tiene varias variantes. La mayor complicación de las vocales implica mayor refinamiento.

|      | I  | II | III | IV  | V     | VI | VII    |
|------|----|----|-----|-----|-------|----|--------|
| Caet | et | të | tēm | tae | talae | tī | tēriel |
| Caen | en | në | nēm | nae | nalae | nī | nēriel |
| Caep | ep | pë | pēm | pae | palae | pī | pēriel |
| Cael | el | lë | lēm | lae | lalae | lī | lēriel |