---
title: Breville/Sage Oracle: vapor y códigos ER, qué revisar primero
description: Vapor en la Oracle de Breville/Sage — qué significan sus códigos, la purga que conviene intentar primero y cuándo la cal es la culpable.
---

El circuito de vapor es la zona más castigada de una Breville Oracle: caldera de vapor de acero inoxidable, lanza de auto-texturizado, sondas de nivel y bomba de llenado, todo a temperatura a diario. También genera una parte enorme de los códigos de error de la máquina. La familia Oracle usa una tabla de servicio de 32 entradas que Breville no publica, y en el Reino Unido el mismo hardware luce la insignia **Sage**, con códigos idénticos. Antes de dar por muerta una pieza, haz las comprobaciones baratas: la mayoría de las paradas del lado del vapor son una boquilla obstruida, una purga que no se hizo o cal en una sonda.

## Dónde están los códigos de vapor en la tabla Oracle

La Oracle (BES980) y la Oracle Touch (BES990) comparten tabla; la BES980 enseña las entradas como "Error 1" a "Error 32" y la BES990 las antepone con ER. Las entradas relacionadas con el vapor se concentran en cinco puntos:

- **Error 1 a 4** — el sensor de temperatura de la caldera de vapor, rotando entre circuito abierto en el arranque, señal perdida en operación y cortocircuito en ambas situaciones. Una sonda, cuatro formas de avisar.
- **Error 13 a 16** — el mismo cuarteto para el sensor de temperatura de la propia lanza de vapor, la sonda que corta el auto-texturizado al alcanzar la temperatura correcta de la leche. Vive en el punto más húmedo de la máquina.
- **Error 18** — la caldera de vapor no calienta con normalidad.
- **Error 20 y 21** — nivel de agua de la caldera de vapor o problemas de la bomba de llenado, y una lectura de sonda de nivel que no cuadra con lo que la placa espera.
- **Error 26** — la caldera de vapor sobrecalentó por encima del objetivo; el **Error 32** es una fuga de la caldera de vapor o un fallo de relleno.

No todo lo que rodea la lanza pertenece al circuito de vapor: los códigos 5 a 8 son del sensor de la caldera de café, con el [Error 8](https://es.codefixcoffee.com/breville/oracle-bes980/error-8/) como entrada de cortocircuito en operación. Leer el registro almacenado ayuda a separar las familias — en la BES980, mantén 1 CUP, 2 CUP y POWER a la vez con la máquina apagada para abrir Error Storage y recorrer los 32 códigos con sus contadores.

## Qué revisar primero: la rutina de purga

Un vapor flojo o que escupe, o un código justo después de una bebida con leche, suelen apuntar a la boquilla y no a la caldera:

1. Desenchufa la máquina y deja que la lanza se enfríe.
2. Desenrosca la boquilla y déjala en remojo en agua caliente con un poco de descalcificador; limpia cada orificio con la aguja de la herramienta de limpieza.
3. Ejecuta la purga — unos diez segundos de vapor a la bandeja de goteo con la boquilla retirada, y luego otros tantos con ella puesta.
4. Purga la lanza después de cada sesión de leche desde ahora; la leche seca en la boquilla es el origen de la mayoría de estas paradas.

Si la máquina vigila la presión de vapor, como hace la Oracle Jet con su código E16, una boquilla incrustada puede disparar un código antes de que notes que el vapor perdió fuerza.

## Dureza, cal y las sondas de nivel

Donde el agua es dura, la cal escribe sus propios códigos. Las sondas de nivel de la caldera de vapor viven permanentemente en agua caliente, y una costra calcárea las aísla de modo que la placa lee "sin agua" aunque la caldera esté llena — esa es la ruta clásica al Error 20 o 21, y al fallo de relleno del Error 32. La cal también se acumula en el camino de la lanza y en la entrada de la bomba de llenado. Un desescalado completo, incluyendo el ciclo de la caldera de vapor, es el diagnóstico más barato que puedes ejecutar y borra por sí solo un número sorprendente de estos códigos.

La hermana de la gama lo confirma: la Dual Boiler guarda sus códigos 00 a 12 en un menú de autocomprobación, y el [código 00](https://es.codefixcoffee.com/breville/dual-boiler-bes920/00/) — sensor de la caldera de vapor no detectado — encabeza una tabla cuyas entradas de nivel y llenado se comportan exactamente igual bajo agua dura.

### Dureza del agua en España y Latinoamérica

En buena parte de España (litoral mediterráneo, sur y amplias zonas del interior) el agua de red supera con holgura los 10 ºdH de dureza, igual que en el norte de México: ahí conviene acortar el intervalo de desescalado que marca la propia máquina y valorar agua embotellada de mineralización débil para el depósito. El filtro de agua original reduce la formación de cal pero no elimina los ciclos de desescalado, solo los espacia. Para descalcificante y accesorios oficiales, [la web de Sage Appliances](https://www.sageappliances.co.uk) es la referencia para los modelos europeos.

## Cuándo desescalar y cuándo desmontar

Primero desescalar, después desmontar — pero conviene saber dónde deja de ayudar el desescalado:

- **Desescala primero** ante códigos de nivel, sonda y relleno (20, 21, 32), vapor flojo sin código y cualquier máquina con más de tres meses desde el último ciclo. Coste: un bote de descalcificador.
- **El desescalado no arregla** un código de sensor que reaparece al instante en una máquina recién desescalada y caliente — sea una entrada de caldera de vapor del 1 al 4 o el [Error 8](https://es.codefixcoffee.com/breville/oracle-bes980/error-8/) del lado del café. Un código que sobrevive al desescalado apunta a la sonda, su cable o un conector.
- **Para y revisa las juntas** si el Error 26 se repite: una junta tórica de la sonda de vapor con fuga deja que el vapor caliente el cable del sensor e imita una caldera desbocada. Unas juntas nuevas son baratas; una placa con un triac que no corta la resistencia calefactora, no.
- **Error 18** en una máquina que ya no calienta vapor en absoluto suele estar en la resistencia — fusible térmico, resistencia calefactora o placa — y no en la cal, así que trátalo como reparación y no como limpieza.

## Cuánto cuestan las piezas

Los conjuntos originales de sensor de temperatura van de unos 25 a 95 € según la sonda; los conjuntos de lanza de vapor, que incluyen su sensor, rondan los 60 a 95 €; un kit de sonda y juntas cuesta unos 85 € y una bomba de llenado de 30 a 60 €. Frente a eso, los presupuestos oficiales fuera de garantía por fallos internos suelen andar entre 300 y 500 €, de modo que un bote de descalcificador primero y una reparación a nivel de sensor después es casi siempre la mejor aritmética. Los lectores del Reino Unido encontrarán la cobertura con marca Sage de estas mismas tablas en la [edición británica del sitio](https://es.codefixcoffee.com/uk/).
