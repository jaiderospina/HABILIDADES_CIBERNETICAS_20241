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

### Pag 1-6 (Grupo #1)


**Expectativas para la Respuesta a Incidentes de Seguridad Informática**
Estado de este Memorando 
Este documento especifica una de las Mejores Prácticas Actuales para la Comunidad de Internet y solicita discusión y sugerencias para mejoras. La distribución de este memorando es ilimitada. 
Aviso de Derechos de Autor 
Copyright (C) The Internet Society (1998). Todos los Derechos Reservados. 

**Resumen**
El propósito de este documento es expresar las expectativas generales de la comunidad de Internet respecto a los Equipos de Respuesta a Incidentes de Seguridad Informática (CSIRTs). No es posible definir un conjunto de requisitos que sean apropiados para todos los equipos, pero es posible y útil enumerar y describir el conjunto general de temas y cuestiones que son de interés y preocupación para las comunidades constituyentes. 
Los constituyentes de CSIRT tienen una necesidad legítima y el derecho de comprender completamente las políticas y procedimientos de 'su' Equipo de Respuesta a Incidentes de Seguridad Informática. Una forma de apoyar esta comprensión es proporcionar información detallada que los usuarios puedan considerar, en forma de una plantilla formal completada por el CSIRT. Se proporciona un esquema de dicha plantilla y un ejemplo completado. 

**Tabla de Contenidos**

   - 1 Introducción ....................................................2 
   - 2 Alcance..........................................................4 
   - 2.1 Publicación de Políticas y Procedimientos del CSIRT ..........4 
   - 2.2 Relaciones entre diferentes CSIRTs ...........................5 
   - 2.3 Establecimiento de Comunicaciones Seguras ....................6 
   - 3 Información, Políticas y Procedimientos..........................7 
   - 3.1 Obtención del Documento.......................................8 
   - 3.2 Información de Contacto ......................................9 
   - 3.3 Carta .......................................................10 
   - 3.3.1 Declaración de Misión..................................10 
   - 3.3.2 Constituencia..........................................10 
   - 3.3.3 Organización Patrocinadora / Afiliación................11 
   - 3.3.4 Autoridad..............................................11 
   - 3.4 Políticas ...................................................11 
   - 3.4.1 Tipos de Incidentes y Nivel de Soporte.................11 
   - 3.4.2 Cooperación, Interacción y Divulgación de Información.......................12 
   - 3.4.3 Comunicación y Autenticación...........................14 
   - 3.5 Servicios ...................................................15 
   - 3.5.1 Respuesta a Incidentes ................................15 
   - 3.5.1.1 Evaluación de Incidentes ......................15 
   - 3.5.1.2 Coordinación de Incidentes ....................15 
   - 3.5.1.3 Resolución de Incidentes.......................16 
   - 3.5.2 Actividades Proactivas ................................16 
   - 3.6 Formularios de Reporte de Incidentes ........................16 
   - 3.7 Descargos de Responsabilidad ................................17 
   - Apéndice A: Glosario de Términos ..................................18 
   - Apéndice B: Material Relacionado ..................................20 
   - Apéndice C: Equipos de Respuesta a Incidentes de Seguridad Informática Conocidos ......21 
   - Apéndice D: Esquema para la Plantilla del CSIRT ...................22 
   - Apéndice E: Ejemplo - Plantilla Completada para un CSIRT ..........23 
   - 4 Agradecimientos .................................................36 
   - 5 Referencias .....................................................36 
   - 6 Consideraciones de Seguridad ....................................36 
   - 7 Direcciones de los Autores ......................................37 
   - 8 Declaración Completa de Derechos de Autor .......................38 

 **1 Introducción**
 
El Grupo de Trabajo GRIP se formó para crear un documento que describa las expectativas de la comunidad respecto a los equipos de respuesta a incidentes de seguridad informática (CSIRTs). Aunque la necesidad de dicho documento surgió en la comunidad general de Internet, las expectativas expresadas también deberían coincidir estrechamente con las de comunidades más restringidas.

En el pasado ha habido malentendidos sobre lo que se debe esperar de los CSIRTs. El objetivo de este documento es proporcionar un marco para presentar los temas importantes (relacionados con la respuesta a incidentes) que son de interés para la comunidad. 

Antes de continuar, es importante entender claramente qué se entiende por el término "Equipo de Respuesta a Incidentes de Seguridad Informática." Para los fines de este documento, un CSIRT es un equipo que realiza, coordina y apoya la respuesta a incidentes de seguridad que involucran sitios dentro de una comunidad definida (ver Apéndice A para una definición más completa). Cualquier grupo que se llame a sí mismo CSIRT para una comunidad específica debe, por lo tanto, reaccionar ante incidentes de seguridad reportados y amenazas a "su" comunidad de maneras que la comunidad específica acuerde que son de su interés general.

Dado que es vital que cada miembro de una comunidad constituyente pueda entender lo que es razonable esperar de su equipo, un CSIRT debe dejar claro quién pertenece a su comunidad y definir los servicios que el equipo ofrece a la comunidad. Además, cada CSIRT debe publicar sus políticas y procedimientos operativos. De manera similar, estos mismos constituyentes necesitan saber qué se espera de ellos para recibir los servicios de su equipo. Esto requiere que el equipo también publique cómo y dónde reportar incidentes. 

Este documento detalla una plantilla que será utilizada por los CSIRTs para comunicar esta información a sus constituyentes. Los constituyentes ciertamente deben esperar que un CSIRT proporcione los servicios que describen en la plantilla completada. Debe enfatizarse que sin la participación activa de los usuarios, la efectividad de los servicios del CSIRT puede verse muy disminuida. 
 Esto es particularmente cierto en el caso de los reportes. Como mínimo, los usuarios necesitan saber que deben reportar incidentes de seguridad, y saber cómo y dónde deben reportarlos. 
 
Muchos incidentes de seguridad informática se originan fuera de los límites de la comunidad local y afectan sitios internos; otros se originan dentro de la comunidad local y afectan a hosts o usuarios en el exterior. A menudo, por lo tanto, el manejo de incidentes de seguridad involucrará múltiples sitios y potencialmente múltiples CSIRTs. Resolver estos incidentes requerirá cooperación entre sitios individuales y CSIRTs, y entre CSIRTs. 

Las comunidades constituyentes necesitan saber exactamente cómo su CSIRT trabajará con otros CSIRTs y organizaciones fuera de su comunidad, y qué información se compartirá. 

