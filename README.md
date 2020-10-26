# Introducción a PLN

Este repositorio contiene todo el material para el módulo de PLN, para la diplomatura de ciencias de datos de la UTN FRC.

La materia hace uso de las siguientes tecnologías:

* Python 3.5 o superior
* Jupyter notebook
* Git
* Virtualenvwrapper **

**Como recomendación, se sugiere el uso de estas herramienta para mantener un orden de las librerías en su computadora sin comprometer las ya existentes.

## Instalación

1- Para sistemas basados en Unix:

```
sudo apt-get install git python-pip python3 virtualenvwrapper
```

2- Preparar el entorno de trabajo con virtualenv

```
mkvirtualenv -p $(which python3)  nombre_del_entorno_a_elegir
```

2.1- Activar/desactivar el entorno

```
workon nombre_elegido
```

Desactivar el entorno virtual

```
deactivate
```

3- Obtener el código

```
git clone https://github.com/nestornav/nlp-intro.git
```

Sí núnca usaron Git + Github en sus vidas, les dejo un video que espero les resulte útil [acá](https://youtu.be/3XlZWpLwvvo).

## Estructura del repositorio

├── class_x/         # El contenido para cada clase. Presentaciones, notebooks, etc.
├── work/            # Listado de los trabajos solicitados
    ├──data/         # Dataset necesario para las prácticas
