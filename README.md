# eepp
La solucion esta comprendida de:
Employees.Api = encargada de las accion(peticiones y respuestas)
Employees.Core = maneja el modelo e interfaces
Employees.Infrastructure =  maneja el repositorio de datos

EmployeesMVC = es el proyecto web que consume la api y si se da click en el boton traera todos los datos que la api responde,
               si se ingresa un codigo de empleado, solo presentara la info del codigo solicitado
               si e ingresa un codigo que no es valido el sistema no mostrara ninguna info
       
 La solucion esta configurada para que ejecute los proyectos 