El resto de este documento describe el conjunto de temas y cuestiones que los CSIRTs necesitan elaborar para sus constituyentes. Sin embargo, no se intenta especificar la respuesta "correcta" a ningún área temática en particular. Más bien, cada tema se discute en términos de lo que ese tema significa. 

El capítulo dos proporciona una visión general de tres áreas principales: la publicación de información por parte de un equipo de respuesta, la definición de la relación del equipo de respuesta con otros equipos de respuesta, y la necesidad de comunicaciones seguras. El capítulo tres describe en detalle todos los tipos de información que la comunidad necesita saber sobre su equipo de respuesta. 

Para facilitar el uso por parte de la comunidad, estos temas se condensan en una plantilla de esquema que se encuentra en el Apéndice D. Esta plantilla puede ser utilizada por los constituyentes para obtener información de su CSIRT. 
Es la sincera esperanza del grupo de trabajo que, mediante la clarificación de los temas en este documento, se aumente la comprensión entre la comunidad y sus CSIRTs. 


**2 Alcance**

Las interacciones entre un equipo de respuesta a incidentes y su comunidad constituyente requieren primero que la comunidad comprenda las políticas y procedimientos del equipo de respuesta. 

En segundo lugar, dado que muchos equipos de respuesta colaboran para manejar incidentes, la comunidad también debe comprender la relación entre su equipo de respuesta y otros equipos. Finalmente, muchas interacciones aprovecharán las infraestructuras públicas existentes, por lo que la comunidad necesita saber cómo se protegerán esas comunicaciones. Cada uno de estos temas se describirá con más detalle en las siguientes tres secciones. 

**2.1 Publicación de Políticas y Procedimientos del CSIRT**

Cada usuario que tenga acceso a un Equipo de Respuesta a Incidentes de Seguridad Informática debe saber tanto como sea posible sobre los servicios y las interacciones con este equipo mucho antes de que él o ella realmente los necesite. 

Una declaración clara de las políticas y procedimientos de un CSIRT ayuda a los constituyentes a comprender la mejor manera de reportar incidentes y qué apoyo esperar después. ¿Ayudará el CSIRT a resolver el incidente? ¿Proporcionará ayuda para evitar incidentes en el futuro? Las expectativas claras, particularmente sobre las limitaciones de los servicios proporcionados por un CSIRT, harán que la interacción con él sea más eficiente y efectiva. 

Existen diferentes tipos de equipos de respuesta: algunos tienen comunidades muy amplias (por ejemplo, el Centro de Coordinación CERT y la Internet), otros tienen comunidades más delimitadas (por ejemplo, DFN-CERT, CIAC), y otros tienen comunidades muy restringidas (por ejemplo, equipos de respuesta comerciales, equipos de respuesta corporativos). Independientemente del tipo de equipo de respuesta, la comunidad apoyada por él debe estar informada sobre las políticas y procedimientos del equipo. Por lo tanto, es obligatorio que los equipos de respuesta publiquen dicha información para su comunidad. 

Un CSIRT debe comunicar toda la información necesaria sobre sus políticas y servicios en una forma adecuada a las necesidades de su comunidad. Es importante entender que no todas las políticas y procedimientos necesitan ser de acceso público. Por ejemplo, no es necesario comprender la operación interna de un equipo para interactuar con él, como cuando se reporta un incidente o se recibe orientación sobre cómo analizar o asegurar los sistemas. 

En el pasado, algunos equipos proporcionaban una especie de Marco Operativo, otros proporcionaban una lista de Preguntas Frecuentes (FAQ), mientras que otros escribían documentos para distribuir en conferencias de usuarios o enviaban boletines informativos. 
Recomendamos que cada CSIRT publique sus directrices y procedimientos en su propio servidor de información (por ejemplo, un servidor web). Esto permitiría a los constituyentes acceder fácilmente a él, aunque el problema sigue siendo cómo un constituyente puede encontrar su equipo; las personas dentro de la comunidad deben descubrir que hay un CSIRT "a su disposición." Se prevé que las plantillas completadas del CSIRT pronto serán buscables por motores de búsqueda modernos, lo que ayudará a distribuir información sobre la existencia de CSIRTs y la información básica necesaria para acercarse a ellos. 

Sería muy útil tener un repositorio central que contenga todas las plantillas completadas del CSIRT. No existe tal repositorio en el momento de escribir este documento, aunque esto podría cambiar en el futuro. 

Independientemente de la fuente de la que se obtenga la información, el usuario de la plantilla debe verificar su autenticidad. Es muy recomendable que dichos documentos vitales estén protegidos por firmas digitales. Estas permitirán al usuario verificar que la plantilla fue efectivamente publicada por el CSIRT y que no ha sido manipulada. Este documento asume que el lector está familiarizado con el uso adecuado de las firmas digitales para determinar si un documento es auténtico. 


**2.2 Relaciones entre Diferentes CSIRTs**

En algunos casos, un CSIRT puede operar de manera efectiva por sí solo y en estrecha cooperación con su comunidad. Pero con las redes internacionales de hoy, es mucho más probable que la mayoría de los incidentes manejados por un CSIRT involucren a partes externas a su comunidad. Por lo tanto, el equipo necesitará interactuar con otros CSIRTs y sitios fuera de su comunidad. La comunidad constituyente debe comprender la naturaleza y el alcance de esta colaboración, ya que información muy sensible sobre constituyentes individuales puede ser divulgada en el proceso. 

Las interacciones entre CSIRTs pueden incluir solicitar consejos a otros equipos, difundir conocimientos sobre problemas y trabajar cooperativamente para resolver un incidente de seguridad que afecte a una o más de las comunidades de los CSIRTs. 
Al establecer relaciones para apoyar tales interacciones, los CSIRTs deben decidir qué tipos de acuerdos pueden existir entre ellos para compartir y proteger la información, si esta relación puede ser divulgada y, de ser así, a quién. 
Tenga en cuenta que hay una diferencia entre un acuerdo de pares, donde los CSIRTs involucrados acuerdan trabajar juntos y compartir información, y una simple cooperación, donde un CSIRT (o cualquier otra organización) simplemente contacta a otro CSIRT y solicita ayuda o consejo. 

