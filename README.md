# Competencia de la doble rendija cuántica
Este experimento es realizado con la finalidad de materializar y entender el comportamiento de uno de los experimentos denominado "El más bello del siglo XIX" en la física
### Historia:
Thomas Young, con el objetivo de apoyar la teoría de que la luz era una onda y rechazar la teoría de que la luz estaba formada por partículas.
hizo pasar un haz de luz por dos rendijas y vio que sobre una pantalla se producía un patrón de interferencias, una serie de franjas brillantes y oscuras alternadas.

Este resultado es inexplicable si la luz estuviera formada por partículas porque deberían observarse sólo dos franjas de luz frente a las rendijas, pero es fácilmente interpretable asumiendo que la luz es una onda y que sufre interferencias.


### Importancia:
El experimento de la doble rendija es de gran importancia en el campo de la física y la comprensión de la naturaleza fundamental de la materia y la luz por diversos motivos:
En primer lugar, demuestra la dualidad onda-partícula de las partículas subatómicas, como electrones y fotones, mostrando que las partículas pueden exhibir tanto comportamiento de partícula como de onda. Esto desafía la noción clásica de que las partículas son entidades sólidas y puntuales y nos lleva a una comprensión más profunda de la naturaleza cuántica de la realidad.
Este experimento es un pilar fundamental en la teoría cuántica, ayudando a establecer los conceptos fundamentales de la superposición, la interferencia y la probabilidad en el mundo subatómico. Además, proporciona evidencia experimental de que las partículas subatómicas no siguen las mismas reglas que los objetos macroscópicos y nos lleva a una nueva descripción de la realidad basada en las leyes cuánticas.

### planteamiento:
- Primero realizamos nuestros grafos en papel y lápiz el cual nos dió la facilidad para corregir algunos elementos.
- Establecimos nuestro estado iniciale el cual fue: X0= [1,0,0,0,0,0,0,0]^t ; el mismo para el estado probabilístico y cuántico.
- la matriz para el sistema probabilístico fue: [[0,0,0,0,0,0,0,0],[1/2,0,0,0,0,0,0,0],[1/2,0,0,0,0,0,0,0], [0,1/3,0,1,0,0,0,0], [0,1/3,0,0,1,0,0,0], [0,1/3,1/3,0,0,1,0,0], [0,0,1/3,0,0,0,1,0], [0,0,1/3,0,0,0,0,1]]; la cual cumple la caracteristica que la suma de las filas y columnas debe dar 1.
- La matriz para el sistema cuántico fue: [[0,0,0,0,0,0,0,0],[complex(0, 1/math.sqrt(2)),0,0,0,0,0,0,0],[complex(0, 1/math.sqrt(2)),0,0,0,0,0,0,0], [0,complex(0, -1/math.sqrt(3)),0,1,0,0,0,0], [0,complex(0,1/math.sqrt(3)),0,0,1,0,0,0], [0,complex(0, -1/math.sqrt(3)),complex(0, -1/math.sqrt(3)),0,0,1,0,0], [0,0,complex(0, 1/math.sqrt(3)),0,0,0,1,0], [0,0,complex(0, -1/math.sqrt(3)),0,0,0,0,1]].
- Utilizando la libreria presentada en la actividad "Simulación de lo clásico a lo cuántico" podemos corroborar nuestro experimento.
  (Al igual que en la libreria utilizada usamos Numpy, math y complex)
- El resultado de manera teorica se puede apreciar que existe un "lugar" en donde habrá mayor porcentaje de visivilidad, este resultado es respaldado mediante el resultado práctico al encontrar en algunos espacios mayor concentración del haz de luz.

### Materiales:
Para este experimento utilizamos los siguientes materiales:
- Papel aluminio.
- Un Láser Color rojo.
- Un listón de balso.
- Un gancho de ropa.
- Dos palitos del juego "Jenga"
- Cuchillas punta de lanza.
- Cinta

### Montaje experimental:
- Tomamos el láser y lo pegamos con cinta a uno de los palitos del juego jenga para determinar la altura a la que se encontrará el laser.
- Teniendo en cuenta la altura tomamos un liston de balso el cual cuenta con las siguientes dimensiones 5cm de ancho x 5cm de alto x 0.4 cm de profundo y realizamos cortes formando un cuadrado en el centro del listón; esta ranura cuenta con las siguientes dimensiones 2cm de ancho x 2cm de largo x 0.4 cm de profundo.
- Con ayuda de las cuchillas punta de lanza cortamos un trozo de papel aluminio en forma de cuadrado el cual cubrirá por completo la ranura hecha en el liston; seguido de esto calculando el centro del trozo del papel aluminio realizamos dos pequeños cortes muy finos los cuales se encuentran separados uno del otro por cuestiones milimétricas.
  (Para poder apreciar de mejor manera la separación se recomienda colocar el papel alumio en contra luz)
- Pegamos el papel aluminio sobre el listón con cinta cubriendo en su totalidad el cuadrado hecho en el listón.
- Para garantizar mejores resultados en el experimento y disminuir el error sistemático tomamos un pequeño gancho de ropa; en el momento que se coloca sobre el láser, este lo mantendrá encendido.
- Nos ubicamos sobre una superficie uniforme, encendemos el láser, enfrente ubicamos la doble rendija hecha sobre el papel aluminio, apagamos la luz y veremos proyectado el patrón de interferencia formado.

### Desarrolladores del experimento:
- Ivan Santiago Forero Torres (Estudiante de Ingenieria en Sistemas)
- Joshua David Quiroga (Estudiante de Ingenieria en Sistemas)

## Universidad Escuela Colombiana de Ingenieria Julio Garavito.
