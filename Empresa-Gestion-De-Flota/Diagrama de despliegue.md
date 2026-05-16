Se requiere diseñar el diagrama de despliegue (Deployment Diagram) de un sistema empresarial de gestión de flotas (Fleet Management System). El objetivo es representar la arquitectura física del sistema en producción, mostrando cómo se distribuyen los componentes principales y cómo se gestionan las solicitudes de los usuarios a través de la infraestructura.

El sistema debe incluir, como mínimo, los siguientes elementos: un balanceador de carga, múltiples servidores de aplicación, un clúster de caché y un clúster de base de datos. El diseño debe reflejar cómo las solicitudes entrantes son distribuidas entre servidores, cómo se optimiza el rendimiento mediante caching y cómo se garantiza la persistencia y consistencia de los datos en la base de datos.

Además, se debe contemplar un escenario de alta disponibilidad, donde la caída de un servidor no interrumpa el servicio, y el sistema pueda seguir respondiendo a las peticiones mediante los recursos restantes.

---
![Diagrama de despliegue](Empresa-Despliegue)