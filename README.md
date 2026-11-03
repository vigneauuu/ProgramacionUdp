# Programación UDP

Recopilación de ejercicios y entregas académicas de mi formación en programación. Cada carpeta es una experiencia independiente; no constituye una sola aplicación.

## Contenido

| Carpeta | Contenido |
| --- | --- |
| [C++](C++/) | Ejercicios de controles, solemnes y examen. |
| [Java](Java/) | Ordenamiento, árboles binarios y AVL, colas de prioridad y heaps. |
| [HTML](HTML/) | Antecedentes de entregas web y una tienda con Express y Handlebars. |

Los ejemplos se conservan como material de aprendizaje. No hay un sistema de compilación ni una suite de pruebas común para todo el repositorio.

## Entregas web

[HTML/read.md](HTML/read.md) explica el estado de las carpetas. La primera entrega conserva documentación, pero su `index.html` está vacío. La segunda requiere PostgreSQL, `DATABASE_URL` y `JWT_SECRET` definidos localmente; su manifiesto aún tiene versiones de dependencias incompletas.

La API y la interfaz de entregas posteriores están en [Entrega3WEB](https://github.com/vigneauuu/Entrega3WEB) y [Entrega4WEB](https://github.com/vigneauuu/Entrega4WEB).

## Credenciales

La conexión a PostgreSQL y una clave de firma antiguas estuvieron publicadas en el historial. Deben considerarse comprometidas: si siguen en uso, cambia la contraseña del rol de la base de datos y la clave JWT en el entorno que ejecute la aplicación. No agregues credenciales ni archivos `.env` a Git.
