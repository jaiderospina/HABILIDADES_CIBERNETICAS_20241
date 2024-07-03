# RFC 2350

RFC 2350, titulado "Expectations for Computer Security Incident Response," establece las expectativas para los Equipos de Respuesta a Incidentes de Seguridad Informática (CSIRT). Los aspectos principales tratados son:


1. **Introducción**: 
   - Se define un CSIRT como un equipo que proporciona servicios y soporte para manejar y prevenir incidentes de seguridad informática. Estos equipos son esenciales para mantener la seguridad y estabilidad de los sistemas de información.

2. **Alcance**: 
   - Se subraya la importancia de la transparencia en las políticas de los CSIRTs. Los equipos deben documentar y publicar claramente sus políticas, las relaciones con otros CSIRTs y garantizar que los canales de comunicación sean seguros y confiables.

3. **Información, Políticas y Procedimientos**: 
   - Los CSIRTs deben proporcionar información clara y accesible sobre su contacto, misión y ámbito de operación (constituencia). Además, deben detallar su autoridad para actuar y las políticas específicas para responder a incidentes, incluyendo procedimientos para la gestión de incidentes y coordinación con otras entidades.

4. **Apéndices**: 
   - Se incluyen recursos adicionales como un glosario de términos relevantes, referencias a materiales relacionados, una lista de CSIRTs conocidos para referencia, una plantilla de ejemplo para la documentación de CSIRT y un ejemplo completo para ilustrar cómo debería ser la documentación de un CSIRT.

Este documento proporciona un marco comprensivo para establecer y operar un CSIRT eficaz, promoviendo prácticas estándar y colaboración entre equipos de respuesta a incidentes.

Para obtener más detalles, puedes consultar el documento completo [aquí](https://www.rfc-editor.org/rfc/rfc2350).

### Taller.

1. En grupos realizar la tradución del RFC 2350 (526312754-rfc2350.PDF) respetando el formato del mismo. Para ello respetar la asignación de páginas realizado en clase, de marera colaborativa sobre este README.md de esta carpeta.

2. Estudiar de manera individual el documento generado.

3. Participar en la exploración grupal que se realizará en clase.

4. De la actividad general,  se realizará una prueba escrita individual en clase (quizzis). 


###  RFC 2350


**Pag 7-12 (temporal para conocimiento)**

Claves criptográficas utilizadas en la comunicación segura:

•	Claves públicas (para técnicas como PGP y PEM): Debido a que son accesibles a través de Internet, las claves públicas deben ser autenticadas antes de su uso. Mientras que PGP se basa en una "Red de Confianza" (donde los usuarios firman las claves de otros usuarios), PEM se basa en una jerarquía (donde las autoridades de certificación firman las claves de los usuarios).

•	Claves secretas (para técnicas como DES y PGP/cifrado convencional): Debido a que deben ser conocidas tanto por el remitente como por el receptor, las claves secretas deben intercambiarse antes de la comunicación a través de un canal seguro.

La comunicación es fundamental para todos los aspectos de la respuesta a incidentes. Un equipo puede apoyar mejor el uso de las técnicas mencionadas anteriormente reuniendo toda la información relevante, de manera consistente. Requisitos específicos (como llamar a un número específico para verificar la autenticidad de las claves) debe quedar claro desde el principio. Las plantillas CSIRT proporcionan un vehículo estandarizado para entregar esta información. 

Está fuera del alcance de este documento abordar los problemas técnicos y problemas administrativos de las comunicaciones seguras. El punto es que los equipos de respuesta deben apoyar y utilizar un método para asegurar la comunicaciones entre ellos y sus electores (u otros equipos de respuesta). Cualquiera que sea el mecanismo, el nivel de protección debe ser aceptable para la comunidad constituyente.


