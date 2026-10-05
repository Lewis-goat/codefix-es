---
title: Breville Dual Boiler 00–12: los códigos de dos dígitos
description: La Breville Dual Boiler BES920 guarda códigos 00–12 en un menú oculto: qué significa cada familia, vapor contra café y cómo arreglarlos.
---

En la mayoría de las cafeteras de espresso de Breville las averías se anuncian en la pantalla de siempre: la Barista Touch muestra códigos ER, la Oracle literalmente "Error" y la Oracle Jet números E. La **Dual Boiler BES920** rompe el esquema. Su tabla de fallos es un conjunto llano de códigos de dos dígitos, **del 00 al 12**, y no vive en la pantalla cotidiana sino en un menú de autotest oculto. Viendo el panel frontal durante un día normal no los verás: hay que conocer la combinación de botones.

La numeración merece un minuto de atención, porque es una tabla muy ordenada: el bloque en el que cae un código dice de qué tipo de fallo se trata, y dentro de cada bloque el código señala la pieza que se queja.

## Cómo leer el registro de errores

El registro se abre desde el menú de autotest:

1. Apaga la máquina desde el interruptor de pared.
2. Mantén pulsados **EXIT** y **MANUAL** mientras reconectas la corriente; aparecerá el menú de autotest.
3. Pulsa **MENU** hasta llegar al punto 3, el registro de errores. El punto 4 muestra el estado del nivel de las calderas, reportado como LLL (bajo) o HHH (alto).
4. Dentro del registro, **MENU** avanza por los códigos 00 a 12, cada uno con su contador almacenado.
5. En "ErSt", mantén **MANUAL** hasta que pite para borrar los códigos guardados; el contador de cafés no se reinicia.

El contador pesa tanto como el propio código. Un fallo registrado una sola vez hace un año es historia; un fallo cuyo contador sube semana a semana es un problema vivo creciendo en silencio.

## Qué cubre la familia 00

Los códigos **00 a 05** forman el bloque de sensores de temperatura, ordenado en tres parejas. En cada pareja, el número bajo indica que la sonda **no se detecta** —la placa la lee como circuito abierto— y el número alto que responde como **cortocircuito**:

- **00 y 01** — sonda de temperatura de la caldera de vapor: primero no detectada, luego en cortocircuito.
- **02 y 03** — sonda de temperatura de la caldera de café: no detectada y en cortocircuito.
- **04 y 05** — sonda del calentador del grupo de preparación: no detectada y en cortocircuito.

La BES920 monta doble caldera de acero inoxidable más grupo calentado, de modo que esas tres sondas cubren sus tres zonas calientes. La página del [código 00](https://es.codefixcoffee.com/breville/dual-boiler-bes920/00/) trata la sonda de la caldera de vapor, y su consejo práctico se traslada tal cual a las otras cinco: vuelve a encajar e inspecciona el conector de la sonda antes de comprar piezas, y busca humedad, porque el agua que puentea un conector puede leerse como circuito abierto o como cortocircuito según cómo quede posada. Las sondas NTC originales cuestan entre 25 y 90 € según cuál de las tres sea; los kits de juntas tóricas, de 10 a 20 €, y muchas veces son ellos los verdaderos culpables.

## Lado del vapor contra lado del café

El resto de la tabla se reparte siguiendo la misma frontera de hardware que marcan las parejas de sondas:

- **Caldera de vapor:** 06 (problema de bomba durante el arranque), 07 (fallo de nivel de agua o de bomba) y 11 (sobrecalentamiento detectado).
- **Caldera de café — el lado de la preparación:** 08 (problema de bomba o de caudal), 09 (fallo de nivel de agua) y 10 (sobrecalentamiento detectado).
- **Grupo de preparación:** 12 (sobrecalentamiento detectado).

### Los códigos que viajan en compañía

Estos fallos están entrelazados, y por eso leer el registro completo gana a leer un código suelto. El código 08 significa que la bomba funcionó y el caudalímetro no vio pasar nada — lo habitual es cal adherida a la hélice del caudalímetro, o una bomba pequeña que zumba sin mover agua, y en ambos escenarios el desescalado es el primer movimiento. El código 11, temperatura excesiva en la caldera de vapor, suele ser la consecuencia de una caldera que no se rellena — comprueba si 07 u 08 también acumulan registros — porque la resistencia calefactora sigue calentando con poco agua; la otra causa es una sonda que pierde por su retén. Antes de pedir repuesto alguno, mira el punto 4 del menú de autotest: un estado de nivel que contradiga lo que oyes cuando la máquina se llena te dice de qué lado está realmente el problema.

El código 12, sobrecalentamiento del grupo, es el extremo raro de la tabla y el que más exige vigilar la recurrencia: un sobrecalefamiento que vuelve una y otra vez apunta a la placa de potencia dejando retenido un calentador encendido, no a una deriva de la sonda. La página del [código 12](https://es.codefixcoffee.com/breville/dual-boiler-bes920/12/) lo desarrolla.

### En España esta máquina se vende como Sage

En Europa, y en España en concreto, estas cafeteras no llegan con la marca Breville sino como Sage: la Dual Boiler se comercializa con ese logotipo y con manuales de [Sage Appliances](https://www.sageappliances.co.uk). La mecánica, los códigos del 00 al 12 y el menú de autotest son idénticos a los de la BES920. Al pedir repuestos —sondas NTC, kits de juntas tóricas—, las referencias de la BES920 cruzan sin problema entre ambas marcas.

## Cuánto cuestan las piezas

- Producto descalcificante para los códigos de caudal y nivel: unos 10 €, y resuelve una parte nada despreciable de ellos.
- Bomba de llenado: de 30 a 60 €.
- Sonda de la caldera de vapor con kit de juntas: unos 85 €; el kit de juntas tóricas por separado, de 10 a 20 €.
- Fusible térmico: de 10 a 20 € — pero averigua primero por qué saltó.
- Triac o placa de potencia: de 80 a 150 €.

Los presupuestos de servicio oficial fuera de garantía por fallos internos suelen rondar los 300 a 500 € o más, así que una bomba o una sonda compensan repararlas uno mismo; una placa en una máquina veterana merece pedir presupuesto antes. Agua y corriente de red comparten la parte alta de la caldera: desenchufa antes de tocar cualquier sonda.

Para conocer cómo redactan sus códigos las demás máquinas de la gama, consulta la [sección Breville](https://es.codefixcoffee.com/breville/) — las de la familia ER comparten ideas de diagnóstico, pero no numeración.
