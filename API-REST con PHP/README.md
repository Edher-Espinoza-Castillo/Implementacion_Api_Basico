# Api-Rest con PHP
 
# Las URL a emplear son los siguientes:

* GET /peoples → recuperara una lista de personas.
* GET /peoples/1 → recupera la información de una persona en específico.
* POST /peoples → Crea una nueva persona
* PUT /peoples/1 → Actualiza el registro con el ID 1
* DELETE /peoples/1 → Elimina el registro con ID 1



# Los códigos de respuesta a utilizar son:


1. 500: Internal Server Error → Se ha producido un error interno
2. 422: Unprocessable Entity → Entidad no procesable
3. 400: Bad Request → La solicitud contiene sintaxis errónea y no debería repetirse
4. 204: No Content → La petición se ha completado con éxito, pero su respuesta no tiene ningún contenido



# Para probar el API se debe usar mediante Insomnia, y configurar algunas peticiones dependiendo de la ruta del proyecto correspondiente:

1. Obtener personas: GET: http://localhost/tuProyecto/peoples
2. Persona por ID: GET: http://localhost/tuProyecto/peoples/1
3. Nueva persona: POST: http://localhost/tuProyecto/peoples
4. Actualizar registro: PUT: http://localhost/tuProyecto/peoples/1
5. Eliminar registro: DELETE: http://localhost/tuProyecto/peoples/1
