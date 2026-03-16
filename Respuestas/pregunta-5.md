db.productos.aggregate([
  {
    $group: {
      _id: "$categoria",
      totalStock: { $sum: "$stock" }
    }
  }
])