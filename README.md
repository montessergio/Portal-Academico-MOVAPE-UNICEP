# Portal de Gestión Académica Integral - MOVAPE / UNICEP 🎓

> ### 🌐 [ACCEDER AL PORTAL EN VIVO](https://montessergio.github.io/Portal-Acad-mico-MOVAPE-UNICEP/)

Este ecosistema digital ha sido desarrollado para centralizar la administración escolar de la **Fundación MOVAPE / UNICEP**. El sistema ofrece una arquitectura robusta que gestiona planes de estudio de hasta 10 cuatrimestres, control de usuarios y repositorios de materiales académicos en tiempo real.

---

## 🏛️ Arquitectura del Sistema

La plataforma se segmenta en tres perfiles operativos con permisos jerárquicos:

### 1. Panel Administrativo (Nivel Root) 🛡️
Es el núcleo de control del sistema. Permite supervisar la integridad de la institución:
* **Gestión de Usuarios:** Alta y baja de alumnos (Estatus Activo/Baja).
* **Modificación Académica:** Cambio de carrera y modalidad para los estudiantes.
* **Asignación de Cátedra:** Control sobre las materias que cada docente imparte.
* **Configuración de Mallas:** Edición de materias dentro de los planes de estudio oficiales.

### 2. Panel del Personal Docente 👨‍🏫
Herramientas diseñadas para el seguimiento del aprendizaje:
* **Control de Asistencia:** Gestión de listas por asignatura.
* **Gestión de Contenidos:** Carga de archivos y manuales de estudio.
* **Evaluación:** Registro de calificaciones que se sincronizan con el perfil del alumno.

### 3. Portal del Estudiante 👤
Interfaz enfocada en la experiencia de usuario (UX) y consulta:
* **Kardex Digital:** Visualización de calificaciones por cuatrimestre.
* **Biblioteca de Clase:** Acceso directo a materiales subidos por sus profesores.
* **Plan de Estudios Completo:** Visualización de la malla curricular total (9 y 10 cuatrimestres).

---

## ⚙️ Especificaciones Técnicas

El proyecto se rige bajo estándares de desarrollo web moderno (Vanilla Stack), garantizando portabilidad y velocidad:
* **Frontend:** HTML5 Semántico y CSS3 con diseño responsivo.
* **Lógica:** JavaScript ES6+ para la gestión dinámica de datos y sesiones.
* **Despliegue:** GitHub Pages para visualización inmediata.

---

## 📂 Carreras y Planes de Estudio Integrados

El sistema incluye las mallas curriculares completas para las siguientes licenciaturas e ingenierías:
* ⚙️ **Ingeniería Industrial**
* ⚖️ **Derecho**
* 🧠 **Psicología**
* 💼 **Administración**
* 🍎 **Pedagogía**

---

## 🔑 Credenciales de Acceso (Demo)

Para explorar todas las funcionalidades, puede utilizar las siguientes cuentas integradas:

| Perfil | ID de Usuario | Descripción |
| :--- | :--- | :--- |
| **Administrador** | `ADMIN-01` | Acceso total al sistema |
| **Docente** | `PROF-101` | Gestión de clases y materiales |
| **Estudiante** | `EST-001` a `EST-005` | Consulta de 5 perfiles distintos |

---

## 🛠️ Instalación Local

1. Clonar el repositorio:
   ```bash
   git clone [https://github.com/montessergio/Portal-Acad-mico-MOVAPE-UNICEP.git](https://github.com/montessergio/Portal-Acad-mico-MOVAPE-UNICEP.git)
