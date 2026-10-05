# 🎓 GestorAlumnos

Aplicación para gestionar el alta, consulta y seguimiento de alumnos de un centro educativo.

## Características

- Alta, edición y baja de alumnos
- Búsqueda por nombre, curso o DNI
- Gestión de asignaturas y matrículas
- Registro de notas y cálculo de medias
- Exportación de listados a CSV

## Requisitos

- JDK 17 o superior
- MySQL 8 (o la base de datos que uses)
- Maven 3.9+

## Instalación

1. Clona el repositorio:
```bash
   git clone https://github.com/usuario/gestor-alumnos.git
```
2. Configura la conexión a la base de datos en `config.properties`.
3. Compila y ejecuta:
```bash
   mvn clean package
   java -jar target/gestor-alumnos.jar
```

## Uso

Al iniciar la aplicación, accede al menú principal y elige la opción deseada
(alumnos, asignaturas, notas). Todos los cambios se guardan en la base de datos.

## Estructura del proyecto
