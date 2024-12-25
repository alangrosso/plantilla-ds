# **Plantilla**

## **Descripción**

Crear una plantilla para proyectos standar de Data Science.

## **Instrucciones**

```s
# Activar ambiente virtual
source AMBIENTE_VIRTUAL/Scripts/activate

# Dirigirse a directorio de trabajo en local
cd TU/DIRECTORIO/DE/TRABAJO

# Verificar librerias y paquetes necesarios para el proyecto
pip list | grep NOMBRE_LIBRERIA

# Para actualizar fecha automáticamente
pip install jinja2-time

# Ejecutar desde repo
## Desde dev
cookiecutter https://github.com/alangrosso/plantilla-ds --checkout dev
## Desde main
cookiecutter https://github.com/alangrosso/plantilla-ds.git

# Ejecutar desde local
## Clonar repo
git clone https://github.com/alangrosso/plantilla-ds.git
cookiecutter <Ruta de Archivo>
## Ejecutar
cookiecutter .
cookiecutter --verbose .
cookiecutter --verbose --debug-file debug.log .
cookiecutter --verbose --overwrite-if-exists .

# Verificar directorio y archivos creados
# Modificar de acuerdo a caso de uso
```

## **Contacto**

- [alangrosso@gmail.com](mailto:alangrosso@gmail.com)
- [LinkedIn](https://www.linkedin.com/in/alangrosso/)