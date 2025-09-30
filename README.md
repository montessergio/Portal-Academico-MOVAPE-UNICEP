🎓 Portal Académico MOVAPE/UNICEP
✨ Visión General
El Portal Académico MOVAPE/UNICEP es una aplicación web prototipo diseñada para simular la experiencia de un sistema de gestión de información universitaria, sirviendo como una prueba de concepto (PoC) rápida y funcional. Nuestro objetivo principal es crear una interfaz digital intuitiva y unificada que brinde a estudiantes, docentes y administradores acceso en tiempo real a información académica crucial, simplificando los procesos y mejorando la comunicación interna.
Este proyecto fue desarrollado íntegramente en un único archivo HTML, CSS y JavaScript (Vanilla JS), demostrando un enfoque de prototipado rápido y frontend-first.
________________________________________
🎯 Objetivo de Producto
El objetivo principal de este producto es transformar la Fundación MOVAPE/UNICEP en una institución educativa completamente digitalizada, proporcionando una plataforma centralizada y multi-rol que simplifique la gestión académica y fortalezca la comunicación entre todos los actores.
Declaración del Objetivo
Aumentar la eficiencia administrativa y la transparencia académica en un 25% durante el primer año de operación, centralizando el acceso a calificaciones, horarios, materiales y herramientas de gestión (asistencia y tareas) para estudiantes, docentes y administradores en un único ecosistema digital de fácil acceso.
🗺️ Estrategia de Producto
Nuestra estrategia se centrará en la digitalización de la experiencia académica integral, utilizando la estructura de roles (Estudiante, Docente, Administrador) ya definida en el prototipo para desarrollar un producto de alto valor y usabilidad para cada segmento.
1. Propuesta de Valor Central
   Para Estudiantes: Ser la fuente única de verdad para su progreso académico y su vida universitaria.
   Para Docentes: Simplificar y automatizar las tareas administrativas de gestión de clases (listas, tareas y materiales).
   Para Administradores: Ofrecer una visibilidad completa del ciclo educativo y la actividad institucional.
2. Segmentación de la Experiencia y Roadmap
  El prototipo actual (HTML/CSS/JS con datos fijos) valida la interfaz y los flujos básicos. La estrategia de desarrollo debe enfocarse en la transición a un sistema dinámico y funcional.
3. Estrategia Tecnológica y de Crecimiento
   Validación Tecnológica (Fase 1 - Core): La prioridad inmediata es migrar la data fija a una base de datos escalable y segura (como Firestore o PostgreSQL) e implementar un sistema de autenticación real (no demo) para garantizar la privacidad y la integridad de los datos académicos.
  Iteración de Valor (Fase 2 - Expansión): Enfocarse en completar los flujos críticos del docente (Asistencia y Calificación), ya que estos impulsan la utilidad del portal para el segmento más activo.
  Retención y Mejora (Fase 3 - Optimización): Implementar características de comunicación proactiva, como notificaciones en tiempo real para nuevas tareas, cambios de horario o anuncios importantes, y optimizar el portal para un rendimiento impecable en dispositivos móviles (ya que muchos estudiantes acceden desde el móvil).
4. Métricas Clave de Desempeño (KPIs)
   Adopción: Tasa de inicio de sesión semanal de Estudiantes y Docentes.
   Impacto de Eficiencia (Docentes): Porcentaje de asistencia registrada a través del portal vs. métodos manuales.
   Compromiso (Estudiantes): Tasa de acceso al Material de Estudio y Tasa de Entrega de Tareas a tiempo.
   Estabilidad: Tiempo de actividad del portal (uptime) y tasa de errores de inicio de sesión.
