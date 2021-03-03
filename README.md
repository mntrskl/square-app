# square-app
# Practice
Detalles a implementar:
- Escenas
	- App
- Actores
	- Square: Cuadrado representado en pantalla con componente Image.
- Acciones
	- Jump: Movimiento vertical en el eje Y (+50) que retorna al origen.
	- Spin: Rotacion sobre el eje Z de 360°.
   	- Ping Pong: Movimiento lateral que visita ambos extremos en X (50,-50) y retorna al origen.
   	- Play Animation: Ejecuta un Animation Clip asociado al objeto.
- Deseables
	- Efectuar correcciones previamente discutidas.
	- Evitar que el usuario pueda ejecutar varias acciones al mismo tiempo. O permitir esto de manera ordenada y limpia.
	- Canvas con ajuste dinamico a la resolucion de pantalla.
	- Boton "Ping Pong", implementar funcionalidad. 
	- Boton "Play Animation", implementar funcionalidad.
	- El texto "Action Text" deberia actualizarse mientras se realiza una accion.
	- Definir si para Square conviene cambiar el tipo a un SpriteRender.
- Extras
	- Generar una nueva Scene "Splash" y transicionar de esta a la Scene "App".
	- Implementar eventos para cuando una accion termina.
	- Reproducir un sonido cuando se toca un boton.
