# Wargames Dice Roller

Aquest és el repositori públic de l'aplicació _Wargames Dice Roller_.

Aquesta és la versión en català del README. També disposem d'una versión en [anglès](README.md) i d'una versió en [castellà](README_Spanish.md).

## Reportar error i demanar noves funcionalitats

Tens alguna idea per a futurs desenvolupaments? Algun error lleig que se'ls hagi escapat al nostre equip de proves? Si disposes d'un compte de GitHub no dubtis en obrir una "Issue" amb la teva idea o amb l'error que has trobat!

Quan ens informis d'un error, si us plau inclou el màxim d'informació no personal que sigui rellevant per a reproduïr-lo, com ara el model de dispositiu, la versión de iOS i la versió de l'aplicació (aquesta es pot trobar a la pestanya "Ajustos").

## Política de Privacitat

Aquesta Política de Privacitat regeix l'ús del programari _Wargames Dice Roller_ (en endavant, l'"Aplicació") per a dispositius iOS i Android.

### Quina informació recull l'Aplicació i per a què es fa servir?

L'Aplicació no recull informació de cap tipus: ni del dispositiu ni de l'ús que se li en dona.

### Canvis

Aquesta Política de Privacitat pot veure's actualitzada de tant en tant per qualsevol motiu. Notificarem quelsevol canvi en aquesta Política de Privacitat mitjançant la pujada de la nova Política de Privacitat en aquest lloc web. Es recomana a tots els usuaris consultat aquesta Política de Privacitat regularment per consultat canvis, doncs l'ús continuat de l'Aplicació comporta l'acceptació implícita de tots els canvis.

## Disponibilitat i compatibilitat

[Vegeu-la en l'AppStore](https://apps.apple.com/app/wargames-dice-roller/id6448962936)

[Vegeu-la en la PlayStore](https://play.google.com/store/apps/details?id=com.prietomartinez.wargamesdiceroller)

Aquesta aplicació és actualment compatible amb **dispositius iPhone amb iOS 16 o superior** i **dispositius amb Android 9 o superior**, i es troba disponible en les regions següents:
* Europa (tots els països)

## Històric de versions

### iOS

#### Versió 1.3

* Noves funcionalitats:
	- Afegida funcionalitat per a guardar diverses configuracions de tirada als "Ajustos" per a ser carregades en la pestanya "Llençar daus".
	- Afegida funcionalitat als "Ajustos" per a canviar la configuració de tirada per defecte que es precarrega en la pestanya "Llençar daus".
	- Afegit un menú per a seleccionar la configuració de tirada a carregar en la pestanya "Llençar daus".

* Correccions d'errors:
	- Corregit un error que causava que l'aplicació es tanqués en seleccionar un tipus de daus amb un nombre de cares inferior al valor actual del llindar d'èxit en la pantalla d'ajustos de tirada.
	- Corregit un error que causava que el valor del llindar de crítics no fós actualitzat en canviar el tipus de dau seleccionat a un tipus amb un nombre de cares inferior que el valor actual.

#### Versió 1.2

* Implementades guies d'usuari en diverses pantalles.

#### Versió 1.1.1

* Correcció d'alguns errors en textos sorgits en l'anterior actualització.

#### Versió 1.1

* Noves funcionalitats:
	- Afegida funcionalitat per a sumar o restar un valor a una tirada de tipus "sumar daus" (entre 0 i 15).
	- Afegida funcionalitat per a definir èxits i crítics amb comparacions "major o igual", "igual" o "menor o igual" a un valor del dau. Compatible amb jocs D20 tipus Infinity®.

* Correccions d'errors:
	- Corregida la computació d'èxits i crítics: ara els crítics són casos especials d'èxits, enlloc de tirades independents.
	- Corregits alguns errors en les traduccions a castellà i anglès.
	- Corregit un error que causava que l'històric no quedés ordenat correctament.

#### Versió 1.0

Publicació inicial de l'aplicació.

* Funcionalitats incloses:
	- Funcionalitat per a realitzar una única tirada de múltiples daus.
	- Funcionalitat per a computar diferents resultats d'una tirada, incloent sumar daus, concatenar dígits i comptar èxits/fracassos amb llindars.
	- Funcionalitat per a afegir passos post-tirada inicial, com ara afegir o descartar daus, tornar a tirar daus o canviar resultats de daus concrets.
	- Persistència en disc per a tirada, ja sigui per a consultar-les en un hisòric o bé per a tornar a realitzar una tirada amb els mateixos paràmetres.
	- Ajustos que permeten definir una tirada per defecte per a pre-omplir els paràmetres de la tirada. Sempre es poden canviar abans de realitzar la tirada en sí.

### Android

#### Versió 1.2.1

* Arreglat un error pel qual el control per a incrementar o reduir els valors d'èxit i crític no apareixia per a tirades de tipus "Èxits / fracassos".

#### Versió 1.2

* Implementada funcionalitat de lliscament per a eliminar passos en la seqüència post-tirada.
* Implementada funcionalitat per a reordenar els passos en la seqüència post-tirada.

#### Versió 1.1

* Implementades guies d'usuari en diverses pantalles.
* Afegides animacions en interactuar amb alguns elements en pantalla per a millorar l'experiència d'usuari.
* Arreglat un error pel qual les barres superior i inferior apareixien translúcides.. 

#### Versió 1.0

Publicació inicial de l'aplicació, equivalent a la versió 1.1.1 en iOS.

* Funcionalitats incloses:
	- Funcionalitat per a realitzar una única tirada de múltiples daus.
	- Funcionalitat per a computar diferents resultats d'una tirada, incloent sumar daus, concatenar dígits i comptar èxits/fracassos amb llindars.
	- Funcionalitat per a afegir passos post-tirada inicial, com ara afegir o descartar daus, tornar a tirar daus o canviar resultats de daus concrets.
	- Persistència en disc per a tirada, ja sigui per a consultar-les en un hisòric o bé per a tornar a realitzar una tirada amb els mateixos paràmetres.
	- Ajustos que permeten definir una tirada per defecte per a pre-omplir els paràmetres de la tirada. Sempre es poden canviar abans de realitzar la tirada en sí.
	- Funcionalitat per a sumar o restar un valor a una tirada de tipus "sumar daus" (entre 0 i 15).
	- Funcionalitat per a definir èxits i crítics amb comparacions "major o igual", "igual" o "menor o igual" a un valor del dau. Compatible amb jocs D20 tipus Infinity®.