**RAID - Arreglo de Discos Independientes Redundantes**

Conjunto de discos que trabajan como un solo volumen lógico, para brindar redundancia de datos, mejoras en el rendimiento, o ambos.

Los datos se distribuyen en los discos en alguna de varias maneras, que se conocen como niveles de *RAID*. Cada nivel brinda un balance diferente entre los objetivos principales: *confiabilidad*, *disponibilidad*, *rendimiento* y *capacidad*.

Por lo general, se utilizan discos iguales (misma marca, mismo modelo) para componer el arreglo.

**Niveles Standard Más Utilizados**

[RAID 0](RAID0.md)

[RAID 1](RAID1.md)

[RAID 5](RAID5.md)

**Arreglos Andidados (Híbridos)**

Los elementos del *RAID* pueden ser discos individuales u otros arreglos *RAID*. Por lo general, no se anidan más de un nivel. Estos arreglos siempre se conforman con una cantidad par de discos y buscan combinar los beneficios de los niveles *RAID* que se anidan (con un costo mayor, ya que se necesitan más discos).

[RAID 0+1](RAID01.md)

[RAID 1+0](RAID10.md)


> Fuente: Wikipedia. https://en.wikipedia.org/wiki/RAID, https://en.wikipedia.org/wiki/Standard_RAID_levels, https://en.wikipedia.org/wiki/Nested_RAID_levels
