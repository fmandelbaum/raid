**RAID 5** ***(Distributed Parity)***

![RAID 5](img/RAID_5.svg)

> By en:User:Cburnett - Own work  This W3C-unspecified vector image was created with Inkscape., CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=1509158

Mínimo 3 discos (2 de datos + 1 de paridad).

Separación en tiras a nivel de bloque (*block-level stripping*) con paridad distribuída, sin espejado (*mirroring*).

La capacidad de este arreglo es la suma de la capacidad de los discos que componen el conjunto de datos. Ej: Tres discos de 1TB dan un arreglo de 2TB.

El beneficio de este arreglo es que frente a la falla de uno de los discos, el arreglo puede seguir operando (como en el *RAID1*), sin pérdida de datos (se usa la información de paridad para reconstruir los datos cuando haga falta), y con la ventaja de rendimiento de lectura y escritura (aunque un poco menos en este caso, porque hay que calcular la paridad) del *RAID0*.

Sin embargo, para reconstruir el arreglo después del fallo de un disco, se necesita leer la todos los datos de todos los discos, lo cual puede causar la pérdida total del arreglo si falla un segundo disco mientras se reconstruye el arreglo.
