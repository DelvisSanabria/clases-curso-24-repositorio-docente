## Ejercicio en Clase: Construyendo el Futuro de Amazon (en GitHub) - Versión 2.0

¡Bienvenidos, futuros desarrolladores de Amazon! En este ejercicio, simularemos la creación de la estructura de un proyecto en GitHub. Su tarea será aprender a usar los conceptos básicos de GitHub para organizar y colaborar en un proyecto, sin necesidad de escribir una sola línea de código por ahora. El objetivo es que cada uno de ustedes contribuya a una parte diferente, ¡y nadie tendrá que esperar a nadie!

### Escenario del Proyecto: "Amazon Futuro"

Imagina que Amazon está desarrollando un nuevo sistema interno para organizar sus departamentos y equipos de desarrollo. Necesitamos una estructura de archivos que represente cómo se organizarían.


### Instrucciones Generales para Todos los Estudiantes:

1.  **Crear una cuenta en GitHub** (si aún no la tienen).
2.  **Entender los conceptos básicos:** Repasen la información que se les proporcionó sobre GitHub, repositorios, ramas, commits, pull requests, etc.
3.  **Comuníquenme su nombre de usuario de GitHub** al finalizar el ejercicio.


### Rol del Profesor (Usted):

1.  **Crear el Repositorio Base:**
    * Cree un nuevo repositorio en GitHub llamado `amazon-futuro`.
    * Inicialice el repositorio con un archivo `README.md`.
    * Dentro del `README.md`, escriba una breve descripción del proyecto, por ejemplo: "Este repositorio simula la estructura de departamentos y equipos de desarrollo de Amazon."
    * Agregue un archivo `.gitignore` al repositorio (puede usar la plantilla de Git para "Node" o "Python" como ejemplo, aunque no escriban código, esto es solo para que se familiaricen con el archivo).
    * ¡**IMPORTANTE**!: Asegúrese de que este repositorio sea **público**.

2.  **Asignar Tareas Individuales:**
    * Comparta el enlace al repositorio `amazon-futuro` con todos los estudiantes.
    * Explique claramente la tarea individual de cada estudiante, como se detalla a continuación.


### Tareas Individuales para los Estudiantes:

**Estudiante Mauricio: (Jefe de Proyectos - Configuración Inicial)** (Listo)
* **Forkea** el repositorio `amazon-futuro` a tu cuenta de GitHub con propósitos colaborativos.
* **Clona** tu fork a tu máquina local.
* Crea una **nueva rama** en tu repositorio local llamada `feature/planificacion-inicial`.
* Cambia a la rama `feature/planificacion-inicial`.
* Crea un nuevo archivo llamado `PLANIFICACION.md` en la raíz del repositorio.
* Dentro de `PLANIFICACION.md`, escribe la siguiente línea: `# Planificación del Proyecto Amazon Futuro`.
* Realiza un **commit** con el mensaje "Configuración inicial de planificación."
* Haz **push origin** de tus cambios a tu rama `feature/planificacion-inicial` en tu repositorio remoto (tu fork).
* Crea un **Pull Request** desde tu rama `feature/planificacion-inicial` de tu fork a la rama `main` del repositorio original `amazon-futuro`. En la descripción del PR, escribe "Se añade el archivo de planificación inicial."

**Estudiante Euro: (Arquitecto de Carpetas - Estructura de Departamentos)**
(Listo)
* **Forkea** el repositorio `amazon-futuro` a tu cuenta de GitHub con propósitos colaborativos.
* **Clona** tu fork a tu máquina local.
* Crea una **nueva rama** en tu repositorio local llamada `feature/estructura-departamentos`.
* Cambia a la rama `feature/estructura-departamentos`.
* Crea una carpeta llamada `Departamentos`.
* Dentro de la carpeta `Departamentos`, crea tres carpetas vacías: `Ventas`, `Marketing`, y `Desarrollo`.
* Crea un archivo vacío llamado `.gitkeep` dentro de cada una de estas tres nuevas carpetas (para asegurar que Git las rastree).
* Realiza un **commit** con el mensaje "Se crea la estructura de carpetas de departamentos."
* Haz **push origin** de tus cambios a tu rama `feature/estructura-departamentos` en tu repositorio remoto (tu fork).
* Crea un **Pull Request** desde tu rama `feature/estructura-departamentos` de tu fork a la rama `main` del repositorio original `amazon-futuro`. En la descripción del PR, escribe "Se agrega la estructura de departamentos."

