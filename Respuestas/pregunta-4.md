db.productos.updateOne(
  { nombre: "Tablet X" }, 
  { $set: { stock: 35 } } 
)