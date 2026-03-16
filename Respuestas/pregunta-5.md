db.cursos.Aggregation([
  {
    $group: {
      __id: "$nivel",
      totalCreditos: {$sum : "$creditos"}
    }
  }
])
