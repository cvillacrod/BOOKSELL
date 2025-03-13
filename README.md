# BOOKSELL
App movil para la venta de libros.


#Introducción y objetivos
En la actualidad, el intercambio de libros en el CIP de Estella se realiza manualmente a
través de carteles en el tablón de anuncios del centro.
El objetivo del proyecto es diseñar e implementar una aplicación móvil para el intercambio
y/o venta de libros en el CIP de Estella.
En los siguientes apartados se detallan los requisitos funcionales y no funcionales mínimos
que se requieren en el proyecto.

#Registro de usuarios
Cualquier persona debe poder registrarse en la aplicación al abrirla por primera vez.
Se pedirán los siguientes datos mínimos:
- Nombre y apellidos
- correo electrónico
- teléfono de contacto
- contraseña
El correo electrónico hará las veces de identificador para el usuario.
#Editar perfil
Cada usuario debe poder editar los datos de su perfil en cualquier momento.
El correo electrónico no podrá cambiarse, ya que es el identificador de usuario.
#Publicar un libro
Cualquier usuario puede publicar uno o varios libros que quiere vender. Para ello, se
pedirán los siguientes datos mínimos:
- Título
- ISBN
- Año de publicación
- Ciclo formativo
- Módulo
- Precio al que se ofrece
- Estado (en venta / vendido)
Se guardará internamente la fecha en la que se publica el libro en la aplicación.
También se guardará un identificador único para cada libro publicado.
#Consultar Mis Libros
Los usuarios deben poder consultar los libros que han publicado en la aplicación.
Desde aquí debe ser posible modificar los datos de un libro o eliminar un libro.
También debe verse el estado de cada libro (en venta / vendido).
# Buscar libros
Los usuarios deben poder consultar los libros publicados por otros usuarios de la
aplicación. Sólo deben verse aquellos libros que aún no han sido vendidos.
Debe ser posible filtrar los libros por título, ciclo formativo y módulo.
#Enviar un mensaje
Al seleccionar un libro que esté en venta, el usuario debe poder enviar un mensaje al
vendedor para realizar alguna pregunta o ponerse en contacto para realizar la venta.
El vendedor debe recibir una notificación emergente en su móvil avisando de que ha
recibido un mensaje.
# Historial de mensajes
Los usuarios deben poder consultar el historial de mensajes que han realizado en la
aplicación. Los mensajes estarán agrupados por conversaciones. Cada conversación estará
asociada a un libro en venta.
Desde aquí debe ser posible continuar una conversación.
# Vender un libro
Cuando un usuario cambie el estado de un libro a “Vendido”, todos aquellos usuarios que
tengan mensajes relacionados con dicho libro recibirán una notificación emergente
avisando de que el libro ya no está disponible. También se añadirá un mensaje en la
conversación diciendo “El libro ha sido vendido”.
# Borrar un libro
Cuando un usuario borre un libro de la aplicación, todos aquellos usuarios que tengan
mensajes relacionados con dicho libro recibirán una notificación emergente avisando de
que el libro ya no está disponible. También se añadirá un mensaje en la conversación
diciendo “El libro ha sido eliminado”.
Las conversaciones asociadas al libro no deben eliminarse.
# Darse de baja
El usuario debe poder darse de baja de la aplicación, eliminando así su perfil de usuario.
Todos los libros publicados por el usuario serán también eliminados y se aplicarán las
instrucciones de la sección “Borrar un libro”.
