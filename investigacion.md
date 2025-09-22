"# Investigación sobre Git y GitHub"



\# Investigación sobre Git y GitHub



\## 1. ¿Qué es Git y para qué se utiliza?

Git es un sistema de control de versiones distribuido que permite llevar un registro de los cambios realizados en los archivos de un proyecto. Se utiliza para coordinar el trabajo en equipo, facilitar la colaboración entre desarrolladores y mantener un historial de versiones que permite recuperar estados anteriores.



\## 2. ¿Qué diferencia hay entre Git y GitHub?

\- \*\*Git\*\*: Es la herramienta de control de versiones que funciona de manera local en la computadora.

\- \*\*GitHub\*\*: Es una plataforma en línea que permite almacenar repositorios Git en la nube y facilita el trabajo colaborativo, la gestión de proyectos y la integración con otras herramientas.



\## 3. ¿Qué es un repositorio?

Un repositorio es el espacio donde se almacenan todos los archivos de un proyecto junto con el historial de cambios. Puede estar en la computadora (local) o en una plataforma como GitHub (remoto).



\## 4. ¿Qué significa hacer un commit en Git?

Un commit es como una “fotografía” del proyecto en un momento específico. Permite guardar los cambios con un mensaje descriptivo para identificar qué se modificó.



\## 5. Explicación de comandos básicos en Git



\- `git config --local user.name "GitHub user name"`

  Configura el nombre de usuario que aparecerá en los commits del repositorio actual.



\- `git config --local user.email "GitHub email"`

  Configura el correo electrónico asociado al usuario en el repositorio actual.



\- `git init`

  Inicializa un repositorio Git en una carpeta local.



\- `git add`

  Añade archivos al área de preparación (staging area) antes de hacer un commit.



\- `git commit`

  Registra de manera definitiva los cambios añadidos con `git add`.



\- `git push`

  Envía los commits locales al repositorio remoto en GitHub.



\- `git clone`

  Descarga una copia de un repositorio remoto a la computadora local.



\- `git init --initial-branch=main`

  Crea un nuevo repositorio inicializando la rama principal como `main`.



\- `git remote add origin <URL>`

  Vincula el repositorio local con un repositorio remoto en GitHub.



\- `git add .`

  Añade todos los archivos modificados o nuevos al área de preparación.



\- `git commit -m "Initial commit"`

  Crea el primer commit en el repositorio con un mensaje que describe la acción.



\- `git push --set-upstream origin main`

  Sube los cambios de la rama principal local (`main`) al repositorio remoto y establece la relación de seguimiento entre ambas ramas.



\## 6. ¿Qué es un archivo README.md y por qué es importante?

El archivo `README.md` es un documento escrito en formato Markdown que normalmente se encuentra en la raíz de un repositorio. Es importante porque:

\- Describe el propósito del proyecto.

\- Explica cómo usarlo o instalarlo.

\- Sirve como carta de presentación para que otros entiendan rápidamente de qué trata el repositorio.

