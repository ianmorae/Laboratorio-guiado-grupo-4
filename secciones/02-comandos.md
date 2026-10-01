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

## 2.3 El ciclo de trabajo

**-git status:** El comando git status se utiliza para revisar el estado actual del proyecto. Permite saber qué archivos fueron modificados, cuáles están pendientes de agregar y cuáles ya están preparados para realizar un commit.

**Ejemplo:**

Si modificamos el archivo index.html, podemos ejecutar: **git status**.

Git nos indicará que el archivo index.html fue modificado y que todavía no ha sido agregado al área de preparación.

**-git add:** El comando git add se utiliza para agregar los cambios al área de preparación (staging area). Esto indica a Git qué cambios queremos incluir en el próximo commit.

**Ejemplo:**

Si queremos agregar todos los archivos modificados: **git add .**

En este caso, el punto . indica que se agregarán todos los cambios del proyecto. También podemos agregar solamente un archivo: git add index.html. 
Esto prepara únicamente el archivo index.html para el próximo commit.

**-git commit:** El comando git commit se utiliza para guardar los cambios que fueron agregados al área de preparación. Cada commit representa un registro de los cambios realizados en el proyecto y lleva un mensaje que permite identificarlo.

**Ejemplo:**

Después de utilizar git add, podemos guardar los cambios con: **git commit -m "Actualiza la página principal"**.

En este ejemplo, "Actualiza la página principal" es el mensaje que describe el cambio realizado.

**-git push:** El comando git push se utiliza para enviar los commits del repositorio local al repositorio remoto, como GitHub.

**Ejemplo:**

Después de realizar el commit, podemos enviar los cambios a GitHub mediante: **git push**

De esta manera, el commit que estaba guardado en nuestra computadora se envía al repositorio remoto.

## 2.4 Consultar el historial

**-git log:** El comando git log sirve para consultar el historial de cambios de un proyecto. Permite ver los commits que se han realizado y conocer información como el autor, la fecha, el mensaje y el identificador de cada commit.

**-Identificador de un commit:** El identificador de un commit es un código único que Git asigna a cada cambio guardado. Sirve para diferenciar un commit de los demás y localizar un cambio específico dentro del historial del proyecto.