**Una clase debe tener una única responsabilidad o razón para cambiar**

ventajas:
- **Baja el acoplamiento al evitar tomar responsabilidades de otras clases**
- Aumenta la cohesión al unificar las responsabilidades de la clase.

**Ejemplo**: Dividir el diseño en varias clases.

- **Problema**: Tener una clase **Reporte** que se encargue de generar informes y enviarlos x mail. 
	- **HAY BAJA COHESIÓN**
		- Si cambiamos la forma de enviar mails, cambiamos **REPORTE**
		- Si cambiamos la lógica del Generador de reportes,, cambiamos la clase **REPORTE**
		- Si cambiamos la lógica del reporte tmb cambiamos **REPORTE**
- **SOLUCIÓN**
	- 