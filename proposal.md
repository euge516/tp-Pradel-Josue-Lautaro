# Propuesta TP DSW

## Grupo:No especificado
### Integrantes
* legajo - Apellido(s), Nombre(s)
* 39932 -   Eugene, Pradel --> eugedev516@gmail.com
* 52523 - Kalkov Lautaro --> lautarokalkov@gmail.com
* 47007 - Josue Micael, Herrera --> josueherrera790@gmail.com

### Repositorios
* [frontend app](https://github.com/euge516/front.git)
* [backend app](https://github.com/euge516/back-end.git)

## Tema: Systema de gestion de producto(E-commerce)
### Descripción:"El sistema va a permitir al cliente de realizar su compra online, y ver su historial de compra y sumar punto para que puede canjearlo en un futuro. Y para el dueno le va a permitir de gestion sus productos mejor, ver los productos mas vendido etc."


### Modelo
![img](C://Users//prade//Downloads//gestiondeproducto.drawio.png)

![Link](https://app.diagrams.net/#G1UTT0csvfq2Sclc_0FIJ-2UyeDlAqiTds#%7B%22pageId%22%3A%229f46799a-70d6-7492-0946-bef42562c5a5%22%7D)

## Alcance Funcional 

### Alcance Mínimo


Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Usuarios<br>2. CRUD Permision<br>3. CRUD Tipo de pago|
|CRUD dependiente|1. CRUD Venta {depende de} CRUD Productos y CRUD Tipo de pago<br>2. CRUD Productos {depende de} CRUD SubCategoria |
|Listado<br>+<br>detalle| 1. Listado de Producto filtrado por mas vendido, muestra nro y nombre,cantidad,stock,fecha<br> 2. Listado de producto filtrado por categoria, muestra Codigo, nombre y stock|
|CUU/Epic|1. Vender producto<br>2.Finalizar compra.


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Categoria<br><br>2. CRUD Presentacion<br>3. CRUD Menu<br>4. CRUD Localidad<br>5. CRUD Provincia<br>6. CRUD Pais<br>7. CRUD Punto<br>8. CRUD SubCategoria
<br>9. CRUD SubMenu<br>10.CRUD Lote|
|CUU/Epic|1. Crear la subcategoria<br>2. Crear SubMenu|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, Cada vez que un cliente realiza una compra el sistema asignara un valor en puntos dependiendete del monto total, a mayor monto mas puntos. Esto beneficiara al cliente con descuentos conforme a la cantidad de puntos que haya obtenido.

|Req|Detalle|
|:-|:-|
|Listados |1. CRUD Punto <br>2.Punto por vencer|
|CUU/Epic|1. Cajear punto|
|Otros|1. Envío de recordatorio de reserva por email|

