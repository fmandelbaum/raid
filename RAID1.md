**RAID 1** ***(Mirroring)***

![RAID 1](img/RAID_1.svg)

> By en:User:Cburnett - Own work  This W3C-unspecified vector image was created with Inkscape., CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=1509082

Mínimo 2 discos. Siempre cantidad par de discos en el arreglo.

Espejado (*mirroring*) de los datos, sin separación en tiras (*stripping*) ni paridad.

La capacidad de este arreglo es la mitad de la suma de las capacidades de los discos. Ej: Dos discos de 1TB dan un arreglo de 1TB.

Si falla un disco del arreglo no se pierde ningún dato (la otra mitad del arreglo tiene todos los datos).

El beneficio de este arreglo es la tolerancia alta frente a fallos. También se beneficia el rendimiento de las operaciones de lectura (el disco que tiene "más disponible" el dato es el que lo proporciona). Sin embargo, las operaciones de escritura son (un poco) más lentas ya que hay que escribir "dos veces" cada dato.
