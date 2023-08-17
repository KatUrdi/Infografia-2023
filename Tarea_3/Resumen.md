# 1 Datos:
En el video se explora los aspectos técnicos del desarrollo de juegos para NES (Nintendo Entertainment System), una plataforma de 8 bits lanzada en 1985. , abordando temas como la detección de colisiones, la generación de números aleatorios y el guardado de datos de juego. El video resalta los desafíos que enfrentaron los desarrolladores de juegos durante la era de NES y las soluciones creativas que idearon para superar estos desafíos. . Se discuten aspectos clave de generación de datos en 8 bits y se analiza el impacto de esta tecnología en el desarrollo de videojuegos.

# 2 Resumen:
En este video podemos ver el desarrollo de juegos en la consola NES de 8 bits. Se abordan los desafíos de trabajar con limitaciones técnicas, como la resolución de pantalla de 256x240 píxeles y una paleta de 64 colores. Se detallan métodos de generación de gráficos utilizando patrones de baldosas y capas, lo que permitió crear niveles con eficiencia en el uso de memoria limitada. Toca la detección de colisiones, la generación de números aleatorios y el guardado de datos de juego, arrojando luz sobre las soluciones ingeniosas que los desarrolladores utilizaron para crear experiencias de juego memorables a pesar de las limitaciones del hardware. Además, se discute cómo se lograron físicas realistas en juegos como Super Mario Bros. a pesar de las restricciones de poder de cálculo de la NES.

# 3 Puntos clave:
en el video podemos ver la importancia de generar números aleatorios en juegos de 8 bits, especialmente para escenarios como determinar eventos del juego, generación de enemigos, cálculos de daño, etc. algunos puntos importantes que destaco son:

- Resolución y paleta: La NES tenía una resolución de pantalla de 256x240 píxeles y una paleta de 64 colores, lo que desafió a los desarrolladores a ser creativos con la limitada gama de colores y detalles visuales.

- Gráficos con baldosas: Los gráficos se generaban utilizando patrones de baldosas de 8x8 píxeles, que se almacenaban en las tablas de patrones. Cada nivel se construía combinando estas baldosas, lo que permitía ahorrar memoria al reutilizar elementos visuales.

- Capas y sprites: Se utilizaban capas para crear un efecto de profundidad en los escenarios. Los sprites se usaban para elementos móviles, como personajes y enemigos. La NES permitía tener hasta 64 sprites en pantalla a la vez, lo que requería estrategias eficientes para la gestión de memoria.

- Compresión y set decoration: Para optimizar el uso de memoria, algunos juegos como Super Mario Bros. utilizaban técnicas de compresión y "set decoration". Esto implicaba almacenar patrones repetitivos en los fondos y solo almacenar los elementos únicos para cada nivel.

- Registro de Desplazamiento Lineal de Retroalimentación de Fibonacci de 16 bits: Un enfoque sofisticado utilizado por Tetris, que implica la manipulación de la -memoria y comparaciones de bits, lo que resulta en una secuencia de números pseudoaleatorios.

- Tablas Precomputadas: Final Fantasy emplea una tabla de números aleatorios precomputados, almacenada en la memoria. Este método es eficiente pero requiere la preparación manual de la tabla.

- Cálculo Basado en Cuadros: El enfoque de Contra implica el uso del número de cuadro actual para calcular números aleatorios, a pesar de su simplicidad, es funcional para su caso de uso específico.
