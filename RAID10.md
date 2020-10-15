**RAID 1+0 (RAID 10)** ***(Stripping of Mirrors)***

![RAID 1+0](img/RAID_10_01.svg)

> By NudelSuppe, basierend auf RAID 01 von Cburnett - Own work, CC BY 3.0, https://commons.wikimedia.org/w/index.php?curid=22591138

Mínimo 4 discos.

La capacidad de este arreglo es la mitad de la suma de las capacidades de los discos. Ej: Cuatro discos de 1TB dan un arreglo de 2TB.

Se crea un mirror y se hace un stripe del mirror. El arreglo puede sostener la falla de más de un disco siempre y cuando ningún mirror pierda todos sus discos.

De acuerdo a las especificaciones del fabricante y a benchmarks oficiales independientes, en la mayoría de los casos *RAID 10* ofrece mejor rendimiento y latencia que todos los otros niveles *RAID* excepto *RAID0* (que gana en rendimiento). Es por esto, que este arreglo es el preferido para aplicaciones intensivas de entrada y salida (*I/O-intensive*): servidores de bases de datos, servidores web y de correo electrónico, así como también cualquier otro uso que requiere alto rendimiento del sistema de discos.
