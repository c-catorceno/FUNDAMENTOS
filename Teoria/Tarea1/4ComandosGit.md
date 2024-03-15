## 4. COMANDOS
### 4.1 Git init
- Inicializa un repositorio nuevo de Git y comienza a supervisar el directorio existente. Este agrega una subcarpeta oculta dentro del directorio existente que hospeda la estructura de datos interna que se requiere para el control de versiones.
- Este comando crea un nuevo repositorio de Git.

### 4.2 Git config
- Es una función útil que sirve para definir valores de configuración de Git a nivel de un proyecto global o local. Estos niveles de configuración se corresponden con archivos de texto .gitconfig. Al ejecutar git config, se modificará un archivo de texto de configuración.
- Permite configurar y establecer algunos datos o valores (como el nombre y correo electrónico) que luego serán utilizados por otros comandos de Git.

### 4.3 Git add
- Almacena provisionalmente un cambio. Git rastrea los cambios que se hacen a la base de código de un desarrollador, pero es necesario probarlos y tomar una captura de pantalla de ellos para incluirla en el historial del proeycto. Este comando realiza pruebas, la primera parte de este proceso de dos pasos. Cualquier cambio que se pruebe, se convertirá en parte de la siguiente captura de pantalla y también del historial del proyecto. Las pruebas y confirmaciones por separado otorgan a los desarrolladores el control completo sobre el historial y sobre el proyecto sin cambiar la forma en la que codifican y trabajan.
- Se utiliza para subir/añadir un cambio a la rama.

### 4.4 Git commit
- Guarda la instantánea del historial del proyecto y completa el proceso de seguimiento de los cambios. En resumen, una confirmación funciona tal como el tomar una fotografía. Todo lo que se haya almacenado provisionalmente con git add pasará a formar parte de la instantánea con git commit.
- Se utiliza para comfirmar los cambios que añadiste previamente a la rama.

### 4.5 Git push
- Actualiza el repositorio remoto con las confirmaciones realizadas localmente en una rama.
- Este comando lleva los cambios confirmados hacia el repositorio y los sube/guarda.

### 4.6 Git pull
- Actualiza la línea de desarrollo local con actualizaciones de sus contrapartes remotas. Los desarrolladores utilizan este comando si un compañero de equipo hizo confirmaciones en una rama en un repositorio remoto y quieren reflejarlos en su ambiente local.
- Se utiliza para que los cambios que se hayan realizado en el repositorio remoto puedan ser actualizados en un ambiente local de un determinado dispositivo.

### 4.7 Git checkout
- En términos de Git, "checkout" (extraer) es el acto de cambiar entre diferentes versiones de una entidad objetivo. El comando git checkout opera sobre tres entidades distintas: archivos, confirmaciones y ramas. Este comando cambia entre ramas o restaura los archivos del árbol de trabajo.
- Este comando te permite volver a una versión anterior de un commit o momento en el tiempo del historial de las versiones de tu programa.

### 4.8 Git branch
- Muestra las ramas en las que se trabaja localmente.
- Al correr este comando se muestra una lista de los branches/ramas en las que se trabaja localmente.

### 4.9 Github
- GitHub hospeda repositorios de Git y proporciona a los desarrolladores las herramientas para generar un código mejor mediante características de línea de comandos, propuestas (debates en hilo), solicitudes de cambio, revisión de código, etc. Es una plataforma de desarrollo colaborativo que aloja proyectos en la nube utilizando el sistema de control de versiones llamado Git. Ayuda a los desarrolladores a almacenar y administrar el código llevando un registro de cambios.
- Es una plataforma de control de versiones que facilita la administración y almacenamiento de un código en un repositorio a través de un registro de cambios.

### 4.10 Github pages
- GitHub Pages es un servicio de alojamiento de sitio estático que toma archivos HTML, CSS y JavaScript directamente desde un repositorio en GitHub, opcionalmente ejecuta los archivos a través de un proceso de complilación y publica un sitio web.
- Es un servicio que permite a los usuarios de Github a alojar sitios web estáticos de manera gratuita y directamente desde sus repositorios.

### 4.11 Wiki
- Las wikis son parte de los repositorios Git, de manera que puedes hacer cambios localmente y subirlos a tu repositorio mediante un flujo de trabajo de Git. Cada repositorio en GitHub.com viene equipado con una sección para alojar documentación, llamada wiki. Puede utilizar la wiki de su repositorio para compartir contenido extenso sobre su proyecto, como cómo usarlo, cómo lo diseñó o sus principios básicos. Un archivo README indica rápidamente qué puede hacer su proyecto, mientras que puede usar una wiki para proporcionar documentación adicional.
- Es un espacio/sección dentro del repositorio para alojar, crear y editar documentación donde podrás proporcionar información adicional sobre el código y el proyecto en general.