﻿# Trabajo Profesional

Este trabajo consiste en realizar una excursora de plastico, principalmente del polimero PLA que es el mas usado en las impresoras 3D. Dicho polimero empiza a ser moldiable en una temperatura entre los *80 ºC* a *110 ºC*, para realizarlo vamos a realizar un control de temperatura sobre el extrusor para mantener una temperatura en ese rango. Vamos a considerar que el plastico ingresa en trozos iguales y de un tamaño entre *1.5 mm* a *2.5 mm* **(Le tire para tirar)**. 

## Distribución del git (carpetas):

    - **Archivo README.md**: es lo que lees en el git, siempre que agregues alguna informacion intenta de agregarlo aca.
    - **Bibliografia**: carpeta donde poner toda la informacion que usamos, es importante agregar todo lo que usamos hasta los link de iterner, despues en el informe final seguro haya que agregarlo, creare un archivo de *link.txt* para todo el tema de los links, si se puede agregar una mini descripcion.
    - **Codigo**: carpeta donde va el codigo
        - **Codigo antigua**: el codigo de embebidos, no hay que tocarlo
        - **Codigo actual**: no se si agregar una carpeta o dejar todo adentro de codigo pero a fin y a cabo seria el codigo que vamos haciendo.
    - **Modelo**: carpeta para agregar la mecanica del problema, seguro van haber varios modelos entonces dividimos en diferentes carpetas (aca poner diseño 3d en formato stl para poder imprimirlo en una impresora 3D.)
        - **Modelo1**: tiene el modelo 1, lo mejor es hacer una mini descripcion del modelo para no ser genericos
        - **...**
        -**Modelo N**: ultimo modelo

## Procedimiento de github:

    **IMPORTANTE**: vas a tener que intalar el gitbash, podes descargar la terminar bash desde la pagina oficial: "https://git-scm.com/downloads" pero si usas python podes descargar anaconda y te lo instala automaticamente con otros recursos pero si no lo usas descarga directamente del link. Luego para usarlo desde el powershell me parece (no estoy seguro) vas a tener que agregar el git al path desde variables de entorno.

    **OBS:** puede ser que te pida el usario y la contraseña para hacer el procedimiento, si es asi seguro en la terminal te lo dice. Y todos los comandos que escribo a continuacion van siempre en la ruta del repo desde la terminal. 

    -1. Primero vas a tener que clonar el repo, te copias la direccion https que se encuentra en el boton "clone" o copias esto: "https://github.com/Pabloale96/Tp-Prof.git" (sin comillas)
    -2. abris una terminal en la carpeta donde queres que se encuentra el repo y ejecutas "git clone https://github.com/Pabloale96/Tp-Prof.git", esto te creo un repo local.

    -3. Procesidimiento para cambiar el repo:
        -3.1 Antes de empezar a trabajar sobre algo siempre tenes que traer los ultimos cambios del repo haciendo un "git pull" para no pisar sobre el trabajo que otro haga. En este comando te puede saltar un error al merge (no se pudo automerge los archivos que se encuentra en el repo y los que se encuentra en el repo local o falta hacer el merged, este problema te lo explico mas adelante)
        -3.2 Si el pull salio bien, entonces ya podes trabajar sobre tu repo local (todos lo que hagas no modifica al repo entonces trabaja sin miedo), cuando termines todo lo que querias hacer, tenes que subir los cambios, para eso haces un "git add ." (te agrega todos los archivos que modificaste) si solo queres agregar una cantidad x de archivos podes usar "git add "rutaArchivo1" "rutaArchivo2" "rutaArchivo3" ... "rutaArchivox""
        -3.3 Una vez agregados todos los archivos que queres subir, tenes que hacer un commit para eso se ejecuta "git commit" que te va a abrir un editor de texto para poder escribir un mensaje para dar mas informacion de lo que hiciste, una forma para evitar esto podes ejecutar "git commit -m "mensaje"" que automaticamente te escribe el mensaje, las comillas del mensaje es importante. Un ejemplo serie git commit -m "Hago un primer commit para subir los cambios sobre el README",  la idea es que el mensaje sea representativo para saber que cambios hiciste.
        -3.4 Por ultimo, hay que subir los cambios, haciendo un "git push" (aca te puede preguntar contraseña e usuario) y sube todo al repo de github.
    
### Algunos comando utiles:
    - "git status" te dice que cambios faltan agregar al repo (creo que tambien te dice si te falta un cambio que esta en el repo pero no esta en tu repo local, es decir, te falta hacer el pull)
    - Tambien hay comando para hacer ramas pero no los domino del todo, esta bueno tener una rama secundaria para evitar cambiar directamente el repo pero no es necesario en este proytecto

# Overleaf:
    -link : https://www.overleaf.com/project/60784f0907656d9d9f60732d
