# Organización de archivos y carpetas
 Esta bóveda sigue una implementación ***basada*** en [[Orden de carpetas y archivos|Jonny Decimal]], una propuesta para organizar carpetas y archivos. Esta puede consultarse [acá](https://johnnydecimal.com/10-19-concepts/11-core/11.01-introduction/). [^1]
## Reglas: 
- Solo las carpetas llevan la numeración.
- La numeración sigue este orden: NN.NN siendo cada N un *Nivel* diferente.
- Las carpetas de cualquier nivel pueden contener tanto archivos como otras carpetas.
- Existen 4 niveles:
	- Las **'Areas'** Ocupan los espacios X
	- Las **'Categorías'** los espacios XX
	- Las **'Sub-categorías'** los espacios XX.X
	- Los **'IDs'** los espacios XX.XX
- Como generalidad no pueden haber mas de 10 carpetas en el mismo nivel, es decir solo puede existir para el *area 1* las carpetas 10, 11, 12, 13, 14, 15, 16, 17, 18, 19. De ninguna manera existiría algo como 101 o  156. Mas de 10 carpetas satura el orden visual que se busca.
- Cada carpeta siempre debe estar contenida en una carpeta de nivel superior, a excepción de obviamente las areas. Ejemplo:
	- 0
		- 00
			- 00.0
				- *Archivo*
			- 00.1
				- 00.11
				- 00.12
				- 00.13
			- 00.2
		- 01
			- 01.0
			- 01.1
				- 01.11
		- 02
	- 1
* Las carpetas tienen: `[numeración] [espacio] [nombre]`
	* 01 Obsidian
	* 1 Personales
	* 21.11 Asignatura1
## Generalidades sugeridas
- Las carpetas que terminan con cero *0* o doble cero *.00* se tienden a reservar para archivos que explican el sistema, o una explicación relacionada al contenido de la carpeta madre. Como en este caso *00 System* o *'21.0 General'*. 
- Por simplicidad en las carpetas XX.00 o XX.0 Se recomienda solo colocar archivos, no sub carpetas
- En las carpetas que terminen en 9 se recomienda colocar los archivos o elementos que se creen en gran volumen y/o que no requieran un orden, como por ejemplo las notas diarias en `19 Notas diarias` o archivos de las notas en `9 Data`

[^1]: Aunque dista bastante de la propuesta original, es necesario mencionarla. 
