# Manual de Uso: Proyecto "Catálogo de Películas"

## Índice
1. [Introducción](#introducción)
2. [Requisitos Previos](#requisitos-previos)
3. [Instalación](#instalación)
4. [Compilación y Ejecución](#compilación-y-ejecución)
5. [Uso del Catálogo de Películas](#uso-del-catálogo-de-películas)
6. [Preguntas Frecuentes](#preguntas-frecuentes)

## Introducción
Bienvenido al manual de usuario del proyecto "Catálogo de Películas". Este manual te guiará a través de los pasos necesarios para compilar y ejecutar el proyecto, así como su uso básico.

## Requisitos Previos
Antes de comenzar, asegúrate de tener los siguientes requisitos:
- Python instalado en tu sistema (versión 3.x).
- Una terminal o línea de comandos.
- El código fuente del proyecto.

## Instalación
1. Clona el repositorio del proyecto (si aún no lo has hecho):
   ```sh
   git clone https://github.com/tuusuario/catalogo_pelicula.git
   ```
2. Navega al directorio del proyecto:
   ```sh
   cd proyecto1/catalogo_pelicula/catalogo-peliculas
   ```

## Compilación y Ejecución
1. Abre tu terminal o línea de comandos.
2. Navega al directorio del proyecto (si no lo has hecho):
   ```sh
   cd proyecto1/catalogo_pelicula/catalogo-peliculas
   ```
3. Ejecuta el archivo `catalogo_pelicula.py`:
   ```sh
   python catalogo_pelicula.py
   ```

## Uso del Catálogo de Películas
Una vez que hayas ejecutado el archivo `catalogo_pelicula.py`, podrás interactuar con el catálogo de películas mediante la interfaz gráfica (GUI) proporcionada. Aquí hay una guía rápida sobre las funciones disponibles en el GUI:

### Barra de Menú
- **Inicio**
  - **Crear Registro en DB**: Crea las tablas necesarias en la base de datos.
  - **Eliminar Registro en DB**: Elimina las tablas de la base de datos.
  - **Salir**: Cierra la aplicación.

### Campos de Película
- **Nombre**: Campo para el nombre de la película.
- **Duración**: Campo para la duración de la película.
- **Género**: Campo para el género de la película.

### Botones
- **Nuevo**: Habilita los campos para ingresar una nueva película.
- **Guardar**: Guarda la nueva película en la base de datos.
- **Cancelar**: Deshabilita los campos y limpia los datos ingresados.
- **Editar**: Permite editar la película seleccionada en la tabla.
- **Eliminar**: Elimina la película seleccionada de la base de datos.

### Tabla de Películas
La tabla muestra las películas guardadas en la base de datos con las columnas de ID, Nombre, Duración y Género. Puedes seleccionar una película para editar o eliminar utilizando los botones correspondientes.

## Preguntas Frecuentes
1. **¿Cómo añado una nueva película al catálogo?**
   - Haz clic en "Nuevo", completa los campos "Nombre", "Duración" y "Género", y luego haz clic en "Guardar".

2. **¿Cómo elimino una película del catálogo?**
   - Selecciona la película en la tabla y haz clic en "Eliminar".