**Estudiante Wolmar: (Especialista en Documentación - Información de Contacto)**
* **Forkea** el repositorio `amazon-futuro` a tu cuenta de GitHub con propósitos colaborativos.
* **Clona** tu fork a tu máquina local.
* Crea una **nueva rama** en tu repositorio local llamada `feature/contactos`.
* Cambia a la rama `feature/contactos`.
* Crea un nuevo archivo llamado `CONTACTOS.md` en la raíz del repositorio.
* Dentro de `CONTACTOS.md`, escribe la siguiente línea: `# Contactos Clave del Proyecto`.
* Añade tu nombre y un correo electrónico de ejemplo debajo de esa línea.
* Realiza un **commit** con el mensaje "Se añade el archivo de contactos inicial."
* Haz **push origin** de tus cambios a tu rama `feature/contactos` en tu repositorio remoto (tu fork).
* Crea un **Pull Request** desde tu rama `feature/contactos` de tu fork a la rama `main` del repositorio original `amazon-futuro`. En la descripción del PR, escribe "Se añade el archivo de contactos."

**Estudiante Elvis: (Analista de Proyectos - Notas Iniciales)**
(Listo)
* **Forkea** el repositorio `amazon-futuro` a tu cuenta de GitHub con propósitos colaborativos.
* **Clona** tu fork a tu máquina local.
* Crea una **nueva rama** en tu repositorio local llamada `feature/notas-iniciales`.
* Cambia a la rama `feature/notas-iniciales`.
* Crea una carpeta llamada `Notas`.
* Dentro de la carpeta `Notas`, crea un archivo llamado `Notas_Generales.md`.
* Dentro de `Notas_Generales.md`, escribe: `# Notas Importantes` y añade una línea de texto cualquiera debajo.
* Realiza un **commit** con el mensaje "Se añade el archivo de notas generales."
* Haz **push origin** de tus cambios a tu rama `feature/notas-iniciales` en tu repositorio remoto (tu fork).
* Crea un **Pull Request** desde tu rama `feature/notas-iniciales` de tu fork a la rama `main` del repositorio original `amazon-futuro`. En la descripción del PR, escribe "Se agrega la carpeta y archivo de notas."

**Estudiante Santiago: (Organizador de Recursos - Herramientas)**
(Listo)
* **Forkea** el repositorio `amazon-futuro` a tu cuenta de GitHub con propósitos colaborativos.
* **Clona** tu fork a tu máquina local.
* Crea una **nueva rama** en tu repositorio local llamada `feature/herramientas`.
* Cambia a la rama `feature/herramientas`.
* Crea una carpeta llamada `Herramientas`.
* Dentro de la carpeta `Herramientas`, crea un archivo llamado `Herramientas_Recomendadas.md`.
* Dentro de `Herramientas_Recomendadas.md`, escribe: `# Herramientas del Proyecto` y lista tres herramientas genéricas (ej: "IDE", "Editor de Texto", "Navegador Web").
* Realiza un **commit** con el mensaje "Se añade el archivo de herramientas recomendadas."
* Haz **push origin** de tus cambios a tu rama `feature/herramientas` en tu repositorio remoto (tu fork).
* Crea un **Pull Request** desde tu rama `feature/herramientas` de tu fork a la rama `main` del repositorio original `amazon-futuro`. En la descripción del PR, escribe "Se añade la lista de herramientas."

