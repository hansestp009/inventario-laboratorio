# Instrucciones para agentes de IA

## Idioma y convenciones

- Utiliza Python 3.
- Escribe en español el código nuevo, los nombres de variables y funciones, y los mensajes del programa.
- Usa `snake_case` para variables, funciones y nombres de archivos Python; usa minúsculas para las carpetas.
- Las constantes pueden usar `MAYUSCULAS_CON_GUION_BAJO`.
- Incluye un docstring breve que describa el propósito de cada función.

## Organización

- `app.py` contiene el punto de entrada y el menú principal.
- `src/inventario.py` contiene la lógica relacionada con los equipos.
- `src/mantenimiento.py` contiene las funciones relacionadas con el mantenimiento.
- `data/equipos.json` contiene los datos persistentes.
- No coloques la lógica principal del inventario directamente en `app.py`.
- No cambies la estructura de carpetas sin justificación.

## Datos

- Almacena los equipos en formato JSON.
- Conserva en cada equipo los campos `codigo`, `nombre`, `tipo`, `estado` y `ubicacion`.
- Asegura que el código de cada equipo sea único.
- No cambies el formato de almacenamiento sin actualizar primero la documentación del proyecto.

## Cambios

- Revisa `README.md`, este archivo y la estructura actual antes de modificar el proyecto.
- Identifica los archivos relacionados y aplica únicamente los cambios necesarios para la tarea solicitada.
- Reutiliza funciones existentes y evita modificar funcionalidades no relacionadas.
- Mantén la compatibilidad con las funciones existentes y no elimines código funcional sin necesidad.
- No introduzcas librerías externas, SQLite ni otra base de datos.
- Si un cambio modifica el comportamiento o el formato de los datos, documenta el cambio y valida las funcionalidades afectadas.
