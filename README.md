# Changes-WEB2-TPE

Tienda de ropa Changes Base de datos desarrollada para tienda de ropa masculina. Donde ser mostrara el catalogo de productos con funcionalidad de filtrado y creación de carrito para su compra La relacion entre las tablas es la siguiente: 

Usuarios <--> Carritos: Donde un usuario puede tener varios carritos, y que cada carrito pertenece a un solo usuario 
Carritos <--> Carrito_productos: Muestra que un carrito puede tener varios productos. Además Carritos muestra el estado de cada uno ya sea, activo, pendiente, finalizado o cancelado
Carrito_productos <--> Productos: Muestra que un producto puede estar en varios carritos La relacion entre los Productos y los Carritos la gestiona la tabla Carrito_producto, detalla los productos y la cantidad en cada carro