**Estudiante Nesuady: (Diseñador de Flujos - Procesos)**
(Listo)
* **Forkea** el repositorio `amazon-futuro` a tu cuenta de GitHub con propósitos colaborativos.
* **Clona** tu fork a tu máquina local.
* Crea una **nueva rama** en tu repositorio local llamada `feature/procesos`.
* Cambia a la rama `feature/procesos`.
* Crea una carpeta llamada `Procesos`.
* Dentro de la carpeta `Procesos`, crea un archivo llamado `Flujo_Trabajo.md`.
* Dentro de `Flujo_Trabajo.md`, escribe: `# Flujo de Trabajo` y añade una frase simple sobre cómo se trabajará.
* Realiza un **commit** con el mensaje "Se añade el archivo de flujo de trabajo."
* Haz **push origin** de tus cambios a tu rama `feature/procesos` en tu repositorio remoto (tu fork).
* Crea un **Pull Request** desde tu rama `feature/procesos` de tu fork a la rama `main` del repositorio original `amazon-futuro`. En la descripción del PR, escribe "Se agrega el archivo de flujo de trabajo."

**Estudiante Manuel: (Especialista en Nombres - Convenciones)**
(Listo)
* **Forkea** el repositorio `amazon-futuro` a tu cuenta de GitHub con propósitos colaborativos.
* **Clona** tu fork a tu máquina local.
* Crea una **nueva rama** en tu repositorio local llamada `feature/convenciones`.
* Cambia a la rama `feature/convenciones`.
* Crea una carpeta llamada `Documentacion`.
* Dentro de la carpeta `Documentacion`, crea un archivo llamado `Convenciones_Nombres.md`.
* Dentro de `Convenciones_Nombres.md`, escribe: `# Convenciones de Nombres` y añade una regla de ejemplo (ej: "Los nombres de archivos deben ser en minúsculas y usar guiones bajos.").
* Realiza un **commit** con el mensaje "Se añade el archivo de convenciones de nombres."
* Haz **push origin** de tus cambios a tu rama `feature/convenciones` en tu repositorio remoto (tu fork).
* Crea un **Pull Request** desde tu rama `feature/convenciones` de tu fork a la rama `main` del repositorio original `amazon-futuro`. En la descripción del PR, escribe "Se añade documento de convenciones de nombres."

**Estudiante Brayan: (Gestor de Ramas - Pruebas)**
(Listo)
* **Forkea** el repositorio `amazon-futuro` a tu cuenta de GitHub con propósitos colaborativos.
* **Clona** tu fork a tu máquina local.
* Crea una **nueva rama** en tu repositorio local llamada `feature/pruebas-desarrollo`.
* Cambia a la rama `feature/pruebas-desarrollo`.
* Dentro de la carpeta `Departamentos`, en la carpeta `Desarrollo`, crea una subcarpeta llamada `Pruebas`.
* Dentro de la carpeta `Pruebas`, crea un archivo vacío `test_plan.md`.
* Realiza un **commit** en la rama `feature/pruebas-desarrollo` con el mensaje "Se añade carpeta de pruebas."
* Haz **push origin** de la rama `feature/pruebas-desarrollo` a tu repositorio remoto (tu fork).
* Crea un **Pull Request** desde tu rama `feature/pruebas-desarrollo` de tu fork a la rama `main` del repositorio original `amazon-futuro`. En la descripción del PR, escribe "Se añade la estructura de pruebas."