Aunque el establecimiento de tales relaciones es muy importante y afecta la capacidad de un CSIRT para apoyar a su comunidad, depende de los equipos involucrados decidir sobre los detalles. Está más allá del alcance de este documento hacer recomendaciones para este proceso. Sin embargo, el mismo conjunto de información utilizado para establecer expectativas para una comunidad de usuarios con respecto al intercambio de información ayudará a otras partes a comprender los objetivos y servicios de un CSIRT específico, apoyando un primer contacto. 

**2.3 Establecimiento de Comunicaciones Seguras**

Una vez que una parte ha decidido compartir información con otra parte, o dos partes han acordado compartir información o trabajar juntas, como se requiere para la coordinación de la respuesta a incidentes de seguridad informática, todas las partes involucradas necesitan canales de comunicación seguros. (En este contexto, "seguro" se refiere a la transmisión protegida de información compartida entre diferentes partes, y no al uso adecuado de la información por parte de las partes.) Los objetivos de la comunicación segura son: 

   - Confidencialidad:
        ¿Puede alguien más acceder al contenido de la comunicación? 
   - Integridad: 
        ¿Puede alguien más manipular el contenido de la comunicación? 
   - Autenticidad: 
        ¿Estoy comunicándome con la persona "correcta"?
     
Es muy fácil enviar correos electrónicos falsificados y no es difícil establecer una identidad (falsa) por teléfono. Las técnicas criptográficas, por ejemplo Pretty Good Privacy (PGP) o Privacy Enhanced Mail (PEM), pueden proporcionar formas efectivas de asegurar el correo electrónico. Con el equipo adecuado también es posible asegurar la comunicación telefónica. Pero antes de usar tales mecanismos, ambas partes necesitan la infraestructura "correcta", lo que significa preparación por adelantado. La preparación más importante garantizar la autenticidad de las claves criptográficas utilizadas en la comunicación segura: 


**Grupo No. 2 Pag 7-12**

•	Claves públicas (para técnicas como PGP y PEM): Debido a que son accesibles a través de Internet, las claves públicas deben ser     autenticadas antes de su uso. Mientras que PGP se basa en una "Red de Confianza" (donde los usuarios firman las claves de otros usuarios), PEM se basa en una jerarquía (donde las autoridades de certificación firman las claves de los usuarios).

•	Claves secretas (para técnicas como DES y PGP/cifrado convencional): Debido a que deben ser conocidas tanto por el remitente como por el receptor, las claves secretas deben intercambiarse antes de la comunicación a través de un canal seguro.

La comunicación es fundamental para todos los aspectos de la respuesta a incidentes. Un equipo puede apoyar mejor el uso de las técnicas mencionadas anteriormente reuniendo toda la información relevante, de manera consistente. Requisitos específicos (como llamar a un número específico para verificar la autenticidad de las claves) debe quedar claro desde el principio. Las plantillas CSIRT proporcionan un vehículo estandarizado para entregar esta información. 

Está fuera del alcance de este documento abordar los problemas técnicos y problemas administrativos de las comunicaciones seguras. El punto es que los equipos de respuesta deben apoyar y utilizar un método para asegurar la comunicaciones entre ellos y sus electores (u otros equipos de respuesta). Cualquiera que sea el mecanismo, el nivel de protección debe ser aceptable para la comunidad constituyente.

**3 Información, Políticas y Procedimientos**

En el capítulo 2 se mencionó que las políticas y procedimientos de un equipo de respuesta necesita ser publicado en la comunidad que los constituye. En este capítulo enumeraremos todos los tipos de información que la comunidad necesita recibir de su equipo de respuesta. La forma en que se comunica esta información a una comunidad diferirá de un equipo a otro, al igual que el contenido de la información específica. La intención aquí es describir claramente los diversos tipos de información que una comunidad constituyente espera de su equipo de respuesta.

Para facilitar la comprensión de las cuestiones y temas relevantes para la interacción de los electores con "su" CSIRT, sugerimos que un CSIRT publique toda la información, políticas y procedimientos dirigidos a sus electores como un documento, siguiendo la plantilla proporcionada en el Apéndice D. La estructura de la plantilla organiza los elementos, lo que facilita el suministro de información específica; en el Apéndice E proporcionamos un ejemplo de una plantilla completa para la Universidad XYZ ficticia. Si bien no se hacen recomendaciones sobre lo que un CSIRT debería adoptar para su política o procedimientos, se describen diferentes posibilidades para brindar

algunos ejemplos. Lo más importante es que un CSIRT tenga una política y que quienes interactúan con el CSIRT puedan obtenerla y comprenderla. 

Como siempre, no se pueden cubrir todos los aspectos de cada entorno y/o equipo. Este esquema debe verse como una sugerencia. Cada equipo debe sentirse libre de incluir lo que crea necesario para apoyar a su electorado.

**3.1 Obtención del Documento**

Los detalles de un CSIRT cambian con el tiempo, por lo que la plantilla completa debe indicar cuándo se modificó por última vez. Además, se debe proporcionar información sobre cómo enterarse de futuras actualizaciones. Sin esto, es inevitable que con el tiempo surjan malentendidos y conceptos erróneos; Los documentos obsoletos pueden hacer más daño que bien.

­­ Fecha de la última actualización:		            Esto debería ser suficiente para permitir cualquier persona interesada en evaluar                                                      la versión de la plantilla.

­ Lista de distribución:	                           Las listas de correo son un mecanismo conveniente para distribuir información                                                          actualizada a una gran cantidad de usuarios. Un equipo puede decidir utilizar su                                                       propia o una lista ya existente para notificar a los usuarios cada vez que el                                                          documento cambia. La lista normalmente podría incluir grupos con los que el CSIRT                                                      tiene interacciones frecuentes.

                                                   Se deben utilizar firmas digitales para los mensajes de actualización enviados por                                                     un CSIRT.
                                                   
­ Ubicación del documento:		                     La ubicación donde se encuentra una versión actual del documento es accesible a                                                        través de los servicios de información en línea del equipo. Los integrantes pueden                                                     entonces aprender más fácilmente sobre el equipo y comprobar si actualizaciones                                                        recientes. Esta versión en línea también deberá ir acompañada de una firma digital

**3.2 Información de contacto**

Aquí se deben enumerar todos los detalles sobre cómo contactar al CSIRT, aunque esto puede ser muy diferente para diferentes equipos; por ejemplo, algunos podrían optar por no publicar los nombres de los miembros de su equipo. No se dan más aclaraciones cuando se puede asumir el significado del ítem.

-­ Nombre del CSIRT

