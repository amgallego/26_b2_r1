## 1. Título de actividad
Actividad 1 - Configuración y Pruebas de Proyecto Spring Boot

## Estudiante
-Ana Marcela Gallego Gomez

## 2. Enlace a la instancia de base de datos

La instancia de Prisma.io no es pública.
Se adjunta evidencia mediante captura de pantalla de la configuración.

![Base de datos creada](imagenes/base-datos-prisma.png)

## 3. Configuración base de datos en prisma
![Configuración Prisma](imagenes/url-prisma.png)

## 4. Log de la consola de Spring Boot conexión y ejecución del proyecto

Se evidencia que la aplicación inicia correctamente y establece una conexión exitosa con la base de datos PostgreSQL en Prisma.io.
![Log de Conexión y Ejecución](imagenes/log-ejecucion.png)

## 5. Evidencias de las pruebas de la API (CRUD)

## POST
Evidencia de la creación de al menos 3 estudiantes diferentes
![Método POST](imagenes/estudiante-2.png)
![Método POST](imagenes/estudiante-3.png)
![Método POST](imagenes/estudiante-4.png)

# GET ALL
Se muestran todos los estudiantes
![Método GET](imagenes/estudiantes-creados.png)

# GET by ID
Muestra un estudiante específico por su ID
![Método GET](imagenes/estudiante-ID.png)

# GET by email
Muestra un estudiante específico por su correo electrónico
![Método GET](imagenes/estudiante-correo.png)

# PUT
Se actualiza la información de un estudiante
![Método PUT](imagenes/estudiante-actualizado.png)

# DELETE
Se elimina a un estudiante
![Método DELETE](imagenes/estudiante-eliminado.png)

## 6. Captura de pantalla del resultado de las pruebas internas

Se ejecutó el comando `./mvnw test`, verificando que todas las pruebas unitarias y de integración pasaron satisfactoriamente sin errores.

![Resultado de Pruebas Internas](imagenes/prueba-interna.png)