🚀 Características y Funcionalidades (Demo)
El portal simula la experiencia de usuario a través de tres roles clave, cada uno con su propio conjunto de información y funcionalidades principales:
🧑‍🎓 Rol: Estudiante
Funcionalidad	Descripción
Info Estudiante	Visualización de datos de carrera, cuatrimestre y modalidad.
Mis Calificaciones	Resumen y detalle de las notas por asignatura.
Mi Horario	Consulta del horario de clases, incluyendo aula y docente.
Tareas Pendientes	Seguimiento de las tareas no entregadas con fechas de vencimiento.
Material de Estudio	Acceso al material de apoyo subido por los docentes.
Plan de Estudios	Visualización detallada de la malla curricular por cuatrimestre y asignaturas.
🧑‍🏫 Rol: Docente
Funcionalidad	Descripción
Gestionar Clases	Lista de las asignaturas a cargo y número de estudiantes.
Material de Clase	Gestión (subida y revisión) del material didáctico para cada asignatura.
Asignaciones/Tareas	Creación y revisión del estado de entrega de las tareas por parte de los alumnos.
Toma de Asistencia	Herramienta para registrar la asistencia de los estudiantes por fecha y clase.
⚙️ Rol: Administrador
Funcionalidad	Descripción
Calendario Académico	Gestión y visualización de eventos, días festivos y periodos de examen.
Anuncios Globales	Herramienta para publicar comunicaciones oficiales a toda la comunidad.
Gestión de Cuentas	Acceso simulado a la base de datos de usuarios (estudiantes y docentes).
________________________________________
🛠️ Stack Tecnológico
Dada la naturaleza de prototipo rápido, la solución se basa en tecnologías puras y ligeras:
•	HTML5: Estructura base del portal.
•	CSS3 (Vanilla CSS): Estilización, diseño responsivo y efectos visuales (fondo animado con esferas).
•	JavaScript (Vanilla JS): Lógica de la aplicación, manejo de eventos, simulación de backend (datos almacenados en objetos JS) y renderizado de dashboards.
________________________________________
📂 Estructura del Proyecto
El código reside en un único archivo, encapsulando la presentación y la lógica:
├── index.html (Contiene HTML, CSS y JavaScript)
Nota: En un proyecto real, se implementaría una estructura modular con backend (Node.js, Python, etc.) y una base de datos robusta (SQL, NoSQL) para la persistencia de datos y una separación limpia de las responsabilidades (arquitectura MVC o similar).
________________________________________
🔑 Acceso de Demostración
Para explorar la funcionalidad simulada, utiliza los siguientes IDs en la pantalla de Login. ¡Simplemente haz clic en el ID para autocompletar el campo!
Rol	ID de Usuario
Administrador	ADM-2024-001
Estudiante	EST-2024-001
Docente	PROF-2024-101
Exportar a Hojas de cálculo
________________________________________
👤 Equipo del Proyecto
Rol	Miembro
Gerente de Producto (Product Manager)	Sergio Montes Cruz
Desarrollador Frontend	OPEN AI-CANVA,CURSOR,GEMINI,GITHUB COPILOT (desarrollo en solitario/equipo ágil)
Diseñador UX/UI	OPEN AI- CANVA,CURSOR,GEMINI,GITHUB COPILOT (diseño rápido e integrado)

Como Gerente de Producto, mi enfoque está en validar la funcionalidad central, la experiencia de usuario de los tres roles principales y asegurar que esta PoC refleje la visión académica de MOVAPE/UNICEP.
________________________________________
💬 Próximos Pasos (Hoja de Ruta)
Una vez validada la demo actual, las siguientes fases de desarrollo incluirán:
1.	Separación de la Lógica: Migrar la lógica de datos y usuarios a un backend real con una base de datos para una solución escalable.
2.	Módulos Avanzados: Desarrollar completamente los módulos de mensajería interna, foros de discusión y gestión de pagos/colegiaturas.
3.	Refinamiento UX/UI: Aplicar un diseño de interfaz más alineado con la identidad corporativa de MOVAPE/UNICEP.
4.	Implementacion de Mensajeria: Implementar un sistema comunicacion a traves de correos electronicos vinculados con el portal estudiantil.
________________________________________
¡Agradezco a todos los colaboradores por el esfuerzo en este prototipo inicial! Sus comentarios son vitales para llevar el Portal Académico al siguiente nivel.
Sergio Montes Cruz Gerente de Producto | Portal Académico MOVAPE/UNICEP