­- Dirección de envio

­ - Zona horaria:	               Esto es útil para coordinar incidentes que cruzan zonas horarias.

­ - Número de teléfono

­ - Número de fax

­ - Otras telecomunicaciones:		Algunos equipos pueden proporcionar comunicaciones de voz seguras (por ejemplo, STU III).

­ - Dirección de correo electrónico

­ - Claves públicas y cifrado: 		El uso de técnicas específicas depende de la capacidad de los interlocutores de comunicación para                                      tener acceso a programas, claves, etc. Se debe proporcionar información pertinente para que los                                        usuarios puedan determinar si pueden utilizar comunicaciones cifradas y cómo hacerlo mientras                                          interactúan con el CSIRT.

- Miembros del equipo
 
- Horas de funcionamiento:        El horario de funcionamiento y el calendario de días festivos deben proporcionarse aquí.
                                 ¿Hay una línea directa las 24 horas?

- Información de contacto adicional: ¿Existe alguna información de contacto específica del cliente?
 
Se puede proporcionar información de contacto más detallada. Esto podría incluir diferentes contactos para diferentes servicios o podría ser una lista de servicios de información en línea. Si existen procedimientos específicos para acceder a algunos servicios (por ejemplo, direcciones para solicitudes de listas de correo), deben explicarse aquí.

**3.3 Carta**

Cada CSIRT debe tener un estatuto que especifique lo que debe hacer y la autoridad bajo la cual lo hará. La carta debe incluir al menos los siguientes elementos:

- Estado de la misión
- circunscripción
- Patrocinio / afiliación
-­ Autoridad

**3.3.1 Declaración de misión**

La declaración de misión debe centrarse en las actividades principales del equipo, ya establecidas en la definición de CSIRT. Para ser considerado un equipo de respuesta a incidentes de seguridad informática, el equipo debe respaldar la notificación de incidentes y respaldar a sus integrantes al abordar los incidentes.

Las metas y propósitos de un equipo son especialmente importantes y requieren una definición clara e inequívoca.

**3.3.2 Circunscripción**

La circunscripción de un CSIRT se puede determinar de varias maneras. Por ejemplo, podrían ser los empleados de una empresa o sus suscriptores pagos, o podría definirse en términos de un enfoque tecnológico, como los usuarios de un sistema operativo en particular.

La definición de la circunscripción debe crear un perímetro alrededor del grupo al que el equipo prestará servicios. La sección de política del documento (ver más abajo) debe explicar cómo se manejarán las solicitudes provenientes de fuera de este perímetro.

Si un CSIRT decide no revelar su electorado, debe explicar el razonamiento detrás de esta decisión. Por ejemplo, los CSIRT que cobran una tarifa no enumerarán a sus clientes, pero declararán que brindan un servicio a un gran grupo de clientes que se mantiene confidencial debido a los contratos de los clientes.

Los distritos electorales pueden superponerse, como cuando un ISP proporciona un CSIRT que presta servicios a sitios de clientes que también tienen CSIRT. El La sección de autoridad de la descripción del CSIRT (ver más abajo) debe dejar claras dichas relaciones.

**3.3.3 Organización patrocinadora/afiliación**

A continuación se debe indicar la organización patrocinadora que autoriza las acciones del CSIRT. Saber esto ayudará a los usuarios a comprender los antecedentes y la configuración del CSIRT, y es información vital para generar confianza entre un elector y un CSIRT.

**3.3.4 Autoridad**

Esta sección variará mucho de un CSIRT a otro, según la relación entre el equipo y sus integrantes. Mientras que un CSIRT organizacional recibirá su autoridad de la dirección de la organización, un CSIRT comunitario será apoyado y elegido por la comunidad, generalmente en una función de asesoramiento.

Un CSIRT puede tener o no autoridad para intervenir en el funcionamiento de todos los sistemas dentro de su perímetro. Debe identificar el alcance de su control a diferencia del perímetro de su electorado. Si otros CSIRT operan jerárquicamente dentro de su perímetro, esto debe mencionarse aquí e identificarse los CSIRT relacionados.

La divulgación de la autoridad de un equipo puede exponerlo a reclamaciones de responsabilidad. Cada equipo debe buscar asesoramiento legal sobre estos asuntos. (Consulte la sección 3.7 para obtener más información sobre responsabilidad).

**3.4 Políticas**

Es fundamental que los equipos de respuesta a incidentes definan sus políticas. Las siguientes secciones analizan la comunicación de estas políticas a la comunidad constituyente.

**3.4.1 Tipos de incidentes y nivel de soporte**

Los tipos de incidentes que el equipo puede abordar y el nivel de soporte que ofrecerá el equipo al responder a cada tipo de incidente deben resumirse aquí en forma de lista. La sección Servicios (ver más abajo) brinda la oportunidad de brindar descripciones más detalladas y abordar temas no relacionados con incidentes.

El nivel de soporte puede cambiar dependiendo de factores como la carga de trabajo del equipo y la integridad de la información disponible. Estos factores deberían describirse y explicarse sus repercusiones. Como una lista de tipos conocidos de incidentes estará incompleta con respecto a incidentes posibles o futuros, un CSIRT también debe brindar algunos antecedentes sobre el soporte "predeterminado" para tipos de incidentes que no se mencionan de otra manera.

El equipo debe indicar si actuará según la información que reciba sobre vulnerabilidades que crean oportunidades para incidentes futuros. El compromiso de actuar sobre dicha información en nombre de sus electores se considera una política de servicio proactiva opcional y no un requisito de servicio básico para un CSIRT.

**3.4.2 Cooperación, interacción y divulgación de información**

Esta sección debe dejar explícito con qué grupos relacionados interactúa habitualmente el CSIRT. Dichas interacciones no están necesariamente relacionadas con la respuesta proporcionada al incidente de seguridad informática, pero se utilizan para facilitar una mejor cooperación en temas o servicios técnicos. De ninguna manera es necesario dar detalles sobre los acuerdos de cooperación; El principal objetivo de esta sección es brindar a los electores una comprensión básica de qué tipo de interacciones se establecen y cuál es su propósito.

La cooperación entre CSIRT puede facilitarse mediante el uso de una asignación de número de billete único combinada con procedimientos de transferencia explícitos. Esto reduce la posibilidad de malentendidos, duplicaciones de esfuerzos, ayuda en el seguimiento de incidentes y evita "bucles" en la comunicación.

