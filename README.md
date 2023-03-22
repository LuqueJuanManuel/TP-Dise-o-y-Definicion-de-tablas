# TP - DISEÑO Y DEFINICIÓN DE TABLAS.

## Desafio:
- Diseñar una base de datos que contengan: que tengan tablas, campos y relaciones, determinar entidades principales que se desprendan de los requisitos, pueden ser usuarios, productos, etc.
### Primer escenario: Crear la base de Datos de Playground: 
     - Queremos tener usuarios, los usuarios tendrán nombre, apellido, email, contraseña y categoría. Los usuarios podrán tener categoría de estudiantes, docentes, editores o administradores.
     - Lo siguiente que queremos es poder almacenar los cursos, que tendrán un título, una descripción, una imagen, una fecha de inicio, una fecha de finalización y un cupo máximo.
     - Los cursos tendrán unidades (para organizar el contenido) que tendrán un título, una descripción y una fecha de inicio.
     - Los usuarios (de cualquier tipo) podrán estar asociados a cursos.
     - Las unidades contendrán clases que también tendrán un título, una descripción, una fecha de inicio, y una marca de visibilidad (si el bloque está visible o no).
     - Las clases contendrán bloques. Los bloques tendrán un título y una marca de visibilidad. Los bloques podrán ser de diferente tipo: texto, video, presentación, PDF o archivo.
     - Los bloques también tendrán que poder guardar el contenido, sea texto o una URL, en caso de que el tipo sea video, presentación, PDF o archivo.

### Segundo escenario: Bazar-Digital:
     - En charlas con los dueños entendemos que el bazar va a vender vajilla, juguetes y artículos de jardín, y van a tener empleados comunes, un coordinador, empleados de mostrador y repositores.
     - Todos los artículos tendrán nombre, precio, descripción, stock y aclararán si son para usoprofesional o no.
     - Todos los empleados tendrán nombre, apellido, dni, sueldo y un rol.


## Trabajo realizado con Diagrams.net