## Tipus de llenguatges de programació

Un **llenguatge de programació** és un llenguatge que permet establir una
comunicació entre l’home i la màquina. El llenguatge de programació
identificarà el codi font, que el programador desenvoluparà per indicar a la
màquina, una vegada aquest codi s’hagi convertit en codi executable, quins
passos ha de donar.

Els diferents tipus de llenguatges són:
* Llenguatge de primera generació o llenguatge màquina.
* Llenguatges de segona generació o llenguatges d’assemblador.
* Llenguatges de tercera generació o llenguatges d’alt nivell.
* Llenguatges de quarta generació o llenguatges de propòsit específic.
* Llenguatges de cinquena generació.

El primer tipus de llenguatge que es va desenvolupar és l’anomenat
**llenguatge de primera generació o llenguatge màquina**. És l’únic
llenguatge que entén l’ordinador directament.
La seva estructura està totalment adaptada als circuits impresos dels ordinadors
o processadors electrònics i molt allunyada de la forma d’expressió i anàlisi dels
problemes propis dels humans (les instruccions s’expressen en codi binari).

El segon tipus de llenguatge de programació són els **llenguatges de segona
generació o llenguatges d’assemblador**. Es tracta del primer llenguatge de
programació que utilitza codis mnemotècnics per indicar a la màquina les
operacions que ha de dur a terme. Aquestes operacions, molt bàsiques, han
estat dissenyades a partir de la coneixença de l’estructura interna de la pròpia
màquina.
Cada instrucció en llenguatge d’assemblador correspon a una instrucció en llenguatge
màquina. Aquests tipus de llenguatges depenen totalment del processador
que utilitzi la màquina, per això es diu que estan orientats a les màquines.

## 1.3.1 Característiques dels llenguatges de primera i segona generació

Com a avantatges dels llenguatges de primera i segona generació es poden establir:

* Permeten escriure programes molt optimitzats que aprofiten al màxim el
maquinari (hardware) disponible.
* Permeten al programador especificar exactament quines instruccions vol
que s’executin.
Els inconvenients són els següents:
* Els programes escrits en llenguatges de baix nivell estan completament
lligats al maquinari on s’executaran i no es poden traslladar fàcilment a altres
sistemes amb un maquinari diferent.
* Cal conèixer a fons l’arquitectura del sistema i del processador per escriure
bons programes.
* No permeten expressar de forma directa conceptes habituals a nivell d’algorisme.
* Son difícils de codificar, documentar i mantenir

El següent grup de llenguatges es coneix com a **llenguatges de
tercera generació o llenguatges d’alt nivell**. Aquests llenguatges, més
evolucionats, utilitzen paraules i frases relativament fàcils d’entendre i
proporcionen també facilitats per expressar alteracions del flux de control
d’una forma bastant senzilla i intuïtiva.
Els llenguatges de tercera generació o d’alt nivell s’utilitzen quan es vol desenvolupar
aplicacions grans i complexes, on es prioritza el fet de facilitar i comprendre
com fer les coses (llenguatge humà) per sobre del rendiment del programari o del
seu ús de la memòria.

Com a conseqüència d’aquest allunyament de la màquina i acostament a les persones,
els programes escrits en llenguatges de programació de tercera generació
no poden ser interpretats directament per l’ordinador, sinó que és necessari dur
a terme prèviament la seva traducció a llenguatge màquina. Hi ha dos tipus de
traductors: els compiladors i els intèrprets.

**Compiladors**

Són programes que tradueixen el programa escrit amb un llenguatge d’alt nivell
al llenguatge màquina. El compilador detectarà els possibles errors del programa
font per aconseguir un programa executable depurat.

El procediment que haurà de seguir un programador és el següent:

* Crear el codi font.
* Crear el codi executable fent ús de compiladors i enllaçadors.
* El codi executable depèn de cada sistema operatiu. Per a cada sistema hi
ha un compilador, és a dir, si es vol executar el codi amb un altre sistema
operatiu s’ha de recompilar el codi font.
* El programa resultant s’executa directament des del sistema operatiu.

**Els intèrprets**

L’intèrpret és un programa que tradueix el codi d’alt nivell a codi de bytes, però, a
diferència del compilador, ho fa en temps d’execució. És a dir, no es fa un procés
previ de traducció de tot el programa font a codi de bytes, sinó que es va traduint
i executant instrucció per instrucció.

Algunes característiques dels llenguatges interpretats són:

* El codi interpretat no és executat directament pel sistema operatiu, sinó que
fa ús d’un intèrpret.
* Cada sistema té el seu propi intèrpret.



## 1.3.2 Característiques dels llenguatges de tercera, quarta i cinquena generació

Els llenguatges de tercera generació són aquells que són capaços de contenir
i executar, en una sola instrucció, l’equivalent a diverses instruccions d’un
llenguatge de segona generació.
Els avantatges dels llenguatges de tercera generació són:

* El codi dels programes és molt més senzill i comprensible.
* Són independents del maquinari (no hi fan cap referència). Per aquest motiu
és possible “portar” el programa entre diferents ordinadors / arquitectures
/ sistemes operatius (sempre que en el sistema de destinació existeixi un
compilador per a aquest llenguatge d’alt nivell).
* És més fàcil i ràpid escriure els programes i més fàcil mantenir-los.

Els inconvenients dels llenguatges de tercera generació són:

* La seva execució en un ordinador pot resultar més lenta que el mateix
programa escrit en llenguatge de baix nivell, tot i que això depèn molt de la
qualitat del compilador que faci la traducció.

Els llenguatges de **quarta generació o llenguatges de propòsit específic**.
Aporten un nivell molt alt d’abstracció en la programació, permetent
desenvolupar aplicacions sofisticades en un espai curt de temps, molt inferior
al necessari per als llenguatges de 3a generació.

Els **llenguatges de cinquena generació** són llenguatges específics per al
tractament de problemes relacionats amb la intel·ligència artificial i els
sistemes experts.
En lloc d’executar només un conjunt d’ordres, l’objectiu d’aquests sistemes és
“pensar” i anticipar les necessitats dels usuaris. Aquests sistemes es troben encara
en desenvolupament. Es tractaria del paradigma lògic.
