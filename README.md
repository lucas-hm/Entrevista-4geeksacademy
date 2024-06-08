# Entrevista-4geeksacademy
Este repo contiene mi charla para la entrevista del jueves

¿Qué es un ataque cross site? 
Es un ataque de inyección de código a través de un servidor externo

¿Qué es el phishing y cómo podrías prevenirlo?
Los ataques de tipo phishing son email pidiéndote qué cambies tu contraseña de mail porque ha sido descifrada, principalmente los envían noreply@google.com. Este tipo de ataques pueden ser prevenidos mediante capacitaciónes básicas de Ciberseguridad. 

¿Cuál es la diferencia entre un WAF y un firewall tradicional?
WAF (Web Application Firewall):
Protección: Se enfoca en proteger aplicaciones web.
Función: Filtra y monitorea el tráfico HTTP/HTTPS para prevenir ataques específicos a aplicaciones web, como inyecciones SQL, cross-site scripting (XSS) y otros exploits de la capa de aplicación.
Nivel: Opera en la capa 7 (aplicación) del modelo OSI.

Firewall tradicional:
Protección: Protege redes internas contra accesos no autorizados y ataques externos.
Función: Filtra el tráfico en función de reglas predefinidas basadas en direcciones IP, puertos y protocolos.
Nivel: Opera en la capa 3 (red) y capa 4 (transporte) del modelo OSI.

¿Qué es la seguridad de capa de aplicación y por qué es importante?
La seguridad de capa de aplicación se enfoca en proteger las aplicaciones de amenazas que intentan explotar vulnerabilidades en el código de la aplicación

¿Cómo funciona el cifrado y cuál es su importancia en la ciberseguridad?
El cifrado funciona como una capa de seguridad para el envio y transformacion de datos, asegurando que las personas autorizadas puedan acceder, manipular y comprender los datos.

Confidencialidad: Protege la información para que solo las partes autorizadas puedan acceder a ella.
Integridad: Asegura que los datos no sean alterados sin autorización durante su almacenamiento o transmisión.
Autenticidad: Verifica la identidad de las partes involucradas en la comunicación.
No repudio: Garantiza que las partes no puedan negar haber realizado una acción, como enviar un mensaje.

Análisis de Incidentes:

Describe un incidente de ciberseguridad que hayas manejado y cómo lo resolviste.
Un incidente que tuve que manejar fue cuando hice mi pasantia en Edemsa, donde tuve problemas con el servidor y le configure un Docker-compose para enviar datos cifrados desde una página que hice en Nodejs. 

¿Qué pasos seguirías en caso de una brecha de seguridad?
1. **Contención inmediata:**
   - **Aislar los sistemas comprometidos**: Desconectar los sistemas afectados de la red para evitar la propagación del ataque.
   - **Bloquear accesos no autorizados**: Revocar credenciales comprometidas y aplicar reglas de firewall para bloquear IPs sospechosas.

2. **Evaluación de daños:**
   - **Identificar la fuente de la brecha**: Analizar logs y sistemas para determinar cómo ocurrió la brecha.
   - **Determinar el alcance**: Evaluar qué datos y sistemas fueron afectados.

3. **Notificación:**
   - **Informar al equipo de respuesta a incidentes**: Notificar a los responsables internos de seguridad.
   - **Comunicar a las partes afectadas**: Informar a los clientes, empleados y socios, según las normativas legales y políticas de la empresa.

4. **Erradicación:**
   - **Eliminar la causa de la brecha**: Remover malware, cerrar vulnerabilidades y eliminar accesos no autorizados.
   - **Actualizar sistemas**: Parches de seguridad y mejoras en las configuraciones de seguridad.

5. **Recuperación:**
   - **Restaurar sistemas afectados**: Utilizar copias de seguridad limpias para restaurar datos y sistemas comprometidos.
   - **Verificar la integridad**: Asegurarse de que los sistemas estén libres de amenazas antes de reactivarlos.

6. **Análisis post-mortem:**
   - **Revisión del incidente**: Analizar detalladamente el incidente para comprender mejor las causas y fallos en las defensas.
   - **Mejoras en la seguridad**: Implementar medidas adicionales para prevenir futuras brechas, como capacitación de personal, mejoras en la infraestructura de seguridad y revisiones de políticas de seguridad.

7. **Documentación y reporte:**
   - **Documentar el incidente**: Registrar todos los detalles del incidente, acciones tomadas y resultados.
   - **Reportar a reguladores**: Si es requerido, informar a las autoridades pertinentes sobre la brecha de seguridad y las acciones tomadas.

Evaluación y Gestión de Riesgos:

¿Cómo evaluarías el riesgo de una nueva vulnerabilidad en el sistema?
-Identificación de la Vulnerabilidad:
   Determina la naturaleza de la vulnerabilidad, cómo fue descubierta y cuál es su posible impacto en el sistema.
-Evaluación de la Severidad:
   Utiliza sistemas de puntuación como el Common Vulnerability Scoring System (CVSS) para cuantificar la gravedad de la vulnerabilidad en función de factores como la facilidad de explotación, el impacto     potencial y el nivel de acceso requerido.
-Determinación de la Exposición:
   Evalúa si la vulnerabilidad afecta componentes críticos del sistema y si es accesible desde fuera de la red o si requiere acceso interno.
-Análisis del Impacto:
   Considera las posibles consecuencias de la explotación de la vulnerabilidad, como la pérdida de datos, interrupción del servicio, daños a la reputación, y costos financieros.

¿Qué metodologías o frameworks de gestión de riesgos conoces y has utilizado?
Cybersecurity Risk Management Framework (RMF)
FAIR (Factor Analysis of Information Risk)

Políticas y Cumplimiento:

¿Qué es la norma ISO/IEC 27001?
Estándar internacional que establece los requisitos para la implementación, mantenimiento y mejora continua de un Sistema de Gestión de la Seguridad de la Información (SGSI).

¿Qué entiendes por GDPR y cómo afecta a la ciberseguridad?
Este es el Reglamento General de Protección de datos, esto afecta mucho en cuanto a ciberseguridad porque hay datos de gente de muchos paises y se deben administrar de forma correcta esos datos para no infringir la ley de cada pais.

¿Qué herramientas de análisis de vulnerabilidades has utilizado?
He utilizado nessus.

¿Tienes experiencia con SIEM (Security Information and Event Management)? ¿Cuál?
Si, he tenido experiencia con SIEM en mi reciente pasantia en Edemsa, donde monitoree logs de datos de compra de computadoras, notebooks y servidores.
