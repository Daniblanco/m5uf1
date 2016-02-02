##1.5.Característiques dels llenguatges més difosos

Els llenguatges de programació més difosos són aquells que més es fan servir
en cadascun dels diferents àmbits de la informàtica. En l’àmbit educatiu, per
exemple, es considera un llenguatge de programació molt difós aquell que es fa
servir a moltes universitats o centres educatius per a la docència de la iniciació a
la programació.

**1.5.1 Característiques de la programació estructurada**

La programació estructurada va ser desenvolupada pel neerlandès Edsger W.
Dijkstra i es basa en el denominat teorema de l’estructura. Per això utilitza
únicament tres estructures: seqüència, selecció i iteració, essent innecessari
l’ús de la instrucció o instruccions de transferència incondicional.

**Claredat**

Hi haurà d’haver prou informació al codi per tal que el programa pugui ser
entès i verificat: comentaris, noms de variables comprensibles i procediments
entenedors... Tot programa estructurat pot ser llegit des del principi a la fi sense
interrupcions en la seqüència normal de lectura.

**Disseny descendent**

El disseny descendent és una tècnica que es basa en el concepte de “divideix i
venceràs” per tal de resoldre un problema en l’àmbit de la programació. Es tracta
de la resolució del problema al llarg de diferents nivells d’abstracció partint d’un
nivell més abstracte i finalitzant en un nivell de detall.

**Programació modular**

La realització d’un programa sense seguir una tècnica de programació modular
produeix sovint un conjunt enorme de sentències l’execució de les quals és
complexa de seguir, i d’entendre, amb la qual cosa es fa gairebé impossible la
depuració d’errors i la introducció de millores. Fins i tot, es pot donar el cas
d’haver d’abandonar el codi preexistent perquè resulta més fàcil començar de nou.

**Tipus abstractes de dades (TAD)**

En programació, el *tipus de dades* d’una variable és el conjunt de valors que la
variable pot assumir. Per exemple, una variable de tipus booleà pot adoptar només
dos valors possibles:Vertader o fals. A més, hi ha un conjunt limitat però ben
definit d’operacions que tenen sentit sobre els valors d’un tipus de dades; així,
operacions típiques sobre el tipus booleà són AND o OR.

Els llenguatges de programació assumeixen un nombre determinat de tipus de
dades, que pot variar d’un llenguatge a un altre; així, en Pascal tenim els *enters*,
els *reals*, els *booleans*, els *caràcters*... Aquests tipus de dades són anomenats tipus
de dades bàsics en el context dels llenguatges de programació.

**1.5.2 Característiques de la programació orientada a objectes**

Un dels conceptes importants introduïts per la programació estructurada és l’abstracció
de funcionalitats a través de funcions i procediments. Aquesta abstracció
permet a un programador utilitzar una funció o procediment coneixent només què
fa, però desconeixent el detall de com ho fa.

L’**orientació a objectes** (en endavant, OO) és un paradigma de construcció
de programes basat en una abstracció del món real.

Un **objecte** és una combinació de dades (anomenades atributs) i mètodes
(funcions i procediments) que ens permeten interactuar amb ell. En OO,
doncs, els programes són conjunts d’objectes que interactuen entre ells a
través de missatges (crides a mètodes).

**Abstracció**

És el procés en el qual se separen les propietats més importants d’un objecte
de les que no ho són. És a dir, per mitjà de l’abstracció es defineixen les
característiques essencials d’un objecte del món real, els atributs i comportaments
que el defineixen com a tal, per després modelar-lo en un objecte de programari.
En el procés d’abstracció no ha de ser preocupant la implementació de cada
mètode o atribut, només cal definir-los.
En la tecnologia orientada a objectes l’eina principal per suportar l’abstracció és la
**classe**. Es pot definir una classe com una descripció genèrica d’un grup d’objectes
que comparteixen característiques comunes, les quals són especificades en els seus
atributs i comportaments.

**Encapsulació**

Permet als objectes triar quina informació és publicada i quina informació és
amagada a la resta dels objectes. Per això els objectes solen presentar els seus
mètodes com a interfícies públiques i els seus atributs com a dades privades o
protegides, essent inaccessibles des d’altres objectes.

**Modularitat**

Permet poder modificar les característiques de cada una de les classes que defineixen
un objecte, de forma independent de la resta de classes en l’aplicació. En altres
paraules, si una aplicació es pot dividir en mòduls separats, normalment classes,
i aquests mòduls es poden compilar i modificar sense afectar els altres, aleshores
aquesta aplicació ha estat implementada en un llenguatge de programació que
suporta la modularitat.

**Jerarquia**

Permet l’ordenació de les abstraccions. Les dues jerarquies més importants d’un
sistema complex són l’herència i l’agregació.
L’herència també es pot veure com una forma de compartir codi, de manera que
quan s’utilitza l’herència per definir una nova classe només s’ha d’afegir allò
que sigui diferent, és a dir, reaprofita els mètodes i variables, i especialitza el
comportament.
