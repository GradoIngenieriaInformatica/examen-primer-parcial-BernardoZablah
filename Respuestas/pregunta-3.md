db.productos.find(
  { categoria: "electronica" }, 
  { nombre: 1, precio: 1, _id: 0 } 
)