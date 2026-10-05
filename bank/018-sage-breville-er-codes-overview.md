---
title: Códigos ER de Sage/Breville: leer la tabla de servicio oculta
description: Códigos ER de Sage y Breville, procedentes de una tabla de servicio nunca publicada. Cómo se organizan ER01-ER18 y la numeración del Oracle.
---

Cuando una cafetera Breville se detiene en seco y enseña un ER05 en el panel, el manual no dirá qué significa. No es un descuido: los códigos de error de Breville proceden de las tablas de servicio internas que la compañía usa para sus reparaciones y no publica para los propietarios. El mismo hardware se vende en el Reino Unido bajo la marca **Sage** — máquinas idénticas, solo cambia la insignia — de modo que un código ER en una Sage Barista Touch significa exactamente lo que significa en una Breville. Nuestra [sección de Breville y Sage](https://es.codefixcoffee.com/breville/) cubre la gama actual; este artículo explica cómo está ordenada la numeración, para que incluso un código que nunca habías visto te diga algo útil.

## Por qué Breville no los publica

El manual de usuario se ocupa de la limpieza y del desescalado, no del diagnóstico. Las tablas completas viven dentro del modo de servicio de cada máquina: pantallas protegidas por contraseña y pensadas para técnicos, con contadores de errores almacenados y lecturas de sensores en directo. Por ser una herramienta de taller y no una función de cara al cliente, Breville nunca las ha publicado en un documento oficial, y la mayoría de los propietarios solo ve el código único que provocó la parada. El contraste no puede ser mayor: Miele imprime el significado de sus códigos F en las propias instrucciones, y por eso las [páginas de códigos de Miele](https://es.codefixcoffee.com/miele/) pueden citar el manual al pie de la letra.

## La tabla de la Barista Touch: de ER01 a ER18

La Barista Touch (BES880) y la Barista Touch Impress (BES881), que comparten familia de placa de control y tabla, usan un esquema de 18 entradas. Una vez vista la estructura, se lee sola: los códigos de sensor llegan en **grupos de cuatro**, uno por sensor, recorriendo circuito abierto en el arranque, circuito abierto en operación, cortocircuito en el arranque y cortocircuito en operación.

- **ER01 a ER04** — el sensor de temperatura del calentador ThermoJet en sus cuatro variantes abierto/corto; [ER01](https://es.codefixcoffee.com/breville/barista-touch-bes880/er01/) es la entrada de circuito abierto en el arranque.
- **ER05 a ER08** — el sensor de temperatura de la jarra de leche, la pequeña sonda de la zona de la bandeja de goteo que lee la jarra mientras la lanza texturiza la leche. ER05, el circuito abierto de arranque, es el código más notificado de toda la Barista Touch, y las cuatro entradas comparten una misma solución.
- **ER09 a ER12** — el sensor de temperatura en línea (el del agua de preparación), con idéntico patrón de cuatro.
- **ER13 y ER14** — errores de recuento del caudalímetro, al arrancar y en operación: la bomba trabajó y la máquina no consiguió contar el agua que circulaba.
- **ER15** — fallo de comunicación entre módulos electrónicos internos; muchas veces es un cable plano que se soltó o un conector mojado, y no una placa muerta.
- **ER16 y ER17** — el molinillo: el motor se sobrecalentó y se apagó por protección, y después un motor que agotó su tiempo sin completar la tarea.
- **ER18** — protección E-fast, un fallo eléctrico o de seguridad como una fuga de corriente; es además el código capaz de saltar el diferencial del cuadro eléctrico de casa.

## La familia Oracle numera de otra forma

En la Oracle, la misma idea despliega una tabla más larga. La Oracle (BES980) y la Oracle Touch (BES990) comparten una lista de 32 entradas, aunque la BES980 las muestra como "Error 1" a "Error 32" y la BES990 les añade el prefijo ER. Las dieciséis primeras siguen la lógica de cuartetos sobre cuatro sensores — caldera de vapor del 1 al 4, caldera de café del 5 al 8 (con el [Error 8](https://es.codefixcoffee.com/breville/oracle-bes980/error-8/) como cortocircuito del sensor en operación), grupo de preparación calentado del 9 al 12 y lanza de vapor del 13 al 16. El resto cubre calderas que no calientan (17 a 19), nivel y llenado de la caldera de vapor (20 y 21), problemas de caudalímetro (22 y 23), sondas de nivel y sobrecalentamiento (24 a 27), un fallo de comunicación de placa en el 28, el molinillo en el 29 y el 30, el motor de prensado en el 31 y una fuga o fallo de relleno de la caldera de vapor en el 32.

Dos tablas menores completan la familia. La Oracle Jet (BES985) usa una lista propia más corta, de E1 a E19, y la Dual Boiler (BES920) guarda códigos de dos dígitos, del 00 al 12, en un menú de autocomprobación en lugar del display normal, así que una Dual Boiler puede acumular durante semanas un fallo que jamás viste en pantalla.

## Cómo leer tú mismo el registro de errores oculto

Como las tablas son datos de servicio, la forma de consultar el historial de tu máquina pasa por esas mismas pantallas. Las rutas tienen sabor a taller, pero los reparadores las documentan bien:

- **Barista Touch y Oracle Touch** — apaga desde el enchufe de pared, mantén pulsado el botón Power frontal mientras devuelves la corriente, suelta al aparecer el logotipo, teclea la contraseña de servicio 00000 y abre Error Counter para los fallos almacenados o Live Debug para temperaturas y niveles en directo.
- **Barista Touch Impress** — la misma secuencia de botones, pero la contraseña de servicio es 02015.
- **Oracle BES980** — con la máquina enchufada pero apagada, mantén a la vez 1 CUP, 2 CUP y POWER durante al menos un segundo; tras el pitido largo, pulsa el dial SELECT para abrir Error Storage y recorrer los errores del 1 al 32 con sus contadores.

Trátalas como pantallas de solo lectura: apunta lo almacenado, deja los ajustes quietos y borra el registro solo después de una reparación, para comprobar si el código regresa.

## Qué cuestan estas reparaciones

Frente a una tabla no publicada, la economía es de lo más previsible. Los conjuntos de sensor de temperatura se mueven entre unos 25 y 95 € según la sonda (las de la lanza de vapor y la jarra de leche son las caras), y los kits de juntas tóricas entre 10 y 20 €; un kit de reparación del sensor de leche ronda los 30 a 50 €, frente a los 80 a 95 € del conjunto original. Los presupuestos del fabricante fuera de garantía por fallos internos suelen caer entre 300 y 500 €, de manera que una solución a nivel de sensor en un taller independiente es casi siempre el mejor camino. En el Reino Unido, la cobertura con marca Sage de estas mismas tablas está en la [edición británica del sitio](https://es.codefixcoffee.com/uk/).

### Comprar una Sage o Breville desde España o Latinoamérica

En España estas máquinas se venden como Sage, con especificación europea de 220-240 V, mientras que en México o Estados Unidos el mismo hardware sale como Breville a 120 V y 60 Hz: antes de importar una unidad, comprueba la placa de características, porque un transformador para 1.500-2.000 W rara vez resulta práctico. Para desescalado, filtros y manuales de los modelos europeos, [el soporte oficial de Sage Appliances](https://www.sageappliances.co.uk) es la referencia. Y si vas a abrir la máquina para diagnosticar, [las guías de reparación de iFixit](https://www.ifixit.com) sirven de orientación antes de desmontar nada.
