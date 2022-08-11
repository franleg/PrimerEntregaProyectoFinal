# Primera Entrega Proyecto Final


## Admin: 

- Query: /?user=admin


## Routes:

### Products
Router base: /api/products

- **GET** (Get all products): '/api/products'
- **GET** (Get product by id): '/api/products/:idProduct'
- **POST** (Add new product): '/api/products' (Disponible para administradores)
- **PUT** (Update product by id): '/api/products/:idProduct' (Disponible para administradores)
- **DELETE** (Delete product by id): '/api/products/:idProduct' (Disponible para administradores)

### Carts
Router base: /api/carts

- **POST** (Add new cart): '/api/carts'
- **DELETE** (Delete cart by id): '/api/carts/:idCart'
- **GET** (Get products in cart by id): '/api/carts/:idCart/products'
- **POST** (Add product in cart by id): '/api/carts/:idCart'
- **DELETE** (Delete product in cart by id): '/api/carts/:idCart/products/:idProduct'


