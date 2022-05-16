Titulo de proyecto: "Consecionaria"

Descripcion:

Proyecto de cierre de modulo 2 de Digital House.

Se trata de un ejercicio integrador en el cual se cuenta con un modulo "autos.js" en el cual hay definido un array
de objetos de tipo auto, los cuales tienen como atributos: marca, modelo, precio, km, color, cuotas, anio, patente y vendido.
Dicho modulo se exporta y es luego requerido en el modulo principal "app.js".
En este modulo se crea un objeto de tipo concesionaria el cual se guarda el array de autos en una propiedad, y tambien
se generan diferentes metodos para operar con los autos del array.

Los metodos desarrollados son:

	buscarAuto(patente), 
	venderAuto(patente), 
	autosParaLaVenta(), 
	autosNuevos(), 
	listaDeVentas(), 
	totalDeVentas(), 
	puedeComprar(auto, persona), 
	autosQuePuedeComprar(persona).

Ejecucion:
(En terminal)
node app.js

DISCLAIMER: Este modulo cuenta con solo metodos que fueron validados por los casos de testeo de la plataforma de Digital House. No se ha hecho uso de los metodos por lo tanto la ejecucion del modulo no hara nada.
	





