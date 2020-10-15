**RAID 0** ***(Stripping)***

![RAID 0](img/RAID_0.svg)

> By en:User:Cburnett - Own work  This W3C-unspecified vector image was created with Inkscape., CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=1509075

Mínimo 2 discos.

Separación en tiras (*stripping*), sin espejo (*mirroring*) ni paridad.

La capacidad de este arreglo es la suma de las capacidades de los discos. Ej: Dos discos de 1TB dan un arreglo de 2TB.

Si falla un disco del arreglo se pierden todos los datos.

El beneficio de este arreglo es el rendimiento de las operaciones de lectura y escritura: en principio se multiplica el rendimiento de cada disco por la cantidad de discos que componen el arreglo.
