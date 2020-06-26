# solid-python
Principios SOLID (Robert C Martin) aplicados en Python 

Seccion 1-Introduccion

1. Introduccion
	S: Principio de Responsabilidad Única		SRP
	O: Principio Abierto Cerrado				OCP
	L: Principio de Substitución de Liskov		LSP
	I: Principio de Segregaciónde Interfaces	ISP
	D: Principio de Inversión de Dependencias	DIP

	Ventajas en el codigo:
	* Facil de mantener y ampliar con el tiempo

	Razones para aplicar
	* Software robusto
	* Codigo limpio
	* Codigo escalable
	* Alta cohesion y bajo acoplamiento

2. 	Acoplamiento
	Es la forma y el nivel de interdependencia entre modulos de software
	Bajo acoplamiento = bien estructurado con un buen diseño de software
	Mejora la mantenimibilidad
	Mejora la reutilizacion
	Minimiza el riesgo de modificar mucho software
	
3.	Cohesion
	El el grado en que los elementos de un mismo módulo permacen juntos
	Alto cohesion, implica mucha relacion, se busca alta cohesion

Seccion 2- Principio de Responsabilidad Única-SRP

4. Teoria SRP
	Una clase debe tener una y solo una razón para cambiar
	Una clase/metodo/funcion debe tener una unica responsabilidad, es decir hacer una unica cosa o funcionalidad

5.	Escribiendo Código que incumple el SRP
	