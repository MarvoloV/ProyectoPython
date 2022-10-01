# Ventas aleatorias con Python

Este repositorio contiene la implementación del Proyecto propuesto "Aplicación de ventas estimadas aleatorias de vuelos comerciales".

- El archivo app.py, contiene la implementación del ejercicio desarrollado con una programación orientada a objetos.

## Paquete Mypy

- Creamos el entorno virtual para nuestro proyecto

```bash
python3 -m venv venv
```

- Activamos nuestro entorno virtual

  - En windows

  ```bash
  source venv/Scripts/activate
  ```

  - En MacOS

  ```bash
  source venv/bin/activate
  ```

- Instalamos el paquete mypy

```bash
pip install mypy
```

- Ejecutar mypy para la revision de tipado

```bash
mypy app.py --check-untyped-defs --ignore-missing-imports
```

- Ejecutamos python para revisar los resultados del proyecto.

```bash
python3 app.py
```
