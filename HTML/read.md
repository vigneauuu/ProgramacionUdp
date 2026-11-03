# Entregas de desarrollo web

Material académico de una tienda, conservado como antecedente de aprendizaje. No hay un despliegue público vigente verificado.

## Primera entrega

[PrimeraEntrega](PrimeraEntrega/) contiene una descripción histórica de la propuesta y un `index.html` vacío. Esta copia no incluye una página estática funcional.

## Segunda entrega

[SegundaEntrega](SegundaEntrega/) incluye un servidor Express, vistas Handlebars, consultas SQL y recursos de una tienda. El código usa PostgreSQL, hashes bcrypt para contraseñas y JWT para autenticación.

Para retomar esa entrega se necesita:

- Una base PostgreSQL propia con el esquema que espera el código.
- `DATABASE_URL` y `JWT_SECRET` en el entorno local.
- Completar las versiones `^x.x.x` que aún aparecen en `package.json` y regenerar el archivo de dependencias.
- Revisar rutas, permisos y vistas antes de ejecutarla o desplegarla.

El servidor declara el puerto 3000. No se ha verificado la ejecución de esta entrega durante la revisión del perfil. Usar bcrypt y JWT no acredita por sí solo la seguridad del sistema.

## Entregas posteriores

- [Entrega3WEB](https://github.com/vigneauuu/Entrega3WEB): API con Express y documentación OpenAPI.
- [Entrega4WEB](https://github.com/vigneauuu/Entrega4WEB): interfaz HTML y JavaScript que consume una API.

Las credenciales antiguas publicadas deben rotarse en el servicio correspondiente. Retirarlas del código no las elimina del historial.
