---
title: "Cuando la Nespresso culpa a la cápsula: sensor, luces y código 1301"
description: "Si su Nespresso rechaza las cápsulas, el fallo suele estar en el sensor, la ventana sucia o un desescalado sin terminar. Luces y código 1301."
---

Pocas averías de cafetera culpan tan rápido al usuario como una Nespresso Vertuo que se niega a aceptar una cápsula. El pod entra, la palanca baja y la máquina actúa como si no hubiera nada dentro — o parpadea y tira la toalla. La gama Vertuo (Next, Plus, Pop, Evoluo) se expresa casi por completo en patrones de luz, documentados en las [páginas de asistencia de Nespresso](https://www.nespresso.com/), mientras que los códigos numéricos de los modelos conectados provienen de las pantallas y de reportes de usuarios más que de una tabla oficial. Ambos lenguajes están cubiertos en la [sección Nespresso](https://es.codefixcoffee.com/nespresso/) de nuestro sitio; este artículo trata el caso en que la máquina señala a la cápsula y la cápsula es inocente.

## Cómo lee una cápsula la Vertuo

Las cápsulas Vertuo llevan un código de barras impreso alrededor del borde. La máquina lo lee a través de una pequeña ventana en la cabeza, después perfora el aluminio y hace girar la cápsula mientras empuja el agua a través de ella. Dos cosas tienen que salir bien:

- **El sensor debe leer el código de barras.** Salpicaduras de café y polvo en la ventana de la cápsula bastan para una lectura errónea.
- **La cápsula debe asentarse recta** para que el aluminio se perfore limpio y la cápsula gire sin bamboleo.

Si cualquiera de las dos falla, la máquina informa de un problema de cápsula sin aclarar de qué lado estuvo el fallo: ahí nace casi toda la confusión.

### Síntomas que apuntan a la máquina, no al pod

- La máquina se comporta como si no hubiera cápsula aunque haya una colocada y la cabeza cerrada.
- Rechaza **todas** las cápsulas: de estuches distintos, de stock reciente, cápsulas originales.
- Limpiar la ventana de la cápsula y el portacápsulas mejora el problema o lo elimina.
- En las máquinas conectadas aparece un código de la familia 1301, la rama del sensor de cápsula, detallada en nuestra [página de referencia de los códigos 1301–1305](https://es.codefixcoffee.com/nespresso/vertuo-machines/1301-1305/).

Si la avería acompaña a la máquina con todas las cápsulas de la casa, deje de comprar estuches nuevos y póngase a limpiar.

## Cuando el pod sí es el problema

Las cápsulas también fallan, y conviene descartarlas barato antes de tocar la máquina:

- Un borde abollado o aplastado — por el transporte, el almacenaje o un golpe — impide que la cápsula se asiente recta: se perfora mal y gotea en lugar de preparar.
- Aluminio rasgado o abombado en cápsulas viejas; absorben humedad poco a poco y se dilatan fuera de tolerancia.
- Una cápsula atascada en el portacápsulas desde un ciclo anterior que bloquea el asiento de la siguiente.

La prueba que zanja la cuestión: prepare una cápsula original nueva sacada de la mitad de un estuche recién abierto; si sale bien, las anteriores eran el problema. Y no fuerce nunca el cierre de la cabeza sobre una cápsula mal colocada.

## Parpadeos que apuntan a las cápsulas

Las Vertuo no tienen un parpadeo específico de cápsula defectuosa: el botón único y el anillo de luz codifican subsistemas, no piezas concretas. Los patrones recurrentes:

- **Parpadeos secuenciales o alternos justo tras el encendido** significan modo de calentamiento. Espere entre quince y veinticinco segundos; no es ninguna avería.
- **Naranja parpadeante en cualquier pauta** es la familia del desescalado: pendiente, en curso o atrasado. Un naranja que no termina nunca suele indicar un desescalado iniciado y no finalizado.
- **Rojo fijo o que se repite** es estado de fallo, típicamente sobrecalentamiento o un error interno. Desenchufe al menos diez minutos, deje enfriar la máquina y vuelva a intentarlo.

Cuente el color, si la luz es fija o parpadeante y los destellos por grupo antes de tocar nada: el [descodificador de luces parpadeantes de Vertuo](https://es.codefixcoffee.com/nespresso/vertuo-machines/blinking-lights/) asocia cada pauta con su subsistema. Y deje para el final el reinicio de fábrica de cinco pulsaciones, no para el principio: borra los recordatorios de desescalado y el emparejamiento sin corregir nada mecánico.

## El solape del 1301: el código que culpa al pod

En las Vertuo conectadas, los códigos de la familia 1300 son el punto donde el problema de cápsula y el del desescalado se cruzan. Los reportes de usuarios asocian el 1301 a dos estados distintos: una máquina atascada en el modo de desescalado — o atrasada en él — y un sensor que no lee la cápsula, con los códigos vecinos dentro de la misma familia. Así, un código con pinta de queja de cápsula puede ser en realidad una queja de desescalado que luce el mismo número. La secuencia oficial ataca las dos mitades a la vez:

1. Reinicio de fábrica: con el asa en posición desbloqueada, pulse el botón cinco veces en tres segundos; parpadeará en naranja cinco veces como confirmación.
2. Ejecute un ciclo de desescalado completo con descalcificador Nespresso y sin interrupciones: un desescalado cancelado es la vía clásica para quedar enganchado en ese modo.
3. Retire el portacápsulas y limpie la ventana de la cápsula y la cabeza de la máquina para que el sensor pueda leer el código de barras.
4. Vacíe el depósito de agua, rellénelo y pruebe de nuevo con una cápsula fresca.
5. Si el fallo persiste después de los pasos anteriores, contacte con el soporte de Nespresso en vez de insistir: la marca suele sustituir las Vertuo defectuosas en garantía antes que repararlas.

Dos precauciones: no desescale nunca con vinagre, porque daña el circuito y puede dejar sin efecto la asistencia, y en lo económico esta secuencia no suele costar nada más allá del descalcificador, entre 10 y 15 €.

### Comprar o traer una Vertuo en España o Latinoamérica

Antes de comprar o traer una Vertuo de otro país, compruebe el voltaje: España y la mayor parte de Sudamérica trabajan a 220–230 V, mientras que México opera a 127 V, así que una máquina importada puede necesitar un transformador. El surtido de cápsulas Vertuo también cambia según el país, y no todas las referencias del catálogo español se venden en los catálogos latinoamericanos. Registrar la máquina en la web local de Nespresso facilita además cualquier gestión en garantía.

## El contraste con una máquina de moler

Una Philips o Saeco que muele sus propios granos se bloquea a su manera: café molido compactado en el embudo tras el [Error 01](https://es.codefixcoffee.com/philips-saeco/espresso-machines/error-01/). En una máquina de cápsulas, en cambio, los fallos del recorrido del café se reducen casi siempre a los mismos tres sospechosos: la ventana del código de barras, la perforación o un desescalado sin terminar. Limpie la ventana, pruebe una cápsula que sepa que es buena, descodifique el anillo de luz antes de actuar, y la máquina dejará de culpar a las cápsulas.