**Estudiante Josluis: (Actualizador de Readme - Descripción Ampliada)**
(listo)
* **Forkea** el repositorio `amazon-futuro` a tu cuenta de GitHub con propósitos colaborativos.
* **Clona** tu fork a tu máquina local.
* Crea una **nueva rama** en tu repositorio local llamada `feature/ampliar-readme`.
* Cambia a la rama `feature/ampliar-readme`.
* Edita el archivo `README.md` existente.
* Añade una sección nueva debajo de la descripción inicial con el título `## Propósito del Proyecto` y escribe dos o tres líneas ampliando la descripción del proyecto.
* Realiza un **commit** con el mensaje "Se amplía la descripción del README."
* Haz **push origin** de tus cambios a tu rama `feature/ampliar-readme` en tu repositorio remoto (tu fork).
* Crea un **Pull Request** desde tu rama `feature/ampliar-readme` de tu fork a la rama `main` del repositorio original `amazon-futuro`. En la descripción del PR, escribe "Se actualiza el README."

**Estudiante Dario: (Creación de Tareas - Listado Pendiente)**
(listo)
* **Forkea** el repositorio `amazon-futuro` a tu cuenta de GitHub con propósitos colaborativos.
* **Clona** tu fork a tu máquina local.
* Crea una **nueva rama** en tu repositorio local llamada `feature/lista-tareas`.
* Cambia a la rama `feature/lista-tareas`.
* Crea una carpeta llamada `Tareas`.
* Dentro de la carpeta `Tareas`, crea un archivo llamado `Lista_Pendientes.md`.
* Dentro de `Lista_Pendientes.md`, escribe: `# Tareas Pendientes` y añade dos tareas de ejemplo (ej: "- Definir equipos de Ventas", "- Diseñar estructura de Marketing").
* Realiza un **commit** con el mensaje "Se añade la lista de tareas pendientes."
* Haz **push origin** de tus cambios a tu rama `feature/lista-tareas` en tu repositorio remoto (tu fork).
* Crea un **Pull Request** desde tu rama `feature/lista-tareas` de tu fork a la rama `main` del repositorio original `amazon-futuro`. En la descripción del PR, escribe "Se añade el archivo de tareas pendientes."

**Estudiante 11: (Reglas de Colaboración - Contribución)**
* **Forkea** el repositorio `amazon-futuro` a tu cuenta de GitHub con propósitos colaborativos.
* **Clona** tu fork a tu máquina local.
* Crea una **nueva rama** en tu repositorio local llamada `feature/contribucion`.
* Cambia a la rama `feature/contribucion`.
* Crea un nuevo archivo llamado `CONTRIBUTING.md` en la raíz del repositorio.
* Dentro de `CONTRIBUTING.md`, escribe: `# Reglas de Contribución` y añade una regla simple (ej: "Antes de cada cambio, asegúrate de hacer `pull origin`.").
* Realiza un **commit** con el mensaje "Se añade el archivo de reglas de contribución."
* Haz **push origin** de tus cambios a tu rama `feature/contribucion` en tu repositorio remoto (tu fork).
* Crea un **Pull Request** desde tu rama `feature/contribucion` de tu fork a la rama `main` del repositorio original `amazon-futuro`. En la descripción del PR, escribe "Se agrega el archivo de reglas de contribución."

**Estudiante 12: (Futuro de Marketing - Subdepartamento)**
* **Forkea** el repositorio `amazon-futuro` a tu cuenta de GitHub con propósitos colaborativos.
* **Clona** tu fork a tu máquina local.
* Crea una **nueva rama** en tu repositorio local llamada `feature/marketing-digital`.
* Cambia a la rama `feature/marketing-digital`.
* Dentro de la carpeta `Departamentos`, en la carpeta `Marketing`, crea una subcarpeta llamada `Digital`.
* Dentro de la carpeta `Digital`, crea un archivo vacío `estrategia.md`.
* Realiza un **commit** con el mensaje "Se añade subdepartamento de Marketing Digital."
* Haz **push origin** de tus cambios a tu rama `feature/marketing-digital` en tu repositorio remoto (tu fork).
* Crea un **Pull Request** desde tu rama `feature/marketing-digital` de tu fork a la rama `main` del repositorio original `amazon-futuro`. En la descripción del PR, escribe "Se añade la estructura de Marketing Digital."

