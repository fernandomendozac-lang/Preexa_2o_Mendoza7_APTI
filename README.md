# Sistema de Gestión de Seguridad Informática Empresarial

**Nombre del Proyecto:** Preexa Mendoza Seguridad IT  
**Materia:** Administración de Seguridad Informática  
**Estudiante:** Mendoza Carrillo Fernando

---

## Objetivo
El objetivo de este examen es desarrollar una plataforma web utilizando el lenguaje **Java** bajo el patrón de arquitectura **MVC**, que permita administrar de forma eficiente la legislación, consejos y tips técnicos de seguridad informática para entornos corporativos, facilitando el mantenimiento de la integridad y confidencialidad de los datos.

## Alcance
El sistema permite realizar las operaciones fundamentales de un **CRUD** sobre una base de datos MySQL:
* **Altas:** Registro de nuevos lineamientos y normativas.
* **Consultas:** Listado dinámico de la base de conocimientos de seguridad.
* **Edición:** Actualización de registros para mantener la vigencia de la legislación.
* **Bajas:** Eliminación de información obsoleta del repositorio.

---

## Apoyo de Inteligencia Artificial (Gemini)
Para la realización de esta actividad, se utilizó la IA **Gemini** de Google como asistente técnico para la generación de la estructura base y la depuración de errores lógicos.

### Registro de Prompts (Interacción con la IA)
A continuación se presentan los comandos clave utilizados para completar el examen:

1. **Definición de estructura:** *"Necesito desarrollar un proyecto web para consejos, tips, legislación de la administración de la seguridad informática a nivel empresarial... en lenguaje java."*
2. **Desarrollo de Interfaz:** *"Ayúdame a crear el código para el index con una tabla de 5 campos para altas y consultas."*
3. **Depuración de Servlets:** *"Tengo un error 404 al intentar enviar el formulario al Controlador, ¿cómo lo resuelvo?"*
4. **Conectividad JDBC:** *"Mi base de datos no está recibiendo los datos, revisa mi clase Conexion.java para MySQL."*
5. **Documentación:** *"Realizar un readme del contenido de este examen que incluya nombre del proyecto, objetivo y alcance."*

---

## Tecnologías y Clases Utilizadas
El proyecto se compone de las siguientes capas técnicas:

* **Controlador:** `Controlador.java` (Servlet encargado de procesar las peticiones).
* **Configuración:** `Conexion.java` (Gestiona el puente hacia MySQL).
* **Modelo:** `Consejo.java` (Entidad de datos) y `ConsejoDAO.java` (Lógica SQL).
* **Vista:** `index.jsp` (Interfaz de usuario con Bootstrap 5).

---
*Examen práctico - Desarrollado en NetBeans con servidor Apache Tomcat.*
