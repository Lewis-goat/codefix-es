---
title: Cómo encontrar y verificar un código de avería de un electrodoméstico
description: Cómo rastrear cualquier código de avería: dónde esconden los fabricantes sus listas, cómo contrastar foros y documentación técnica.
---

El código del display es solo la mitad de la respuesta: confirma que la máquina ha detectado un fallo, pero rara vez dice qué recambio comprar. Un código es la descripción de un síntoma escrita por el programador de la placa de control, y la misma placa que detecta una avería también puede malinformarla. Antes de pedir cualquier pieza necesitas el significado para tu marca, tu tipo de aparato y tu modelo exactos, y además contrastado en más de una fuente.

## Las listas de los fabricantes existen, pero están enterradas

La primera sorpresa es la frecuencia con la que no hay lista oficial, o lo escondida que está:

- Hay marcas que no publican nada. Los lavavajillas GE muestran códigos C, H2O y 888, pero GE no mantiene una página oficial de códigos; el hueco lo rellenan los sitios de reparación. El 888 en un lavavajillas GE es un fallo de la placa de control, y eso no lo vas a aprender de GE.

- Hay marcas que parten la información en dos. Las De'Longhi suelen mostrar palabras como Alarma general, mientras que los modelos recientes registran además códigos numéricos (1101 o 1512) que normalmente solo ve el técnico; ambas capas están recogidas en la página de la [alarma general y los códigos numéricos de De'Longhi](https://es.codefixcoffee.com/delonghi/magnifica-dinamica/general-alarm-code-1101-1512/).

- Hay marcas que publican solo la parte amable: [Philips](https://philips.com) lista un conjunto reducido de códigos resolubles por el usuario para sus cafeteras y deriva el resto a soporte, aunque los códigos "de servicio" también tienen causas identificables.

- Cuando el manual sí incluye una tabla, suele estar al final, en el capítulo de solución de problemas, con una línea por código, sin nombres de componentes y sin pasos de reparación.

La información casi siempre existe; solo hay que mirar más allá de la guía de inicio rápido.

## Verificar un código como lo haría un técnico

### Apunta exactamente lo que muestra el display

Registra la cadena exacta, el tipo de aparato, el número de modelo completo de la placa de características y el momento en que aparece. Un solo dígito mal leído te manda al subsistema equivocado: el "SE" en una cocina o horno Samsung es un fallo de tecla atascada en la membrana del panel —lo explicamos en [SE de Samsung](https://es.codefixcoffee.com/samsung/range-wall-oven/se/)— y cadenas casi idénticas en otros tipos de aparato apuntan a otra parte.

Fíjate también en si el código salta al arrancar o en mitad del ciclo: los fallos de arranque los caza el autotest inicial, mientras que los de mitad de ciclo suelen involucrar lo que estaba activo —bomba, resistencia o válvula—. Anota qué lo hace desaparecer: los hornos Samsung, por ejemplo, mantienen el código en pantalla hasta que se corrige la causa o hasta que se corta la corriente tres minutos en el cuadro, y toda la colección de la marca está indexada en la [página de códigos de horno Samsung](https://es.codefixcoffee.com/samsung-oven-error-codes/).

### Busca primero el significado del fabricante

Consulta el capítulo de solución de problemas, el portal de servicio y recambios de la marca y los boletines técnicos en PDF de tu modelo antes de entrar en ningún foro. El significado oficial es la línea base; todo lo demás es comentario. El [soporte de Miele](https://miele.com), por poner un ejemplo, permite descargar manuales y documentación buscando por número de modelo.

### Manuales en español y máquinas importadas

En las webs de soporte puedes descargar el manual en español buscando el modelo completo que figura en la placa de características, casi siempre detrás o debajo del aparato. Si vives en Latinoamérica y tu máquina llegó importada de Europa, verifica también en esa placa la tensión de trabajo: la red es de 110–127 V en México o Colombia y de 220–230 V en Argentina, Chile o España, y una máquina conectada a la tensión equivocada funciona mal y puede disparar códigos engañosos. Comprobarlo es gratis y ahorra diagnósticos imposibles.

### Contrasta los foros con la documentación de servicio

En los hilos de foro aprendes qué se rompe de verdad: una tabla de servicio te dice que un código significa "avería del grupo de preparación", y un foro te cuenta que en tu modelo casi siempre es un puck de café atascado y un cuarto de hora de limpieza. Trata los hilos como evidencia, no como verdad absoluta:

- Dale peso a los mensajes que citan tu modelo exacto y describen una solución que seguía funcionando semanas después.

- Desconfía de cualquier hilo que recomiende la misma pieza para todos los códigos y todas las máquinas.

- Cuando un foro y un documento de servicio discrepan, el documento gana en significado y el foro en probabilidad.

## La trampa: el mismo código con distinto significado

Aquí fracasa la mayoría de los autodiagnósticos, porque los códigos no están estandarizados, ni entre marcas ni a veces dentro de una misma gama.

- El mismo número puede significar cosas sin relación. En una Jura, el [Error 2](https://es.codefixcoffee.com/jura/automatic-machines/error-2/) es un fallo del circuito de la sonda del termobloque de café o, simplemente, una máquina demasiado fría para calentar. En una Philips o Saeco, el Error 02 es una avería interna que se deriva directamente al servicio técnico. Mismo número, misma categoría, subsistemas y facturas distintas.

- Las palabras pueden esconder códigos: la "Alarma general" de De'Longhi tiene un gemelo numérico registrado para los técnicos, y resolverla bien exige conocer las dos capas.

- La categoría pesa tanto como la marca: una misma cadena de código significa una cosa en la cocina y otra distinta en el lavavajillas o la lavadora de la misma marca. Filtra primero por tipo de aparato y después por modelo.

Contrastar el significado con el síntoma es una buena prueba de cordura: un código de resistencia en una máquina que sigue calentando, o de desagüe en una que desagua bien, suele indicar que estás leyendo la entrada equivocada — o la de otro modelo.

## Lista de verificación en cinco pasos

1. Fotografía el display y anota el número de modelo completo de la placa de características.

2. Consigue el significado del fabricante en el manual o en la documentación de servicio.

3. Confírmalo con al menos dos hilos de foro que citen tu modelo y una solución duradera.

4. Contrasta el resultado en una referencia independiente: por ejemplo, el [Error 11 o 19 de Philips](https://es.codefixcoffee.com/philips-saeco/espresso-machines/error-11-or-19/) debe leerse igual allá donde lo consultes; si dos fuentes discrepan, fíate de la que cita documentación de servicio.

5. Reinicia la máquina una vez y decide: si el código vuelve de inmediato, trátalo como real y elige entre recambio barato, limpieza o técnico.

## Cuándo dejar de investigar

Cierra las pestañas cuando dos fuentes independientes coincidan en el significado y el síntoma encaje. Ninguna lectura adicional cambia un código que reaparece justo después de un reinicio: a partir de ahí la decisión es práctica, y se reduce a comparar el precio del recambio con la edad de la máquina.
