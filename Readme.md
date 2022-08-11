API (en desarrollo) realizada en Django para un Ecommerce tradicional. Los endpoints disponibles hasta el momento son:
- products
- collections

### Endpoint PRODUCTS

Usando este Endpoint se podrá acceder a la lista de productos así como a los detalles de un producto en específico. También se podrán crear nuevos productos y eliminar productos actuales. 

Realizando un *GET* a BASE_URL/store/products/1 obtendremos los detalles del producto con id = 1

{
  "id": 1,
  "title": "Bread Ww Cluster",
  "description": "mus vivamus vestibulum sagittis sapien cum sociis natoque penatibus et magnis dis parturient montes nascetur ridiculus",
  "slug": "-",
  "unit_price": 4,
  "inventory": 11,
  "price_with_tax": 4.4,
  "collection": 6
}

### Endpoint COLLECTIONS

Usando este Endpoint se podrá acceder a la lista de las coecciones así como a los detalles de una colección en específico. También se podrán crear nuevas collecciones y eliminar las actuales. 

Realizando un *GET* a BASE_URL/store/collections/6 obtendremos los detalles de la colección con id = 6

{
  "id": 6,
  "title": "Pets",
  "products_count": 238
}
