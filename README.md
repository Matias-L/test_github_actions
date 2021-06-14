# Introduccion a GitHub Actions
![Actions](https://github.com/Matias-L/test_github_actions/actions/workflows/actions.yml/badge.svg)

Pequeño proyecto para introducirme en GitHub Actions.
Consta de una imagen de NginX con un index.html simple.
Ante cada push se dispara un workflow que consiste de un solo job. El mismo construye la imagen dockerizada y lo sube 
a dockerhub con la etiqueta de la rama main.
Luego, se puede desplegar la aplicación mediante docker-compose con el archivo incluido.  