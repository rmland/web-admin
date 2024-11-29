## Web admin
Pizarra informativa del curso


```sh
cd ruta\webadmin
poetry init

poetry add reflex
poetry install
```


```sh
cd ruta\webadmin
poetry shell
reflex run
```

Iniciar el versionamiento de la base de datos
```sh
reflex db init

reflex db makemigrations --message 'Actualizacion 01'
reflex db migrate
```

No hay usuarios, por tanto se debe crear uno ingresando en:
- http://localhost:3000/signup

Ejemplo:
- admin/pass
- profe01/pass
- profe02/pass
- profe03/pass
- alum01/pass
- alum02/pass
- alum03/pass
- alum04/pass


## Bibliografía

Reflex Examples
- https://github.com/reflex-dev/reflex-examples/tree/main

SQLModel
- https://reflex.dev/docs/database/overview/
- https://sqlmodel.tiangolo.com


Many to Many - Intro
- https://sqlmodel.tiangolo.com/tutorial/many-to-many/
- https://sqlmodel.tiangolo.com/tutorial/many-to-many/create-models-with-link/


Reflex: La Mejor Alternativa Secreta del Desarrollo Web con Python, Guía Definitiva en Español
- https://medium.com/@fnracotorres/reflex-la-mejor-alternativa-secreta-del-desarrollo-web-con-python-gu%C3%ADa-definitiva-en-espa%C3%B1ol-4e982b0d7a41

Diseño de un marco web Pure Python.
- https://cornejomultyservicios.com/Designing_a_Pure_Python_Web_Framework.html