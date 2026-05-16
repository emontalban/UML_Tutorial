Diagrama de Despliegue
Diseñar el diagrama de despliegue del sistema utilizando un servicio de integración continua (CI).

Nodos requeridos:

- Continuous Integration (CI) server
- Staging environment
- Pre-production environment
- Production environment

El diagrama debe representar cómo el código pasa por procesos de pruebas, validaciones y despliegue antes de llegar al entorno de producción.

---

![Diagrama de actividad](Academia-actividad.png)

Este diagrama de actividad representa el flujo del proceso de realización de un examen dentro de un sistema de evaluación educativa. El modelo utiliza swim lanes para separar las acciones del profesor, el sistema y el estudiante. El proceso inicia cuando el profesor asigna el cuestionario y el sistema genera las preguntas. Posteriormente, el estudiante confirma el inicio del examen y responde cada pregunta mientras el sistema controla el flujo y verifica si existen más preguntas pendientes. Una vez finalizado el cuestionario, el sistema calcula los resultados, los envía al profesor para su aprobación y finalmente almacena las calificaciones. El diagrama permite visualizar de forma clara las responsabilidades y la interacción entre los distintos participantes del sistema.