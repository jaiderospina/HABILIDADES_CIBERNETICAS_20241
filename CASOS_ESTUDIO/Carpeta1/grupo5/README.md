## CASOS DE ESTUDIO


# CASO 1.  Consultoría sobre Medidas de ciberseguridad. 

En grupos de 4 integrantes analizar y responder el siguiente caso de estudio. Para ello:

- Crear una carpeta  al interior de la carpeta Caso1 con el número del grupo.
- Responder cada una de las preguntas sobre el README.md de la carpeta, emplee la notación de markdonw para dar formato (nuemerales, negrillas, etc) https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

## Escenario.

Su organización provee un software que debe ser descargado desde un repositorio accedido vía web, de manera regular por terceros. Este software se considera como de alto impacto para la organización. 

1. Bajo el anterior escenario qué medidas implementaría para asegurar que no se presente un eventual ataque mediante compromiso de la cadena de suministro?.
2. Describa el objetivo de la medida y que factor de riesgo mitiga.
3. Defina que es una cadena de suministro y su relevancia en aspectos de ciberseguridad y particularmente en el contexto del ecosistema del ciberespacio.


### DESARROLLO

#### I y II. Para asegurar que no se presente un eventual ataque mediante el compromiso de la cadena de suministro en la entrega de software de alto impacto, es crucial implementar medidas específicas y exhaustivas. 

## **1. Seguridad del Código Fuente**
**Control de Versiones Seguro:**
- Objetivo: Asegurar que todas las modificaciones al código fuente sean rastreables y autenticadas.
- Factor de Riesgo Mitigado: Acceso no autorizado y modificaciones maliciosas del códigofuente.

**Revisiones de Código:**
- Objetivo: Garantizar que el código sea revisado por varios desarrolladores antes de ser fusionado.
- Factor de Riesgo Mitigado: Introducción de vulnerabilidades o código malicioso de manera inadvertida.

**Análisis de Seguridad Automático:**
- Objetivo: Detectar vulnerabilidades y problemas de seguridad en el código antes de su despliegue.
- Factor de Riesgo Mitigado: Vulnerabilidades no detectadas en el código que podrían ser explotadas por atacantes.

## **2. Autenticación y Autorización**
**Autenticación Multifactor (MFA):**
- Objetivo: Asegurar que solo usuarios autenticados de manera robusta puedan acceder al repositorio.
- Factor de Riesgo Mitigado: Compromiso de cuentas mediante ataques de phishing o fuerza bruta.

**Control de Acceso Basado en Roles (RBAC):**
- Objetivo: Limitar los permisos de acceso y modificaciones a solo lo necesario para cada rol específico.
- Factor de Riesgo Mitigado: Acceso innecesario y potencialmente peligroso a partes críticas del sistema por usuarios no autorizados.

## **3. Integridad y Verificación del Software**
**Firmas Digitales:**
- Objetivo: Garantizar la autenticidad y la integridad del software distribuido.
- Factor de Riesgo Mitigado: Modificación no detectada de los archivos de software durante la distribución.

**Hashes y Checksums:**
- Objetivo: Permitir a los usuarios verificar la integridad de los archivos descargados.
- Factor de Riesgo Mitigado: Alteración de los archivos de software durante la transmisión.

## **4. Cadenas de Suministro de Componentes de Terceros**
**Verificación de Dependencias:**
- Objetivo: Asegurarse de que las dependencias de terceros sean seguras y actualizadas.
- Factor de Riesgo Mitigado: Inclusión de dependencias vulnerables o maliciosas en el software.

**Fuentes Confiables:**
- Objetivo: Descarga y actualización de dependencias solo desde fuentes oficiales y verificadas.
- Factor de Riesgo Mitigado: Compromiso de dependencias descargadas desde fuentes no confiables.

**Escaneo de Vulnerabilidades:**
- Objetivo: Detectar vulnerabilidades en las dependencias de terceros regularmente.
- Factor de Riesgo Mitigado: Uso continuo de componentes vulnerables en el software.

## **5. Seguridad en la Distribución**
**Protocolo HTTPS:**
- Objetivo: Proteger la transferencia de datos entre el repositorio y los usuarios.
- Factor de Riesgo Mitigado: Interceptación y manipulación de datos durante la transmisión.

**CDN Seguras:**
- Objetivo: Asegurar que las redes de distribución de contenido sean seguras y confiables.
- Factor de Riesgo Mitigado: Distribución de software comprometido a través de CDN inseguras.

## **6. Monitorización y Auditoría**
**Registro y Monitoreo:**
- Objetivo: Mantener un registro detallado de todas las actividades en el repositorio.
- Factor de Riesgo Mitigado: Actividades no autorizadas o sospechosas que podrían comprometer la integridad del software.

**Auditorías Regulares:**
- Objetivo: Revisar la seguridad del sistema de manera periódica para detectar y corregir vulnerabilidades.
- Factor de Riesgo Mitigado: Vulnerabilidades no detectadas debido a la falta de revisiones regulares.

