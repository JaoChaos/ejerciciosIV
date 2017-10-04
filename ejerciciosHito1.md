# Ejercicios Hito 1 de la asignatura IV 2017/18.

## Ejercicio 1: Consultar en el catálogo de alguna tienda de informática el precio de un ordenador tipo servidor y calcular su coste de amortización a cuatro y siete años.

Primero de todo, dejo un link sobre [cómo se calcula una amortización](http://www.ennaranja.com/economia-facil/que-es-y-como-calcular-una-amortizacion/) para que los lectores puedan consultarlo antes de ver las tablas.

Según el enunciado del ejercicio, suponiendo que se trata de una sustitución de un objeto a los 4 años y a los 7. Así, tenemos que dividir el coste del servidor( sin contar el IVA) entra esos respectivos años.

Yo he utilizado el siguiente [servidor](https://www.pccomponentes.com/hp-proliant-microserver-gen10-amd-opteron-x3216-8gb) de la página de PCcomponentes. Su coste sin IVA es de 214,05€.

Amortización a 4 años: 
Cuota de amortización: 53,51€.

| Año	| Amort. Acumulada	| Valor	|
|------	|:---------------------:|-----:	|
|1	|53,51€			|160,54€|
|2	|107,03€		|107,02€|
|3	|160,53€		|142,7€	|
|4	|214,05€		|0€	|

Amortización a 7 años:
Cuota de amortización: 30,58€-

| Año	| Amort. Acumulada	| Valor	|
|------	|:---------------------:|-----:	|
|1	|30,58€			|183,47€|
|2	|61,16€			|152,89€|
|3	|91,74€			|122,31€|
|4	|122,32€		|91,73€	|
|5	|152,9€			|61,15€ |
|6	|183,48€		|30,58€	|
|7	|214,05€		|0€	|


## Ejercicio 2: Usando las tablas de precios de servicios de alojamiento en Internet y de proveedores de servicios en la nube, Comparar el coste durante un año de un ordenador con un procesador estándar (escogerlo de forma que sea el mismo tipo de procesador en los dos vendedores) y con el resto de las características similares (tamaño de disco duro equivalente a transferencia de disco duro) en el caso de que la infraestructura comprada se usa sólo el 1% o el 10% del tiempo.

Servidores:

[Cloud Next 1 mensual](https://www.arsys.es/servidores/cloud) 1vCPU, 1GB RAM, 40GB SSD por alrededor de 15€/mes.

[Cloud M mensual] 1vCore, 1GB memoria RAM, 50GB SSD alrededor 10€/mes

[Cloud M](https://www.1and1.es/servidor-cloud-dinamico#configuracion-del-servidor) 1vCore, 1GB RAM, 50GB SSD por 0,014€/h

[t2.micro](https://aws.amazon.com/es/ec2/pricing/) 1vCore, 1GB RAM, almacenamiento EBS por 0,014$/h

Para una contratación de 6 meses:
	- Cloud Next 1: 90€
	- Cloud M mensual: 60€

Saldría más barato el Cloud M ya que el precio es independiente del uso.

Para una contratación por horas durante 6 meses al 1% de uso:

	- Cloud M: 4320h*0.01*0.014=0.61€
	- t2.micro: 4320*0.01*0.014=0.61€

Para una contratación por horas durante 6 meses al 10% de uso:

	- Cloud M: 4320*0.1*0.014=6.13€
	- t2.micro: 4320*0.1*0.014=6.13€

Como se observa, sale más rentable contratar los servicios por hora cuando se una solo una parte de los servicios. Para cuando se necesite el 100%, la contratación mensual resulta mejor.

## Ejercicio 3:En general, cualquier ordenador con menos de 5 o 6 años tendrá estos flags. ¿Qué modelo de procesador es? ¿Qué aparece como salida de esa orden? Si usas una máquina virtual, ¿qué resultado da? ¿Y en una Raspberry Pi o, si tienes acceso, el procesador del móvil?

Ejecuto la orden cat /proc/cpuinfo:

[img1]
[img2]
[img3]



