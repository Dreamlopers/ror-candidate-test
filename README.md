# Prueba básica para desarrollador piloto en Ruby on Rails
## Dreamlopers

La siguiente prueba pretende encontrar las características, capacidades y cualidades necesarias que un desarrollador debe tener para trabajar en proyectos específicos relacionados con el lenguaje Ruby y el framework Rails.

### Normas de la prueba

- Evidentemente no existe un monitoreo estricto, pero se sugiere con alto hincapié resolver la prueba en su totalidad haciendo uso de los recursos particulares del desarrollador.
- La prueba debe realizarse en el plazo establecido de 24 horas sin ningún tiempo extra.
- La prueba debe entregarse con las instrucciones necesarias para lograr la instalación, ejecución y uso del material que el evaluado entregue.


### Problema planteado

Se necesita crear una aplicación que permite la administración de un cine en las afueras de la ciudad de Caracas Venezuela. El dueño del cine necesita que la aplicación que se le entregue permite a los usuarios manipular sus entradas y horarios para disfrutar de sus películas, además de saber cuales son las disponibles y poder hacer la compra. El cine solo dispone de cuatro salas de cine y cada una de ellas con una capacidad maxima de 250 butacas.

### Caracteristicas de la aplicación

- La aplicación debe tener dos áreas principales y separadas. El área de administración y el área pública
- Así mismo debe existir un administrador que permita modificar lo necesario y usuarios que puedan ver la lista de películas para poder comprarlas.
- Area de administracion
	- Debe poder verse la cantidad de entradas que se han comprado y las características de las entradas (película, fecha, hora, usuario, etc)
	- Debe poder hacer uso de CRUD de películas donde se puedan agregar las películas que los usuarios quieren ver
	- Así mismo se puede ver la cantidad de dinero que una película ha generado en su totalidad.
	- Registro de los usuarios que han comprado en el cine y cuántas entradas
- Area publica
	- Un usuario publico puede comprar una entrada para una película haciendo uso de su cedula, telefono y su nombre.
	- Un usuario público puede escoger su película, la hora, el dia y la butaca que desea.
- Es necesario que los usuarios sean personas naturales venezolanas para poder entrar al cine, mayores de edad y con un celular válido
- Las películas deben tener una descripcion, un costo, un titulo y una imagen que se muestra al almacenar una URL buscada en google (Ejm: [Imagen] http://es.web.img3.acsta.net/pictures/14/02/26/13/43/492816.jpg)
- La pagina de inicio o pagina raiz debe tener un estilo basico con bootstrap donde se muestra la lista de peliculas que el cine sugiere.
- Nadie a excepción del administrador puede modificar las peliculas y ver las estadísticas.
- Las compras en el sistema serán simuladas por un boton que tenga una confirmación.
- Es posible tener varias películas en cartelera con diferentes horarios para la misma sala

### Aspectos tecnicos
Para desarrollar esta aplicación se necesita:
- Rails 4.2.6
- Ruby 2.2.0
- MongoDB como base de datos
- SOLO LA PAGINA INICIAL con bootstrap

### Una cosa más
En esta prueba se evalúa lo siguiente:
- Habilidad para resolver problemas
- Expontaneidad
- Nivel en rails
- Nivel un ruby
- Nivel como desarrollador
- Nivel de diseño de software