La política de presentación de informes y divulgación debe dejar claro quiénes serán los destinatarios del informe de un CSIRT en cada circunstancia. También debe indicar si el equipo espera operar a través de otro CSIRT o directamente con un miembro de otro grupo sobre asuntos que conciernen específicamente a ese miembro.

Los grupos relacionados con los que interactuará un CSIRT se enumeran a continuación:

Equipos de respuesta a incidentes: 
   un CSIRT a menudo necesitará interactuar con otros CSIRT. Para Por ejemplo, un CSIRT de una gran empresa puede necesitar informar incidentes a un CSIRT nacional, y un CSIRT nacional puede necesitar informar incidentes a CSIRT nacionales de otros países para ocuparse de todos los sitios involucrados en un ataque a gran escala.

La colaboración entre CSIRT puede dar lugar a la divulgación de información. Los siguientes son ejemplos de dicha divulgación, pero no pretenden ser una lista exhaustiva:

­- Informar de incidencias dentro de la circunscripción a otros equipos. Si se hace esto, la información relacionada con el sitio puede llegar a ser de conocimiento público, accesible a todos, en particular a la prensa.

­- Manejar los incidentes que ocurran dentro de la circunscripción, pero reportado desde fuera (lo que implica que parte de la información ya ha sido divulgada fuera del sitio).

**Aporte grupo 3**
**RFC 2350 pag. 13-18**

- Reportar observaciones dentro de la circunscripción que indiquen incidentes sospechados o confirmados fuera del mismo.
- Actuar ante reportes de incidentes por fuera de la circunscripción.
- Pasar información sobre vulnerabilidades a los proveedores, a CSIRTs asociados o directamente a los sitios afectados que se encuentran dentro o fuera de la circunscripción.
- Retroalimentar a las partes que reportan incidentes o vulnerabilidades.
- El suministro de información de contacto relativa a los miembros de la circunscripción, los miembros de otras circunscripciones, otros CSIRT o agencias encargadas de hacer cumplir la ley.
 Vendedores:
Algunos proveedores tienen sus propios CSIRT, pero es posible que otros no. En tales casos, un CSIRT deberá trabajar directamente con un proveedor para sugerir mejoras o modificaciones, analizar el problema técnico o probar las soluciones proporcionadas. Los vendedores juegan un papel especial en el manejo de un incidente si las vulnerabilidades de sus productos están involucradas en el incidente.

Entidades estatales de seguridad:
Estos incluyen la policía y otras agencias de investigación. CSIRT y los usuarios de la plantilla deben ser sensibles a las leyes locales y regulaciones, que pueden variar considerablemente en diferentes países. Un CSIRT podría asesorar sobre los detalles técnicos de los ataques o buscar Asesoramiento sobre las implicaciones legales de un incidente. Las leyes locales y Las regulaciones pueden incluir informes específicos y confidencialidad.

Prensa:
La prensa puede contactar a un CSIRT para obtener información y comentarios. de vez en cuando.
Puede ser útil una política explícita sobre divulgación de información a la prensa, particularmente para aclarar las expectativas de la circunscripción de un CSIRT. La política de manejo de prensa deberá aclarar lo mismo temas como se indica arriba más específicamente, ya que la circunscripción suele ser muy sensibles al contacto con la prensa.

Otro:
Esto podría incluir actividades de investigación o la relación con la organización patrocinadora.
El estado predeterminado de toda la información relacionada con la seguridad que recibe un equipo suele ser "confidencial", pero el cumplimiento estricto de esto hace que el equipo parezca un "agujero negro" informativo, lo que puede reducir la probabilidad de que el equipo obtenga cooperación de clientes y de otras organizaciones. La plantilla del CSIRT debe definir qué información reportará o revelará, a quién, y cuando.

Es probable que diferentes equipos estén sujetos a diferentes restricciones legales. o limitantes a la divulgación, especialmente si funcionan en diferentes jurisdicciones. Además, pueden tener requerimientos de reportes impuestos por su organización patrocinadora. La plantilla de cada equipo debe especificar tales restricciones, tanto para aclarar las expectativas de los usuarios como para informar a otros equipos.

Los conflictos de intereses, particularmente en asuntos comerciales, también pueden restringir la divulgación por parte de un equipo; este documento no hace recomendaciones sobre cómo deben abordarse esos conflictos.

Normalmente, un equipo recopilará estadísticas. Si la información estadística se distribuye, la política de información y divulgación de la plantilla debe decirlo y describir cómo obtener dichas estadísticas.

3.4.3 Comunicación y autenticación

Usted debe tener una política que describa los métodos de comunicación segura y verificable que utilizará. Esto es necesario para comunicación entre un CSIRT y su circunscripción. La plantilla debe incluir claves públicas o direcciones hacia ellas, incluyendo huellas dactilares clave, junto con directrices sobre cómo utilizar esta información para comprobar la autenticidad y actuar al encontrar información corrupta (por ejemplo, dónde reportar esto).

Al momento se recomienda que, como mínimo, cada CSIRT tenga (si es posible), una clave PGP disponible. Un equipo también puede hacer disponibles otros mecanismos (por ejemplo PEM, MOSS, S/MIME), según sus necesidades y las necesidades de su circunscripción. Tenga en cuenta, sin embargo, que los CSIRT y los usuarios deben conocer las leyes y regulaciones locales Algunos países no permiten cifrados fuertes, o imponen políticas sobre el uso de tecnología de cifrado. Además de cifrar información confidencial siempre que sea posible, la correspondencia debe incluir firmas digitales. (Tenga en cuenta que en la mayoría de los países, la protección de la autenticidad mediante el uso de firmas digitales no se ve afectado por las regulaciones existentes sobre cifrado).

Para la comunicación por teléfono o fax, un CSIRT podrá mantener en secreto datos de autenticación para las partes con las que puedan tratar, como por ejemplo un contraseña o frase clave acordada. Obviamente, dichas claves secretas no deben ser
publicadas, aunque su existencia pueda serlo.

3.5 Servicios

Los servicios proporcionados por un CSIRT se pueden dividir en dos categorías: actividades en tiempo real directamente relacionadas con la tarea principal de respuesta a incidentes, y actividades proactivas no en tiempo real de apoyo a la tarea de respuesta a incidentes. La segunda categoría y parte de la primera categoría consisten en servicios que son opcionales en el sentido que no todos los CSIRT los ofrecerán.

3.5.1 Respuesta a incidentes

