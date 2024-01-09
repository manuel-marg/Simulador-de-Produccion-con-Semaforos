# Simulador de Línea de Producción del Escritorio PAHL de IKEA

La prestigiosa compañía sueca de mueblería IKEA ha contratado como desarrollador de software para realizar un programa que simule la línea de producción de su escritorio de última colección PAHL. El programa estará desarrollado en Java y utilizará hilos, semáforos y soluciones de tipo productor/consumidor y/o escritor/lector.

## Funcionalidades del Programa

El programa simulará la producción y ensamblaje de un escritorio PAHL, incluyendo la producción de 4 patas, 40 tornillos y 1 tabla, seguido por el ensamblaje de las piezas para la entrega a las tiendas IKEA en todo el mundo. Se deben seguir los lineamientos de la empresa, que incluyen la limitación de almacenamiento para cada parte producida, la contratación máxima de productores y ensambladores, y las tareas del jefe y el gerente.

## Requisitos y Capacidades

El programa deberá hacer uso de una interfaz gráfica que permita observar y controlar el sistema, proporcionando información en tiempo real sobre la cantidad de productores de cada tipo, la disponibilidad de piezas en el almacén, la cantidad de ensambladores, la cantidad de escritorios PAHL terminados, los días restantes para la entrega, las actividades del jefe y el gerente, entre otros datos relevantes.

Además, la simulación permitirá, en tiempo de ejecución, la contratación o despido de un productor de cualquiera de los tres tipos, así como la contratación o despido de un ensamblador. A través de un archivo (texto, objeto, CSV o JSON), se podrán indicar al programa parámetros como el tiempo que dura un día en el programa, la cantidad de días entre despachos, las capacidades máximas para cada tipo de almacenes, la cantidad inicial y máxima de productores y ensambladores, entre otros.

## Configuración Inicial

La empresa cuenta con una cantidad inicial de 1 productor de patas, 1 productor de tornillos, 1 productor de tablas y 1 ensamblador.

## Nota

Las cantidades iniciales especificadas en la sección anterior son las que deben colocarse en el archivo de configuración.

