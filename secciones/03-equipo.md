# 3. Trabajo en equipo con GitHub

Autor: Paulo Josue Solano Ramirez

## 3.1 Git y GitHub no son lo mismo

Git es el sistema de control de versiones en sí: un programa que corre en la computadora y lleva el historial de cambios de un proyecto sin necesitar internet. GitHub es un servicio en la nube que aloja repositorios de Git y le agrega funciones extra, como una interfaz web, control de acceso por colaboradores e issues. Se puede usar Git sin GitHub, guardando el historial solo en la computadora, pero no se puede usar GitHub sin Git, porque GitHub depende de ese sistema para versionar los archivos. Tambien existen otras plataformas que cumplen el mismo papel que GitHub, como GitLab o Bitbucket, lo que confirma que son cosas separadas: una es la herramienta y la otra es dónde se aloja el trabajo.

## 3.2 Repositorio local y remoto

El repositorio local es la copia del proyecto que vive en la computadora de cada persona, con su propia carpeta .git y su propio historial de commits. El repositorio remoto es la copia que vive en un servidor, en este caso GitHub, y sirve de punto central para que todo el equipo comparta el mismo trabajo. Los cambios no pasan de forma automática entre uno y otro: hay que subirlos con git push para que lo local llegue al remoto, y traerlos con git pull para que lo remoto llegue a lo local. Pueden existir varios repositorios locales, uno por integrante, conectados al mismo repositorio remoto, que es justamente el escenario de este laboratorio. Si alguien borra su copia local, el proyecto no se pierde porque el remoto sigue teniendo el historial completo.