La respuesta a incidentes generalmente incluye la evaluación de informes entrantes sobre incidentes ("Triage de incidentes") y darles seguimiento con otros CSIRT, ISP y sitios ("Coordinación de incidentes"). Una tercera gama de servicios, ayudar a un sitio local a recuperarse de un incidente ("Resolución de incidentes"), se compone de servicios típicamente opcionales, que no todos los CSIRT ofrecerán.

3.5.1.1 Triage de incidentes

La clasificación de incidentes generalmente incluye:

 - Evaluación de reportes: Interpretación de reportes de incidentes entrantes, priorizarlos y relacionarlos con incidentes en curso y tendencias.
 - Verificación Ayuda para determinar si un incidente realmente ha ocurrido y su alcance.
 - 
3.5.1.2 Coordinación de incidentes
   
La coordinación de incidentes normalmente incluye:

 - Categorización de información: Categorización de la información relacionada al incidente (archivos de registro, información de contacto, etc.) con respecto a la política de divulgación de información.
 - Coordinación: Notificación a otras partes involucradas cuando lo necesiten, según la política de divulgación de información.
 
3.5.1.3 Resolución de incidentes
   
Generalmente adicionales u opcionales, los servicios de resolución de incidentes incluyen:

 - Asistencia Técnica: Esto puede incluir análisis de sistemas comprometidos.
 - Erradicación: Eliminación de la causa de un incidente de seguridad (la vulnerabilidad explotada), y de sus efectos (por ejemplo, acceso continuado al sistema por un intruso).
 - Recuperación: Ayuda en la restauración de los sistemas y servicios afectados a su estado antes del incidente de seguridad.
 - 
3.5.2. Actividades proactivas
   
Generalmente adicionales u opcionales, los servicios de resolución de incidentes incluyen:

 - Suministro de información: Esto podría incluir un archivo de vulnerabilidades conocidas, parches o resoluciones de problemas pasados, o listas de correo de asesoramiento.
 - Herramientas de seguridad: Esto puede incluir herramientas para auditar la seguridad de un sitio.
 - Educación y entrenamiento
 - Evaluación del producto
 - Auditoría y consultoría de seguridad del sitio.
   
3.6 Formularios de reporte de incidentes

El uso de formularios de reportes hace que responder ante incidentes sea más sencillo tanto para los usuarios como para los equipos para hacer frente a incidentes. El cliente puede preparar respuestas a varias preguntas importantes antes de que él o ella realmente se comunique con el equipo y, por lo tanto, puede venir bien preparado. El equipo obtiene toda la información necesaria inmediatamente con el primer reporte y puede continuar eficientemente.

Dependiendo de los objetivos y servicios de un CSIRT en particular, se pueden utilizar varios formularios, por ejemplo un formulario de reporte para una nueva vulnerabilidad puede ser muy diferente del formulario utilizado para reportar incidentes.

Lo más eficiente es proporcionar formularios a través de los servicios de información en línea. del equipo. Las indicaciones exactas para descargarlos deben darse en el documento de descripción del CSIRT, junto con declaraciones sobre uso apropiado y pautas sobre cuándo y cómo usar los formularios. Si se admiten direcciones de correo electrónico independientes para reportes basados en formularios deberían listarse aquí nuevamente.

Un ejemplo de dicho formulario es el Formulario de reporte de incidentes proporcionado por el Centro de Coordinación CERT:

 - ftp://info.cert.org/incident_reporting_form
   
3.7 Descargos de responsabilidad

Aunque el documento de descripción del CSIRT no constituye un contrato, sus descripciones de servicios y propósitos podrían generar responsabilidades legales. Por tanto, se recomienda incluir un descargo de responsabilidad al final de la plantilla la cual debe advertir al usuario sobre posibles limitaciones.

En situaciones donde la versión original de un documento deba ser  traducida a otro idioma, la traducción debe llevar un  descargo de responsabilidad indicar como leer el original. Por ejemplo: 

Aunque intentamos traducir cuidadosamente el documento original del alemán al inglés, no podemos estar seguros de que ambos documentos expresan los mismos pensamientos con el mismo nivel de detalle. y corrección. En todos los casos, donde hay una diferencia entre ambas versiones prevalecerá la versión alemana.

El uso y la protección de las exenciones de responsabilidad se ven afectados por las leyes y normas locales que todo CSIRT debe conocer. En caso de duda el CSIRT debe verificar el descargo de responsabilidad con un abogado.
 
Apéndice A: Glosario de términos

Este glosario define los términos utilizados para describir incidentes de seguridad y Equipos de Respuesta a Incidentes de Seguridad Informática. Sólo se incluye una lista limitada. Para obtener más definiciones, consulte otras fuentes, para ejemplo el Glosario del usuario de Internet [RFC 1983].

Circunscripción:

La existencia de una circunscripción está implícita en el propósito de un CSIRT. Este es el grupo de usuarios, sitios, redes u organizaciones atendidas por el equipo. El equipo debe ser reconocido por los miembros de du circunscripción para poder ser efectivo.

Incidente de seguridad:

Para los fines de este documento, este término es sinónimo de Incidente de Seguridad Informática: cualquier evento adverso que comprometa algún aspecto de seguridad informática o de red.

La definición de incidente puede variar entre organizaciones, pero al menos las siguientes categorías son generalmente aplicables:

 - Pérdida de confidencialidad de la información.
 - Compromiso de la integridad de la información.
 - Negación de servicio.
 - Mal uso del servicio, sistemas o información.
 - Daños a los sistemas.
   
Estas son categorías muy generales. Por ejemplo, el reemplazo de un programa de utilidad del sistema por parte de un Troyano es un ejemplo de “compromiso de la integridad”, y un ataque exitoso a una contraseña es un ejemplo de “pérdida de confidencialidad”. Los ataques, incluso si fallan debido a la protección adecuada, pueden considerarse Incidentes.

Dentro de la definición de incidente, la palabra "comprometido" es usada. A veces un administrador sólo puede "sospechar" un incidente. Durante la respuesta se debe establecer si realmente ha ocurrido un incidente.

Equipo de respuesta a incidentes de seguridad informática:

Según las dos definiciones dadas anteriormente, un CSIRT es un equipo que coordina y apoya la respuesta a incidentes de seguridad que involucran sitios dentro de una circunscripción definida.

Para ser considerado un CSIRT, un equipo debe:

 - Proporcionar un canal (seguro) para recibir informes sobre incidentes sospechosos.

   
