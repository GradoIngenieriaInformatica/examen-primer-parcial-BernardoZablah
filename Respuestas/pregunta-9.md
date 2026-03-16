db.productos.find(
  {}, 
  { nombre: 1, precio: 1, _id: 0 }
)