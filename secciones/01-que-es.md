# 1. Qué es el control de versiones y por qué se usa

Autor: Ian Mora

## 1.1 Definición

Un sistema de control de versiones es una herramienta que guarda el historial de cambios de los archivos de un proyecto.
Cada vez que se confirma un cambio, se guarda una "fotografía" del proyecto en ese momento, con quién lo hizo, cuándo y un mensaje que explica qué cambió.
Gracias a eso se puede volver a cualquier versión anterior, comparar versiones y ver cómo evolucionó el trabajo.
No sirve solo para código: también se puede usar con documentos de texto, como esta guía.
El sistema más usado hoy es **Git**.


## 1.2 El método de las copias con fecha

Antes de usar control de versiones, es común guardar copias de la carpeta con nombres como `proyecto-final`, `proyecto-final-v2` o `proyecto-2026-09-30`.
Parece sencillo, pero tiene varios problemas:

- Las copias ocupan mucho espacio y se acumulan rápido.
- Es fácil confundirse y no saber cuál es la versión correcta o la más reciente.
- No queda registrado qué cambió entre una copia y otra, ni por qué.
- Cuando varias personas trabajan a la vez, es muy difícil juntar los cambios sin perder algo.


## 1.3 Qué resuelve un sistema de control de versiones

- **Historial completo:** cada cambio queda guardado con su autor, su fecha y un mensaje.
- **Volver atrás:** si algo se rompe, se puede regresar a una versión que sí funcionaba.
- **Trabajo en equipo:** varias personas trabajan en el mismo proyecto y luego unen sus cambios.
- **Respaldo:** al subirlo a un repositorio remoto como GitHub, el trabajo no depende de una sola computadora.
- **Orden:** hay una sola carpeta del proyecto en lugar de muchas copias.