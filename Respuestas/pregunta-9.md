Realizar una consulta que devuelva ​solo el campo nombre de todos los cursos*.
db.cursos.find(
{},
{ nombre:1 }
)
