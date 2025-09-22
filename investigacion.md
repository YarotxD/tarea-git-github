"# Investigaci�n sobre Git y GitHub"



\# Investigaci�n sobre Git y GitHub



\## 1. �Qu� es Git y para qu� se utiliza?

Git es un sistema de control de versiones distribuido que permite llevar un registro de los cambios realizados en los archivos de un proyecto. Se utiliza para coordinar el trabajo en equipo, facilitar la colaboraci�n entre desarrolladores y mantener un historial de versiones que permite recuperar estados anteriores.



\## 2. �Qu� diferencia hay entre Git y GitHub?

\- \*\*Git\*\*: Es la herramienta de control de versiones que funciona de manera local en la computadora.

\- \*\*GitHub\*\*: Es una plataforma en l�nea que permite almacenar repositorios Git en la nube y facilita el trabajo colaborativo, la gesti�n de proyectos y la integraci�n con otras herramientas.



\## 3. �Qu� es un repositorio?

Un repositorio es el espacio donde se almacenan todos los archivos de un proyecto junto con el historial de cambios. Puede estar en la computadora (local) o en una plataforma como GitHub (remoto).



\## 4. �Qu� significa hacer un commit en Git?

Un commit es como una �fotograf�a� del proyecto en un momento espec�fico. Permite guardar los cambios con un mensaje descriptivo para identificar qu� se modific�.



\## 5. Explicaci�n de comandos b�sicos en Git



\- `git config --local user.name "GitHub user name"`

� Configura el nombre de usuario que aparecer� en los commits del repositorio actual.



\- `git config --local user.email "GitHub email"`

� Configura el correo electr�nico asociado al usuario en el repositorio actual.



\- `git init`

� Inicializa un repositorio Git en una carpeta local.



\- `git add`

� A�ade archivos al �rea de preparaci�n (staging area) antes de hacer un commit.



\- `git commit`

� Registra de manera definitiva los cambios a�adidos con `git add`.



\- `git push`

� Env�a los commits locales al repositorio remoto en GitHub.



\- `git clone`

� Descarga una copia de un repositorio remoto a la computadora local.



\- `git init --initial-branch=main`

� Crea un nuevo repositorio inicializando la rama principal como `main`.



\- `git remote add origin <URL>`

� Vincula el repositorio local con un repositorio remoto en GitHub.



\- `git add .`

� A�ade todos los archivos modificados o nuevos al �rea de preparaci�n.



\- `git commit -m "Initial commit"`

� Crea el primer commit en el repositorio con un mensaje que describe la acci�n.



\- `git push --set-upstream origin main`

� Sube los cambios de la rama principal local (`main`) al repositorio remoto y establece la relaci�n de seguimiento entre ambas ramas.



\## 6. �Qu� es un archivo README.md y por qu� es importante?

El archivo `README.md` es un documento escrito en formato Markdown que normalmente se encuentra en la ra�z de un repositorio. Es importante porque:

\- Describe el prop�sito del proyecto.

\- Explica c�mo usarlo o instalarlo.

\- Sirve como carta de presentaci�n para que otros entiendan r�pidamente de qu� trata el repositorio.

