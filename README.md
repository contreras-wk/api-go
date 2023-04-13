# api-go
Pruebas para construir una API Rest con Gonlang. Se implementa el framework de Fiber v2

## Propuesta de estructura del proyecto!

- server
	+ server.go
- v1 -> Version de la API Rest
	+ application
		* Nota: archivos equivalentes los viewsets!
	+ domain
		* Nota: archivos equivalentes a los modelos!
	+ infrastructure 
		* Nota: En caso de que se requiera conexiones a diferentes bases de datos o se consuman servicios externos.
	
	+ routers
		* Manejo y gestion de las urls por aplicacion !
	
	api.go 
	
	
- cmd
- main.go 