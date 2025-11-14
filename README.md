# Odin project, aprendizaje.

Aquí se **plasmará el conocimiento** adquirido durante el curso de **_Odin project_**, el objetivo es que a medida que avance en el curso, consigne lo aprendido, lección tras lección, asegurando de esta forma un **aprendizaje** más efectivo, sin lagunas u olvidos de información relevante.

## Git

Git es un software utilizado para el control de versiones descentralizadas, donde el objetivo, es llevar una lista de cambios realizados y visibles para todo el equipo de trabajo, garantizando de esta manera la trazabilidad y escalabilidad del código, así como su disponibilidad y acceso, sin depender de maquinas especificas.

### Básicos de Git

1. `git config`: **permite modificar la configuración del git**
    - ***Tags***
        - `--global`: **Modifica aspectos globales de la configuración**

1. `git get`: **Permite ver la configuración del git**
    - ***Tags***
        - `--config user.name`: **Nombre de usuario**
        - `--config user.email`: **correo**

1. `git clone [repository]`: **Permite clonar un repositorio de git en tu maquina local.**

1. `git status`: **Permite ver el estado de los archivos dentro del repositorio**

1. `git log`: **Permite ver el historial de cambios realizados al repositorio**

1. `git add [Nombre de archivo(s)]`: **adicionar los archivos que se deseen agregar al commit**

1. `git commit "message"`: **Captura una snapshot de los cambios efectuados al proyecto**
    - ***Tags***
        - `-m`: **Crea un commit con el mensaje especificado**
        - `-a`: **Confirma una snapshot de todos los cambios en el directorio de trabajo**
        - `-am`: **Combina las etiquetas antes mencionadas**
        - `--amend`: **En lugar de crear una nueva confirmación, se modifica la creada con anterioridad**
1. `git push`: **Realiza el envío de la snapshot al repositorio**

## Github

Es un repositorio online que recopila millones de proyectos de toda indole.