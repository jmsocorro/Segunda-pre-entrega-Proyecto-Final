# Segunda pre-entrega Proyecto Final

## Endpoints api/products

### query para buscar

#### en stock

http://localhost:8080/api/products?query={"stock":{"$gt":"0"}}

#### por categorias

http://localhost:8080/api/products?query={"category":"Impermeabilizantes"}

#### definiendo el límite

http://localhost:8080/api/products?query={"category":"Impermeabilizantes"}&limit=50

#### ordenando por precio

http://localhost:8080/api/products?query={"category":"Impermeabilizantes"}&sort=asc

## Vistas productos

### Listado de productos

http://localhost:8080/products

#### Detalle de producto

http://localhost:8080/products/:pid

## Vistas carrros

### Listado de carros

http://localhost:8080/carts

#### Detalle de producto

http://localhost:8080/carts/:cid