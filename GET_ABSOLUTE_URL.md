# proyecto_final_blog
Cuando ejecuto estas lineas de codigo, funciona todo, aclaro que lo estoy generando aun, pero cuando genero el posteo y lo quiero grabar, en models.py defino una funcion
con get_absolute_url y la derivo al .html principal, denominado home, pero al llegar a estas instancias de ejecucion me reporta el error "No URL to redirect to.  Either provide a url or define a get_absolute_url method on the Model."
Tengo entendido que esto sucede cuando no encuentra el .html correspondiente, pero he revisado todo el codigo de nuevo y no encuentro el problema, hasta sustitui en templates home la linea   <li><a href={%url "home" post.pk%} por {%post.get_absolute_url}
Pero no obtuve resultados, aun sigue dandome el error.
En admin el user es: walter y la password:pulgosa
