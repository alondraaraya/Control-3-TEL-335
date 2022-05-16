## Control-3-TEL-335

#Probar Rutas en Backend.

1)Entrar en carpeta BACKEND
2) npm install
3) npm install axios
3) npm run start:dev
4) Probar Rutas en Postman
	1. POST: http://localhost:3001/carrito/productos    (agregar productos al carrito)
	2. GET:  http://localhost:3001/carrito/productos    (obtener todos los productos dentro de un carrito)
	3. GET:  http://localhost:3001/productos/marca/:marca  (Obtener productos por marca)
	4. GET:	 http://localhost:3001/productos/id/:id/       (Obtener producto por id)
	5. GET:  http://localhost:3001/productos/               (Obtener todos los productos)
	6. GET.  http://localhost:3001/carrito/productos2/:parametro/  (obtener producto por id o marca)
