db.cursos.Aggregation([
  {
    $group: {
      _id= "$nivel",
      totalCreditos: {$sum = "$creditos"}
    }
  }
])
