# Sistema de inventario de equipos

Proyecto para registrar y consultar equipos, sus estados y ubicaciones, además de organizar la información relacionada con su mantenimiento.

## Estructura prevista

```text
.
├── app.py
├── data/
│   └── equipos.json
└── src/
    ├── inventario.py
    └── mantenimiento.py
```

- `app.py`: punto de entrada y menú principal.
- `src/inventario.py`: lógica para gestionar los equipos.
- `src/mantenimiento.py`: funciones relacionadas con el mantenimiento.
- `data/equipos.json`: almacenamiento persistente de los equipos.

Esta estructura describe la organización prevista; los archivos se incorporarán conforme se implemente el proyecto.

## Datos de los equipos

Cada equipo debe conservar los campos `codigo`, `nombre`, `tipo`, `estado` y `ubicacion`. El campo `codigo` identifica al equipo y debe ser único. Los datos se almacenan en formato JSON.

## Ejecución

Cuando esté implementado el punto de entrada, el programa se ejecutará desde la carpeta del proyecto con:

```bash
python app.py
```

## Requisitos

- Python 3.
- Solo se permite utilizar la biblioteca estándar de Python; no se deben agregar dependencias externas.
