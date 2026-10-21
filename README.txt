VOXEL AVENTURA — PROTOTIPO WEB

Cómo jugar:
1. Descomprime el ZIP.
2. Abre index.html en un navegador moderno con conexión a Internet (usa Three.js desde CDN).
3. Elige Pocket o Java y pulsa “Crear mundo nuevo”. El inventario empieza con una única espada.
4. En tablet: botones de movimiento abajo a la izquierda; arrastra en la zona derecha para mirar. Usa ROMPER, COLOCAR, USAR, INVENTARIO y CRAFTEO.
5. Para viajar: busca el portal de piedra cerca del punto inicial y usa 2 diamantes para activarlo. Pulsa USAR otra vez para ir al Inframundo; vuelve a usar el portal para regresar.
6. Busca el portal secreto turquesa en una zona alejada del mundo principal (aprox. x=-32, z=-24). USAR sobre él te lleva a la Dimensión del Dragón.
7. En la dimensión del Dragón, pulsa ATACAR 12 veces para derrotar al jefe. Recibirás 64 diamantes y 64 bloques de netherita. Usa el portal turquesa para regresar.

Implementado en este prototipo:
- Escena 3D voxel con terreno procedural local y generación alrededor del jugador. El punto inicial se coloca sobre césped.
- Selector Pocket (controles táctiles/rendimiento ligero) y Java (más estructuras generadas).
- Cinco ubicaciones fijas de árboles repartidas por el mundo; no aparecen árboles al azar.
- Estructuras: torre en ruinas, santuario, entrada de mina, formación de cristales y campamento abandonado.
- Movimiento en primera persona, salto básico y controles táctiles.
- Inventario inicial con solo espada, barra rápida, recolección y colocación de bloques.
- Recetas básicas, mesa de crafteo y horno interactivos.
- Portal del Inframundo activable con 2 diamantes, zona dimensional de lava y ladrillos, y portal secreto que conduce a la dimensión del Dragón.
- Jefe final simplificado: usa ATACAR 12 veces en la dimensión del Dragón para recibir 64 diamantes y 64 bloques de netherita.
- Guardado/carga local mediante localStorage en el mismo navegador/dispositivo.

Limitaciones: las dimensiones son arenas de prototipo, el dragón está representado por una figura de bloques y el combate se simula con el botón ATACAR (sin IA ni animaciones). El mundo tiene límites, las físicas y colisiones son básicas, no hay multijugador/servidores ni ciclo completo de clima/día-noche. No es una copia de Minecraft y utiliza una identidad visual propia.
- Actualización visual: materiales pixel-art procedurales con textura de alta definición por celdas, y corazones/comida dibujados con formas pixeladas decorativas.
- Nuevas aldeas en el mundo principal; fortaleza del Nether y bastión con patios de oro.
- Cuevas más profundas con mayor cantidad de minerales y posibilidad de encontrar bloques raros en las profundidades.


Actualización: se añadieron texturas pixel-art para ladrillos de aldeas, tablones, mesas y puertas; campo de semilla en el menú; mundos reproducibles por semilla; la semilla 7 crea una gran figura 7 dorada en el mundo.