**Fin aporte grupo 3**

**Aporte grupo 5**
**RFC 2350 Expectativas de respuesta a incidentes de seguridad informática junio de 1998** **Pag. 25-30**

2.9 Miembros del equipo 
 
Zoe Doe de Computing Services es la coordinadora de XYZ-CERT. 
Los coordinadores de respaldo y otros miembros del equipo, junto con sus áreas de experiencia y información de contacto, se enumeran en las páginas web de XYZ-CERT, en http://www.xyz-univ.ca/xyz-cert/teamlist.html 
 
La gestión, el enlace y la supervisión son proporcionados por Steve Tree, Director Adjunto (Servicios Técnicos), Servicios de Computación. 
 
2.10 Otras informaciones 
 
La información general sobre el XYZ-CERT, así como los enlaces a varios recursos de seguridad recomendados, se pueden encontrar en http://www.xyz-univ.ca/xyz-cert/index.html 
 
2.11 Puntos de contacto con el cliente 
 
El método preferido para ponerse en contacto con el XYZ-CERT es por correo electrónico a <xyz-cert@xyz - univ.ca>; el correo electrónico enviado a esta dirección "biff" al humano responsable, o se reenvía automáticamente a la persona de respaldo apropiada, inmediatamente.  Si necesita asistencia urgente, coloque "urgente" en su línea de tema. 
 
Si no es posible (o no es aconsejable por razones de seguridad) utilizar el correo electrónico, el XYZ-CERT se puede llegar por teléfono durante las horas ordinarias de oficina.  Los mensajes telefónicos son revisados con menos frecuencia que los correos electrónicos. 
 
Las horas de funcionamiento del XYZ-CERT se limitan generalmente a las horas normales de trabajo (09:00-17:00 de lunes a viernes, excepto los días festivos). 
 
Si es posible, al presentar su informe, utilice el formulario mencionado en la sección 6. 
 
 
RFC 2350 Expectativas de respuesta a incidentes de seguridad informática junio de 1998 
 
 
 3. Carta 
 
3.1 Declaración de la misión 
 
El objetivo del XYZ-CERT es, en primer lugar, ayudar a los miembros de la comunidad de la Universidad de XYZ en la aplicación de medidas proactivas para reducir los riesgos de los incidentes de seguridad informática, y en segundo lugar, para ayudar a la comunidad XYZ a responder a esos incidentes cuando ocurran. 
 
   3.2 Electorado 
 
La circunscripción electoral de XYZ-CERT es la comunidad universitaria XYZ, tal como se define en el contexto de la "Política de la Universidad XYZ sobre instalaciones de computación".  Esta política está disponible en http://www-compserv.xyz-univ.ca/policies/pcf.html 
 
Sin embargo, tenga en cuenta que, sin perjuicio de lo anterior, los servicios de XYZ-CERT se prestarán únicamente para los sistemas en el lugar. 
 
3.3 Patrocinio y/o afiliación 
 
El XYZ-CERT es patrocinado por la ACME Canadian Research Network.  Mantiene afiliaciones con varios CSIRT universitarios en todo el Canadá y los EE.UU. según sea necesario. 
 
   3.4 Autoridad 
 
El XYZ-CERT opera bajo los auspicios y con la autoridad delegada por el Departamento de Servicios de Computación de la Universidad XYZ.  Para obtener más información sobre el mandato y la autoridad del Departamento de Servicios de Computación, consulte la "Política sobre instalaciones de computación" de la Universidad XYZ, disponible en http://www-compserv.xyz-univ.ca/policies/pcf.html 
 
El XYZ-CERT espera trabajar de manera cooperativa con los administradores de sistemas y usuarios de la Universidad XYZ y, en la medida de lo posible, evitar relaciones autoritarias.  Sin embargo, si las circunstancias lo justifican, XYZ-CERT recurrirá a los Servicios de Computación para ejercer su autoridad, directa o indirectamente, según sea necesario.  Todos los miembros del XYZ-CERT son miembros del CCSA (Comité de Administradores de Sistemas Informáticos), y tienen todos los poderes y responsabilidades asignados a los administradores de sistemas por la Política sobre las instalaciones de computación, o son miembros de la gestión de la Universidad.  
 
Los miembros de la comunidad de la Universidad XYZ que deseen apelar las acciones del XYZ-CERT deben ponerse en contacto con el Director Adjunto (Servicios Técnicos), Servicios de Computación.  Si este recurso no es satisfactorio, el asunto puede ser remitido al Director de Servicios de Computación (en caso de problemas percibidos con la política existente), o a la Oficina de Derechos y Responsabilidades de la Universidad XYZ (en el caso de errores percibido en la aplicación de la política vigente). 
 
   4. Políticas 
 
4.1 Tipos de incidentes y nivel de apoyo 
 
El XYZ-CERT está autorizado para abordar todos los tipos de incidentes de seguridad informática que ocurren, o amenazan con ocurrir, en la Universidad XYZ. 
 
El nivel de apoyo ofrecido por XYZ-CERT variará dependiendo del tipo y la gravedad del incidente o problema, el tipo de componente, el tamaño de la comunidad de usuarios afectada, y los recursos del XYZ -CERT en el momento, aunque en todos los casos se hará alguna respuesta dentro de un día hábil. Los recursos se asignarán de acuerdo con las siguientes prioridades, enumeradas en orden decreciente: 

- Amenazas a la seguridad física de los seres humanos. 
- Ataques de raíz o de nivel de sistema contra cualquier Sistema de Información de Gestión, o cualquier parte de la infraestructura de la espina dorsal de la red. 
- Ataques a nivel de la raíz o del sistema contra cualquier máquina de servicios públicos de gran tamaño, ya sea multiusuario o de propósito dedicado. 
- Compromiso de cuentas de servicios confidenciales restringidas o instalaciones de software, en particular las que se utilizan para aplicaciones MIS que contienen datos confidenciales, o las utilizadas para la administración del sistema. 
- Denegación de los ataques de servicio en cualquiera de los tres artículos anteriores. 
- Cualquier de los anteriores en otros sitios, procedentes de la Universidad XYZ. 
- Ataques a gran escala de cualquier tipo, por ejemplo ataques de sniffing, ataques IRC de "ingeniería social", ataques por cracking de contraseñas. 
- Amenazas, acoso, y otros delitos penales que involucren cuentas de usuarios individuales. 
- Compromiso de cuentas de usuarios individuales en sistemas multiusuarios. 
- Compromiso de los sistemas de escritorio. 
- Falsificación y falsedad, y otras violaciones relacionadas con la seguridad de las reglas y reglamentos locales, por ejemplo, netnews y falsificación de correos electrónicos, uso no autorizado de robots IRC. 


