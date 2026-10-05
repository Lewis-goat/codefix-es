---
title: "Jura errores 1 a 5: la familia del termobloque, explicada"
description: "Los errores 1 a 5 de Jura apuntan todos a los termobloques, sus sondas NTC o los fusibles térmicos. Mapa de códigos y la trampa del Error 2 en frío."
---

Los códigos 1 a 5 de Jura parecen un puñado de números al azar, pero comparten un mismo protagonista: el calor. Todos remiten a los termobloques —los calentadores en línea compactos que producen el agua del café y el vapor— o a las sondas y cordones de protección que los vigilan. Una vez sabes leer la familia, cada código te dice qué resistencia está molesta y si el problema es de medición, de temperatura o de alimentación.

## Dos resistencias, cinco códigos

Una Jura monta dos termobloques: el del café calienta el agua de preparación y el de vapor alimenta el circuito de vapor y agua caliente. Cada uno lleva una sonda NTC —una resistencia cuyo valor varía con la temperatura— que reporta a la placa de control, y cada uno está protegido por cordones con fusible térmico que cortan la corriente si el bloque se recalienta. Los errores 1 a 5 son el aviso de la placa de que uno de esos elementos falla:

- **Errores 1 y 2** apuntan al circuito de la sonda del termobloque de café.
- **Errores 3 y 4** apuntan al termobloque de vapor, leyendo de menos o recalentándose.
- **Error 5** indica que la propia resistencia no entrega.

## Los códigos del lado del café

### Error 1: fallo de la sonda del termobloque de café

El [Error 1](https://es.codefixcoffee.com/jura/automatic-machines/error-1/) significa que la placa no consigue una lectura coherente de la sonda de temperatura del termobloque de café: en las familias S, X, J y Z es el fallo de sonda clásico, y en la F y la E80 suele indicar una sonda dañada. Una curiosidad útil: una máquina que acaba de llegar de un coche o garaje fríos puede mostrar este código sin que nada esté roto. Si aparece con la máquina caliente y regresa al instante tras reiniciar, el circuito de la sonda está abierto: la sonda, su cable o los cordones de fusible que alimentan el bloque.

### Error 2: sonda interrumpida, o simplemente frío

El [Error 2](https://es.codefixcoffee.com/jura/automatic-machines/error-2/) es el código Jura más común de todos, y tiene doble personalidad. La versión benigna: la máquina está por debajo de unos 10 °C y la resistencia queda bloqueada a propósito hasta que se calienta —típico de máquinas entregadas en invierno o instaladas en habitaciones frías—. La versión real: la sonda del termobloque de café o los cordones de fusible térmico han quedado en circuito abierto.

Por eso la prueba de calentamiento es el diagnóstico definitivo. Sube la máquina a temperatura ambiente —vale un secador al mínimo soplando cinco minutos en el hueco del depósito, o un depósito lleno de agua tibia (nunca caliente)— y reinicia. Si el código desaparece, no hay nada roto: guárdala en un lugar más templado. Si persiste con la máquina caliente, el circuito está abierto y toca revisar dentro la sonda NTC y los cordones de fusible.

## Los códigos del lado del vapor

### Error 3: el termobloque de vapor lee de menos

El [Error 3](https://es.codefixcoffee.com/jura/automatic-machines/error-3/) es el espejo del Error 1 en el lado del vapor: el termobloque no informa de su temperatura, por culpa de su sonda, de su cable o de una máquina todavía fría. Un matiz añadido: la cal abundante ralentiza el calentamiento lo suficiente para disparar la comprobación en algunos firmwares, así que un desescalado completo debe estar en la lista antes de desmontar nada. Por dentro, conviene inspeccionar el cable de la sonda en los tramos donde se flexiona.

### Error 4: recalentamiento del termobloque de vapor

El [Error 4](https://es.codefixcoffee.com/jura/automatic-machines/error-4/) es el que hay que tomarse en serio. El termobloque de vapor superó la temperatura que la placa esperaba: o la sonda lee de menos (cal que la aísla, contactos corroídos) o la placa de potencia no cortó la resistencia. La propia Jura sitúa los errores 2 y 4 como las dos reparaciones más frecuentes. Tras enfriar y desescalar, la sonda es el primer recambio; si el bloque se recalienta de nuevo con una sonda NTC nueva, la placa de potencia no está apagando la resistencia y debe sustituirse (presupuesta entre 120 € y 250 €). Una resistencia que no se apaga es un riesgo de incendio: no dejes la máquina enchufada sin vigilancia mientras este código esté activo.

### Error 5: la resistencia no llega a temperatura

El [Error 5](https://es.codefixcoffee.com/jura/automatic-machines/error-5/) significa que la resistencia se encendió y la temperatura nunca subió. En una Jura eso son casi siempre los cordones de fusible térmico que protegen el termobloque, que saltan tras un sobrecalentamiento o simplemente con los años; la otra causa es el elemento del termobloque muerto. Una máquina muy fría también puede provocarlo, así que caliéntala antes de sacar conclusiones. Dentro, mide con polímetro ambos cordones y el elemento: el que marque circuito abierto es la pieza a sustituir —y después averigua por qué saltaron los fusibles: cal, un relé pegado o un funcionamiento en vacío cuando el depósito se quedó sin agua—.

## La pieza que une toda la familia

En este grupo de códigos, los cordones de fusible térmico y las sondas NTC son los personajes recurrentes: una sonda NTC original cuesta entre 25 € y 40 €, un juego de cordones entre 15 € y 30 € y un termobloque entre 90 € y 180 €. Cuando se cambia una sonda, lo habitual entre técnicos es sustituir también los cordones. Y hay un patrón que importa: un fusible que vuelve a saltar a los pocos días significa que la placa deja la resistencia enganchada, no que el recambio tuviera mala suerte.

Recuerda que la carcasa de las Jura usa tornillos de seguridad y que los termobloques trabajan con tensión de red: esta familia es reparación de banco salvo que estés equipado para ello. Compensa arreglar una S, Z, GIGA o E moderna; en una Impressa de diez años, compara el presupuesto con una unidad reacondicionada. El resto de la gama queda en contexto en el [índice de códigos de error de Jura](https://es.codefixcoffee.com/jura/).

### Ojo con las cocinas frías en invierno

En buena parte de España las viviendas no tienen calefacción central y en pleno enero muchas cocinas bajan de 10 °C, justo el umbral del bloqueo del Error 2; algo parecido ocurre en ciudades altas y templadas-frías de Latinoamérica como Bogotá o Quito. Aleja la máquina de ventanas mal aisladas, terrazas cerradas sin calefacción y, por supuesto, del garaje. Para intervalos de mantenimiento y cuidados oficiales, [el soporte de Jura](https://www.jura.com) publica las recomendaciones por gama.
