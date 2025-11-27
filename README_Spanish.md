# Wargames Dice Roller

Este es el repositorio público para la aplicación _Wargames Dice Roller_.

Esta es la versión en español del README. También disponemos de una versión en [inglés](README.md) y de una versión en [catalán](README_Catalan.md).

## Reportando errors y solicitando nuevas funcionalidades

¿Tienes alguna idea para futuros desarrollos? ¿Has encontrado algún bug que se le escapó a nuestro equipo de pruebas? Si tienes una cuenta de GitHub por favor no dudes en abrir una "Issue" con tu idea o el fallo encontrado.

Cuando reportes un error, por favor incluye tanta información relevante y no personal como sea posible, tal como el modelo de dispositivo, versión de iOS/Android y versión de la app (ésta se puede encontrar en la pestaña "Ajustes").

## Política de privacidad

Esta política de privacidad rige el uso de la aplicación de software _Wargames Dice Roller_ ("Aplicación") para dispositivos iOS y Android.

### ¿Qué información recolecta la Aplicación y para qué se usa? 

La Aplicación no recopila información de ningún tipo, ni del dispositivo o del uso que se le da.

### Cambios

Esta Política de privacidad puede ser actualizada de vez en cuando por cualquier motivo. Se informará de los cambios en nuestra Política de Privacidad al actualizarla en este sitio web. Se aconseja consultar esta Política de Privacidad de forma regular para consultar cualquier cambio, pues el uso continuado de la Aplicación lleva implícito la aceptación de cualquier cambio.

## Disponibilidad y compatibilidad