- Denegación de servicio en cuentas de usuarios individuales, por ejemplo, bombardeo por correo. 

Los tipos de incidentes distintos de los mencionados anteriormente se priorizarán en función de su aparente gravedad y magnitud. 

Tenga en cuenta que no se prestará apoyo directo a los usuarios finales; se espera que se pongan en contacto con su administrador del sistema, administrador de red o jefe de departamento para obtener asistencia. El XYZ-CERT apoyará a las últimas personas. 

Si bien el XYZ-CERT entiende que existe gran variación en el nivel de experiencia del administrador del sistema en la Universidad de XYZ, y si bien se esforzará por presentar la información y la asistencia a un nivel adecuado para cada persona, no puede capacitar a los administradores del sistema a la vez, y no puede realizar el mantenimiento del sistema por su cuenta. 
En la mayoría de los casos, el XYZ-CERT proporcionará señales a la información necesaria para aplicar las medidas apropiadas. 

El XYZ-CERT se compromete a mantener a la comunidad de administración del sistema de la Universidad de XYZ informada de posibles vulnerabilidades y, cuando sea posible, informará a esa comunidad de esas vulnerabilidad antes de que sean explotadas activamente. 

4.2 Cooperación, interacción y divulgación de información 

Si bien existen restricciones jurídicas y éticas sobre el flujo de información de XYZ-CERT, muchas de las cuales también están resumidas en la Política de la Universidad de la XYZ sobre las instalaciones de computación, y todas ellas serán respetadas, la Xyz-Cert reconoce su deuda y declara su intención de contribuir al espíritu de cooperación que creó Internet. 
Por lo tanto, si bien se adoptarán las medidas apropiadas para proteger la identidad de los miembros de nuestra circunscripción electoral y los de los sitios cercanos cuando sea necesario, el XYZ-CERT compartirá información libremente cuando esto ayude a otros en la resolución o prevención de incidentes de seguridad. 

En los párrafos siguientes, "partes afectadas" se refiere a los legítimos propietarios, operadores y usuarios de las instalaciones de computación pertinentes. No se refiere a usuarios no autorizados, incluidos usuarios de otra forma autorizados que hacen uso no autorizado de una instalación; tales intrusos pueden no tener expectativas de confidencialidad de la XYZ-CERT. Pueden o no tener derechos legales de confidencialidad; éstos, por supuesto, se respetarán donde existan. 


La información considerada para su publicación se clasificará de la siguiente manera:
- Información de usuario privada es información sobre usuarios particulares o, en algunos casos, aplicaciones particulares, que debe considerarse confidencial por razones legales, contractuales y/o éticas.
La información privada del usuario no se divulgará en forma identificable fuera de XYZ-CERT, salvo lo dispuesto a continuación.  Si la identidad del usuario es disfrazada, entonces la información puede ser liberada libremente (por ejemplo, para mostrar una muestra de archivo.cshrc como modificado por un intruso, o para demostrar un ataque de ingeniería social en particular).
- La información del intruso es similar a la información del usuario privado, pero se refiere a los intrusos.
Si bien la información sobre intrusos, y en particular la información de identificación, no se divulgará al público (a menos que se convierta en un asunto de registro público, por ejemplo porque se han formulado cargos penales), se intercambiará libremente con los administradores del sistema y los CSIRT que rastrean un incidente.
- Información privada del sitio es información técnica sobre sistemas o sitios particulares.
No se publicará sin el permiso del sitio en cuestión, salvo lo dispuesto a continuación.
- La información de vulnerabilidad es información técnica sobre vulnerabilidades o ataques, incluyendo correcciones y soluciones.
La información sobre la vulnerabilidad será liberada libremente, aunque se hará todo lo posible para informar al proveedor pertinente antes de que se informe al público en general.
- Información vergonzosa incluye la declaración de que ha ocurrido un incidente, y información sobre su magnitud o gravedad.  La información embarazosa puede referirse a un sitio o a un usuario o grupo de usuarios en particular.
La información embarazosa no se publicará sin el permiso del sitio o de los usuarios en cuestión, salvo lo dispuesto a continuación.
- La información estadística es una información embarazosa con la información de identificación despojada.
La información estadística se publicará a discreción del Departamento de Servicios de Computación.
- Información de contacto explica cómo llegar a administradores del sistema y CSIRTs.
La información de contacto se divulgará libremente, excepto cuando la persona o entidad de contacto haya solicitado que no sea así, o cuando XYZ-CERT tenga motivos para creer que la difusión de esta información no sería apreciada.
Los posibles destinatarios de la información del XYZ-CERT se clasificarán de la siguiente manera:
- Debido a la naturaleza de sus responsabilidades y las expectativas consecuentes de confidencialidad, los miembros de la dirección de XYZ University tienen derecho a recibir toda la información necesaria para facilitar el manejo de los incidentes de seguridad informática que ocurran en sus jurisdicciones.
- Los miembros de la Oficina de Derechos y Responsabilidades tienen derecho a recibir cualquier información que soliciten en relación con un incidente de seguridad informática o un asunto conexo que se les haya remitido para su resolución.  Lo mismo ocurre con el Departamento de Seguridad de XYZ, cuando se haya solicitado su asistencia en una investigación, o cuando la investigación se haya iniciado a su solicitud.
- Los administradores de sistemas de la Universidad XYZ que son miembros de la CCSA también son, en virtud de sus responsabilidades, confiados con información confidencial.  Sin embargo, a menos que esas personas también sean miembros de XYZ-CERT, se les dará sólo la información confidencial que deben tener para ayudar con una investigación, o para proteger sus propios sistemas.
- Los usuarios de XYZ University tienen derecho a información que se refiere a la seguridad de sus propias cuentas de computadora, incluso si esto significa revelar "información intrusiva", o "informaciones embarazosas" sobre otro usuario.  Por ejemplo, si la cuenta aaaa es pirateada y el intruso ataca la cuenta bbbb, el usuario bbbb tiene derecho a saber que aaaa fue pirateado, y cómo fue el ataque a la cuenta BBBB



