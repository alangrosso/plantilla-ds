# **Plantilla**

## **Descripción**

Crear una plantilla para proyectos standar de Data Science.

## **Instrucciones**

```s
# Dirigirse a directorio de trabajo en local
cd TU/DIRECTORIO/DE/TRABAJO

# Activar ambiente virtual
source AMBIENTE_VIRTUAL/Scripts/activate

# Instalar (para actualizar fecha automáticamente)
pip install jinja2-time

# Ejecutar desde local
## Clonar repo
git clone https://github.com/alangrosso/plantilla-ds.git
cookiecutter <Ruta de Archivo>
## Ejecutar
cookiecutter .
cookiecutter --verbose .
cookiecutter --verbose --debug-file debug.log .
cookiecutter --verbose --overwrite-if-exists .

# Ejecutar desde git
cookiecutter https://github.com/alangrosso/plantilla-ds.git

# Verificar directorio y archivos creados
```

## **Contacto**

- [alangrosso@gmail.com](mailto:alangrosso@gmail.com)
- [LinkedIn](https://www.linkedin.com/in/alangrosso/)