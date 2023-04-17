# ELT-Project

Requisitos previos:
- Instalar Docker
- NodeJS

<br>

El proyecto se debe de instalar de la siguiente manera:

```bash
git clone https://github.com/ItsArthur1/ELT-Project.git

```

<br>

En este caso la carpeta que tiene el repositorio es un link, por lo cual la pueden eliminar y hacer el siguiente paso.

Ahora deberás clonar el repositorio de Redash en tu carpeta principal de la siguiente manera:

````bash

git clone https://github.com/getredash/redash.git


````

Para poder ejecutar Airflow de manera correcta, deberás ejecutar el siguiente comando:

```bash

docker compose up airflow-init

```

<br>

Para poder ejecutar el proyecto completo, deberas ejecutar el siguiente comando:

```bash
docker compose up airflow-init
```


<br>

Para poder ejecutar redash es necesario ejecutar los siguientes comandos en una terminal nueva:

```bash
cd redash
docker compose up

```