## **7. Respaldo y Recuperación**
**Respaldos Frecuentes:**
- Objetivo: Asegurar la disponibilidad de los datos mediante respaldos regulares.
- Factor de Riesgo Mitigado: Pérdida de datos críticos en caso de un ataque o fallo del sistema.

**Planes de Recuperación:**
- Objetivo: Garantizar la capacidad de restaurar el sistema rápidamente en caso de un ataque.
- Factor de Riesgo Mitigado: Tiempo de inactividad prolongado y pérdida de confianza por parte de los usuarios debido a un compromiso del sistema.

## **8. Educación y Concientización**
**Capacitación Regular:**
- Objetivo: Mantener a los desarrolladores y administradores informados sobre las mejores prácticas de seguridad.
- Factor de Riesgo Mitigado: Errores humanos y falta de conocimiento sobre las amenazas y cómo prevenirlas.

**Cultura de Seguridad:**
- Objetivo: Fomentar una mentalidad de seguridad en toda la organización.
- Factor de Riesgo Mitigado: Comportamientos negligentes o despreocupados que podrían comprometer la seguridad del software.

## **9. Colaboración y Comunicación**
**Compartir Información:**
- Objetivo: Colaborar con otras organizaciones y comunidades para estar al tanto de nuevas amenazas.
- Factor de Riesgo Mitigado: Falta de información sobre amenazas emergentes y cómo mitigarlas.

**Alertas y Notificaciones:**
- Objetivo: Mantener a todos los stakeholders informados sobre actualizaciones críticas y posibles incidentes de seguridad.
- Factor de Riesgo Mitigado: Retrasos en la respuesta a incidentes de seguridad debido a la falta de comunicación.

#### **III.	Definición de Cadena de Suministro**

Una cadena de suministro es un sistema de organizaciones, personas, actividades, información y recursos involucrados en la entrega de un producto o servicio desde su origen hasta el consumidor final. En el contexto de software, la cadena de suministro incluye todas las etapas desde la creación del código fuente, pasando por la integración y pruebas, hasta la distribución y mantenimiento del software.

## **Relevancia en Aspectos de Ciberseguridad**
La ciberseguridad en la cadena de suministro es crucial debido a las múltiples etapas y actores involucrados, cada uno de los cuales puede ser un punto potencial de ataque. La seguridad de la cadena de suministro tiene como objetivo proteger la integridad, confidencialidad y disponibilidad del producto o servicio en cada etapa de su ciclo de vida. 

**1. Complejidad y Exposición**
- Multiplicidad de Actores: Incluye proveedores, desarrolladores, integradores, y distribuidores. Cada actor puede introducir riesgos de seguridad.
- Interdependencias: Un compromiso en una parte de la cadena puede afectar a todos los actores conectados.

**2.Diversidad de Componentes:**
- Dependencias de Terceros: El software y hardware a menudo dependen de componentes de terceros, que pueden tener vulnerabilidades.
- Software de Código Abierto: Aunque el código abierto puede aumentar la transparencia, también puede ser un vector de ataque si no se verifica adecuadamente.

**3. Ataques de la Cadena de Suministro:**
- Inserción de Código Malicioso: Los atacantes pueden comprometer el código en cualquier punto del desarrollo, integrando malware que puede propagarse a los usuarios finales.
- Compromiso de Proveedores: Atacar a proveedores menos seguros para acceder a sistemas más seguros a través de la integración de sus productos o servicios.

**4.Distribución y Actualización:**
- Manipulación durante la Distribución: Los atacantes pueden interceptar y modificar el software durante su distribución.
- Actualizaciones de Seguridad: Asegurar que las actualizaciones se distribuyan de manera segura y provengan de fuentes verificadas.

## **Contexto del Ecosistema del Ciberespacio**

En el ciberespacio, la cadena de suministro de software adquiere una relevancia particular debido a la interconexión global y la dependencia de múltiples sistemas y servicios digitales. 

**1.Escalabilidad de Ataques:**
- Propagación Rápida: Las vulnerabilidades en la cadena de suministro pueden afectar a una amplia base de usuarios de manera rápida y global.
- Efecto Multiplicador: Un solo ataque exitoso puede comprometer múltiples sistemas y organizaciones a través de actualizaciones automáticas y dependencias compartidas.

**2. Confianza y Reputación:**
- Confianza en Proveedores: Las organizaciones confían en que sus proveedores de software y hardware mantienen altos estándares de seguridad.
- Reputación de Marca: Un compromiso en la cadena de suministro puede dañar gravemente la reputación de una empresa y la confianza de sus clientes.

**3. Regulación y Cumplimiento:**
- Normativas de Seguridad: Existen regulaciones que requieren que las organizaciones aseguren sus cadenas de suministro, como el GDPR en Europa y el CCPA en California.
- Auditorías y Certificaciones: Las organizaciones deben someterse a auditorías y obtener certificaciones de seguridad que validen sus prácticas de protección de la cadena de suministro.
