---
title: "Jura Error 6 y 7: la válvula de cerámica, explicada sin rodeos"
description: "Qué significan de verdad los errores 6 y 7 de Jura: la válvula de cerámica motorizada, la cal, el encoder de posición y por qué el 7 acaba en el taller."
---

Los códigos numerados de Jura tienen la virtud de ser concretos. Los errores 1 a 5 señalan los termobloques y sus sondas, el 8 al grupo de preparación y el 12 al molinillo. Los errores 6 y 7 señalan ambos al mismo componente: la válvula de cerámica electrónica, el disco motorizado que reparte el agua dentro de la máquina. La diferencia entre uno y otro viene a ser la que hay entre "haz un desescalado y observa" y "reserva banco de trabajo". Vamos al fondo del asunto.

## Qué hace la válvula de cerámica

La mayoría de las superautomáticas con muele reparten el agua entre café, agua caliente y vapor mediante electroválvulas sencillas. Las Jura de especificación alta —de la Z5 a la Z10, la serie X, de la J5 a la J9, la gama GIGA y las S y E más recientes— usan en su lugar una válvula de cerámica electrónica: un pequeño motor hace girar un disco de cerámica entre posiciones, y los canales de ese disco dirigen el agua hacia la salida de café, la boquilla de agua caliente o el circuito de vapor. Un sensor de posición (un encoder) informa en todo momento de dónde está el disco, así que la placa de control siempre sabe que el agua va donde debía ir.

Ese lazo de retroalimentación es la razón de que existan los errores 6 y 7: la placa ordena una posición, espera la confirmación del encoder y lanza un error cuando la confirmación no llega.

## Error 6: el disco no llegó a su posición

El [Error 6](https://es.codefixcoffee.com/jura/automatic-machines/error-6/) significa que la válvula de cerámica no opera correctamente: el disco no alcanzó la posición que la placa pidió. En la práctica hay tres causas, por orden de probabilidad: la cal ha endurecido el mecanismo y el motor no logra girarlo con libertad; la junta de la válvula pierde agua y esta ha mojado el motor y el encoder; o el motor o su sensor de posición han fallado directamente.

La causa más probable tiene arreglo gratuito, así que empieza por ahí.

1. Lanza primero un ciclo de desescalado completo. La cal es la causa número uno de un disco de cerámica agarrotado, y la solución cuesta una pastilla y una hora.
2. Reinicia y escucha. En el arranque la válvula recorre sus posiciones con un chasquido audible. Si completa el ciclo de inicio, has terminado.
3. Si el Error 6 persiste, hay que abrir la máquina: busca agua alrededor del cuerpo de la válvula. La humedad ahí delata una junta que pierde y contamina el accionamiento.
4. Limpiar o sustituir la válvula es la reparación. Motor y válvula se cambian normalmente como un único conjunto, no por separado.

Presupuesta entre 55 € y 110 € un conjunto de válvula de cerámica, o de 10 € a 18 € si solo hace falta el kit de juntas.

## Error 7: el hermano mayor

El [Error 7](https://es.codefixcoffee.com/jura/automatic-machines/error-7/) cubre el mismo hardware fallando de forma más grave, con el accionamiento del grupo de preparación añadido: la máquina mandó la válvula de cerámica (en las GIGA, la multiválvula) a una posición y nunca la vio llegar, o el drive del grupo falló por el camino. En la GIGA X3c y X8c indica específicamente una multiválvula defectuosa, y en la GIGA 6 suele reportarse como bloqueo de motor o de bomba. Es uno de los pocos códigos Jura sin solución fiable a nivel de usuario.

Eso no significa que no valga la pena intentarlo antes de pedir cita.

1. Desenchufa cinco minutos y reinicia. El ciclo de inicio recoloca el grupo y la válvula, de modo que un bloqueo puntual puede desaparecer solo.
2. Descarta las causas baratas: vacía el depósito de posos y la bandeja de goteo, comprueba que no haya nada atascado en la salida de café y ejecuta un programa de limpieza completo sin interrumpirlo.
3. Si el código vuelve, lo habitual al abrir la máquina es encontrar el propio conjunto de la válvula: disco de cerámica agrietado, actuador bloqueado o encoder de posición muerto.

## Por qué el Error 7 suele acabar en el taller

El consejo honesto con este código es "banco de trabajo, salvo que ya repares estas máquinas". Las razones son prácticas antes que misteriosas:

- La carcasa de las Jura va cerrada con tornillos de seguridad (Torx-Plus ovalados) y hay tensión de red cerca de la zona de operación.
- La máquina debe vaciarse por completo antes de tocar la válvula, y el conjunto en sí es delicado de manejar.
- Tras sustituir la válvula o el motor del grupo, el mecanismo necesita recalibrarse para que la placa vuelva a fiarse de sus lecturas de posición.

Hay recambios para la mayoría de modelos —un conjunto de válvula de cerámica o multiválvula cuesta de 55 € a 140 € según modelo, un motor de grupo de 40 € a 65 €—, pero la mano de obra suele superar el precio de la pieza, así que pide presupuesto antes de pedir nada. El servicio oficial fuera de garantía para una superautomática suele moverse entre 230 € y 460 € con transporte de vuelta incluido, y un taller independiente de cafeteras suele salir más barato cuando se trata de una pieza conocida.

## ¿Compensa reparar la máquina?

Las máquinas que montan la válvula de cerámica son precisamente las que merece la pena conservar, y un Error 6 que desaparece tras el desescalado no cuesta nada. Con el Error 7 la cuenta depende del modelo: en una Z o GIGA de gama alta la reparación suele tener sentido, mientras que en una E o ENA de entrada con diez años conviene comparar el presupuesto con una unidad reacondicionada antes de decidir.

No todos los códigos Jura terminan en un banco de trabajo. El [Error 12](https://es.codefixcoffee.com/jura/automatic-machines/error-12/), el clásico atasco por una piedra en el molinillo, se resuelve casi siempre con un aspirador y una revisión del café en grano. La lista completa, incluidos los códigos de termobloque y de grupo de preparación, está en el [índice de códigos de error de Jura](https://es.codefixcoffee.com/jura/).

### La dureza del agua es muy local

Si vives en la España mediterránea o en zonas de agua muy caliza de Latinoamérica, como la península de Yucatán, tu grifo acelera justo el mecanismo que provoca el Error 6: la cal que endurece el disco. Configura la dureza del agua en el menú de la máquina o pasa a agua embotellada de mineralización débil, y respeta el desescalado aunque la máquina no lo reclame. [La asistencia oficial de Jura](https://www.jura.com) detalla los intervalos de mantenimiento recomendados para cada gama.