[Ver en la AppStore](https://apps.apple.com/app/wargames-dice-roller/id6448962936)

[Ver en la PlayStore](https://play.google.com/store/apps/details?id=com.prietomartinez.wargamesdiceroller)

Esta aplicación es actualmente compatible con **dispositivos iPhone usando iOS 17 o superior** y **dispositivos usando Android 9 o superior**, y se encuentra disponible en las siguientes regiones:
* Europa (todos los países)

## Histórico de versiones

### iOS

#### Versión 1.5.1

* Corregido un error que causaba que la descripción de una tirada no se actualizara al cambiar su tipo para una serie.

#### Versión 1.5

* Adaptación de la interficie de usuario a Liquid Glass UI.
* Optimizaciones de código y mejoras de rendimiento.
* Incremento de la versión mínima de iOS a 17.

#### Versión 1.4

* Nuevas funcionalidades:
    - Añadida funcionalidad para realizar secuencias de tiradas.
    - Rediseñada la pantalla "Histórico" para incluir "Serie de tiradas".
    - Alineada interficie de usuario con Android.

* Corrección de errores:
    - Correcciones menores y optimizaciones.

#### Versión 1.3

* Nuevas funcionalidades:
	- Añadida funcionalidad para guardar diversas configuraciones de tirada en los "Ajustes" para que sean cargadas en la pestaña "Tirar dados".
	- Añadida funcionalidad en los "Ajustes" para cambiar la configuración de tirada por defecte que se precarga en la pestaña "Tirar dados".
	- Añadido un menú para seleccionar la configuración de tirada a cargar en la pestaña "Tirar dados".

* Corrección de errores:
	- Corregido un error que causaba que la aplicación se cerrara al seleccionar un tipo de dado con un número de caras inferior al valor actual del umbral de éxito en la pantalla de ajustes de tirada.
	- Corregido un error que causaba que el valor del umbral de críticos no se actualizara al cambiar el tipo de dado seleccionado a un tipo con un número de caras inferior al valor actual.

#### Versión 1.2

* Implementadas guías de usuario en varias pantallas.

#### Versión 1.1.1

* Corrección de algunos errores en textos surgidos en la anterior actualización.

#### Versión 1.1

* Nuevas funcionalidades:
	- Añadida funcionalidad para sumar o restar un valor a una tirada de tipo "suma de dados" (entre 0 y 15).
	- Añadida funcionalidad para definir éxitos y críticos con comparaciones "mayor o igual", "igual" o "menor o igual" a un valor del dado. Compatible con juegos D20 tipo Infinity®.

* Corrección de errores:
	- Corregida la computación de éxitos y críticos: ahora los críticos son un caso especial de éxito, en lugar de un resultado independiente.
	- Corregidos algunos errores en las traducciones.
	- Corregido un error que causaba que el histórico no se ordenara correctamente.

#### Versión 1.0

Publicación inicial de la aplicación.

* Funcionalidades incluidas:
	- Funcionalidad de tirada de dados para realizar una única tirada con múltiples dados.
	- Funcionalidad para computar distintos resultados de una tiradda, incluyendo sumar dados, concatenar dígitos y contar éxitos/fracasos con umbrales.
	- Funcionalidad para añadir pasos tras la tirada inicial, como añadir o quitar dados, volver a tirar ciertos dados, o reemplazar resultados en ciertos dados.
	- Persistencia en disco para tiradas, ya sea para consultarlas en el histórico o bien para volver a realizar una tirada con los mismos parámetros.
	- Ajustes que permiten definir una tirada por defecto para pre-rellenar los parámetros de la tirada. Siempre pueden cambiarse antes de realizar la tirada en sí.

### Android

#### Versión 1.5

* Optimizaciones de código y mejoras de rendimiento.

#### Versión 1.4.1

* Corregido un error por el cual algunas Series de tirades no se borraban al limpiar el Histórico.

#### Versión 1.4

* Nuevas funcionalidades:
    - Añadida funcionalidad para realizar secuencias de tiradas.
    - Rediseñada la pantalla "Histórico" para incluir "Serie de tiradas".
    - Alineada interficie de usuario con iOS.

* Corrección de errores:
    - Correcciones menores y optimizaciones.

#### Versión 1.3

* Nuevas funcionalidades:
	- Añadida funcionalidad para guardar diversas configuraciones de tirada en los "Ajustes" para que sean cargadas en la pestaña "Tirar dados".
	- Añadida funcionalidad en los "Ajustes" para cambiar la configuración de tirada por defecte que se precarga en la pestaña "Tirar dados".
	- Añadido un menú para seleccionar la configuración de tirada a cargar en la pestaña "Tirar dados".

* Corrección de errores:
	- Corregido un error que causaba que la aplicación se cerrara al seleccionar un tipo de dado con un número de caras inferior al valor actual del umbral de éxito en la pantalla de ajustes de tirada.
	- Corregido un error que causaba que el valor del umbral de críticos no se actualizara al cambiar el tipo de dado seleccionado a un tipo con un número de caras inferior al valor actual.

#### Versión 1.2.1

* Corregido un error por el cual el control para incrementar o reducir los valores de éxito y crítico no aparecía para tiradas de tipo "Éxitos / fracasos".

#### Versión 1.2

* Implementada funcionalidad de deslizamiento para eliminar pasos en la secuencia post-tirada.
* Implementada funcionalidad para reordenar los pasos en la secuencia post-tirada.

#### Versión 1.1

* Implementadas guías de usuario en varias pantallas.
* Añadidas animaciones al interactuar con algunos elementos en pantalla para mejorar la experiencia de usuario.
* Arreglado un error por el cual las barras superior e inferior aparecían translúcidas. 

#### Versión 1.0

Publicación inicial de la aplicación. Equivalente a la versión 1.1.1 en iOS

* Funcionalidades incluidas:
	- Funcionalidad de tirada de dados para realizar una única tirada con múltiples dados.
	- Funcionalidad para computar distintos resultados de una tiradda, incluyendo sumar dados, concatenar dígitos y contar éxitos/fracasos con umbrales.
	- Funcionalidad para añadir pasos tras la tirada inicial, como añadir o quitar dados, volver a tirar ciertos dados, o reemplazar resultados en ciertos dados.
	- Persistencia en disco para tiradas, ya sea para consultarlas en el histórico o bien para volver a realizar una tirada con los mismos parámetros.
	- Ajustes que permiten definir una tirada por defecto para pre-rellenar los parámetros de la tirada. Siempre pueden cambiarse antes de realizar la tirada en sí.
	- Funcionalidad para sumar o restar un valor a una tirada de tipo "suma de dados" (entre 0 y 15).
	- Funcionalidad para definir éxitos y críticos con comparaciones "mayor o igual", "igual" o "menor o igual" a un valor del dado. Compatible con juegos D20 tipo Infinity®.
