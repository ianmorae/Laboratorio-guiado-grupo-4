# 2. Los comandos esenciales de Git

Autor: Mariana Paniagua Porras

## 2.1 Las tres zonas 

**-Directorio de trabajo:** Es la carpeta donde se encuentran los archivos del proyecto y donde realizamos cambios. Por ejemplo, cuando modificamos un archivo HTML, Java o CSS, estamos trabajando en esta zona.

**-Área de preparación (Staging Area):** Es el espacio donde se colocan los cambios que queremos incluir en el próximo commit. Para agregar un archivo a esta zona se utiliza el comando git add.

**-Repositorio:** Es el lugar donde Git guarda de manera permanente los cambios registrados mediante commits. El repositorio puede estar de forma local en nuestra computadora y también puede estar conectado a un repositorio remoto como GitHub.

## 2.2 Configuración inicial

**Configurar el nombre**
git config --global user.name "Mariana Paniagua Porras"

Este comando permite establecer el nombre del usuario que aparecerá en los commits.

**Configurar el correo**
git config --global user.email "correo@example.com"

Este comando permite establecer el correo electrónico que Git asociará con los commits realizados.

**Consultar la configuración**
git config --list

Este comando permite revisar las configuraciones que tiene Git actualmente.