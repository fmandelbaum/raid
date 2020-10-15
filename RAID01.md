**RAID 0+1** ***(Mirror of Stripes)***

![RAID 0+1](img/RAID_01.svg)

> By Wheart, based on image File:RAID 0.svg by Cburnett - Own work, CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=6411849

Mínimo 4 discos.

La capacidad de este arreglo es la mitad de la suma de las capacidades de los discos. Ej: Cuatro discos de 1TB dan un arreglo de 2TB.

Se crean dos stripes y se hace un mirror de ambos. Si falla un solo disco, entonces uno de los mirror falló. En este punto se comporta efectivamente como *RAID0* sin redundancia. En la reconstrucción del arreglo tiene más riesgo que *RAID 1+0* ya que se deben leer todos los datos de todos los discos de la tira que queda.