**Estudiante 13: (Futuro de Ventas - Subdepartamento)**
* **Forkea** el repositorio `amazon-futuro` a tu cuenta de GitHub con propósitos colaborativos.
* **Clona** tu fork a tu máquina local.
* Crea una **nueva rama** en tu repositorio local llamada `feature/ventas-online`.
* Cambia a la rama `feature/ventas-online`.
* Dentro de la carpeta `Departamentos`, en la carpeta `Ventas`, crea una subcarpeta llamada `Online`.
* Dentro de la carpeta `Online`, crea un archivo vacío `proyecciones.md`.
* Realiza un **commit** con el mensaje "Se añade subdepartamento de Ventas Online."
* Haz **push origin** de tus cambios a tu rama `feature/ventas-online` en tu repositorio remoto (tu fork).
* Crea un **Pull Request** desde tu rama `feature/ventas-online` de tu fork a la rama `main` del repositorio original `amazon-futuro`. En la descripción del PR, escribe "Se añade la estructura de Ventas Online."

**Estudiante 14: (Versión del Proyecto - Archivo Info)**
* **Forkea** el repositorio `amazon-futuro` a tu cuenta de GitHub con propósitos colaborativos.
* **Clona** tu fork a tu máquina local.
* Crea una **nueva rama** en tu repositorio local llamada `feature/version-proyecto`.
* Cambia a la rama `feature/version-proyecto`.
* Crea un nuevo archivo llamado `VERSION.md` en la raíz del repositorio.
* Dentro de `VERSION.md`, escribe: `# Versión del Proyecto` y añade "Versión: 0.1.0".
* Realiza un **commit** con el mensaje "Se añade archivo de versión del proyecto."
* Haz **push origin** de tus cambios a tu rama `feature/version-proyecto` en tu repositorio remoto (tu fork).
* Crea un **Pull Request** desde tu rama `feature/version-proyecto` de tu fork a la rama `main` del repositorio original `amazon-futuro`. En la descripción del PR, escribe "Se agrega el archivo de versión."

**Estudiante 15: (Actualizador de Readme - Sección de Tareas)**
* **Forkea** el repositorio `amazon-futuro` a tu cuenta de GitHub con propósitos colaborativos.
* **Clona** tu fork a tu máquina local.
* Crea una **nueva rama** en tu repositorio local llamada `feature/actualizar-readme-tareas`.
* Cambia a la rama `feature/actualizar-readme-tareas`.
* Edita el archivo `README.md` existente.
* Añade una sección nueva debajo de "Propósito del Proyecto" (si ya fue añadida por el Estudiante 9) o la descripción inicial, con el título `## Tareas Recientes` y una línea simple como "Se han añadido nuevas estructuras de departamentos y documentación."
* Realiza un **commit** con el mensaje "Se añade sección de tareas recientes al README."
* Haz **push origin** de tus cambios a tu rama `feature/actualizar-readme-tareas` en tu repositorio remoto (tu fork).
* Crea un **Pull Request** desde tu rama `feature/actualizar-readme-tareas` de tu fork a la rama `main` del repositorio original `amazon-futuro`. En la descripción del PR, escribe "Se actualiza el README con tareas recientes."

---

### **Consideraciones para el Profesor:**

* **Revisión y Fusión de Pull Requests:** A medida que los estudiantes creen sus Pull Requests, usted, como propietario del repositorio original, deberá revisarlos y **fusionarlos (`Merge`)** uno por uno. Esto les mostrará a los estudiantes cómo sus cambios se integran en el proyecto principal. Si un estudiante tiene un **conflicto**, esta será una excelente oportunidad para enseñar cómo resolverlo.
* **Comunicación Constante:** Anime a los estudiantes a hacer preguntas y a comunicar cualquier problema.
* **Tiempo de Ejecución:** Este ejercicio puede tomar una buena parte de una clase, dependiendo de la familiaridad de los estudiantes con la línea de comandos y GitHub en general.
