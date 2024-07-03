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

•	Claves públicas (para técnicas como PGP y PEM): Debido a que son accesibles a través de Internet, las claves públicas deben ser     autenticadas antes de su uso. Mientras que PGP se basa en una "Red de Confianza" (donde los usuarios firman las claves de otros usuarios), PEM se basa en una jerarquía (donde las autoridades de certificación firman las claves de los usuarios).

•	Claves secretas (para técnicas como DES y PGP/cifrado convencional): Debido a que deben ser conocidas tanto por el remitente como por el receptor, las claves secretas deben intercambiarse antes de la comunicación a través de un canal seguro.

La comunicación es fundamental para todos los aspectos de la respuesta a incidentes. Un equipo puede apoyar mejor el uso de las técnicas mencionadas anteriormente reuniendo toda la información relevante, de manera consistente. Requisitos específicos (como llamar a un número específico para verificar la autenticidad de las claves) debe quedar claro desde el principio. Las plantillas CSIRT proporcionan un vehículo estandarizado para entregar esta información. 

Está fuera del alcance de este documento abordar los problemas técnicos y problemas administrativos de las comunicaciones seguras. El punto es que los equipos de respuesta deben apoyar y utilizar un método para asegurar la comunicaciones entre ellos y sus electores (u otros equipos de respuesta). Cualquiera que sea el mecanismo, el nivel de protección debe ser aceptable para la comunidad constituyente.

3 Información, Políticas y Procedimientos

En el capítulo 2 se mencionó que las políticas y procedimientos de un equipo de respuesta necesita ser publicado en la comunidad que los constituye. En este capítulo enumeraremos todos los tipos de información que la comunidad necesita recibir de su equipo de respuesta. La forma en que se comunica esta información a una comunidad diferirá de un equipo a otro, al igual que el contenido de la información específica. La intención aquí es describir claramente los diversos tipos de información que una comunidad constituyente espera de su equipo de respuesta.

Para facilitar la comprensión de las cuestiones y temas relevantes para la interacción de los electores con "su" CSIRT, sugerimos que un CSIRT publique toda la información, políticas y procedimientos dirigidos a sus electores como un documento, siguiendo la plantilla proporcionada en el Apéndice D. La estructura de la plantilla organiza los elementos, lo que facilita el suministro de información específica; en el Apéndice E proporcionamos un ejemplo de una plantilla completa para la Universidad XYZ ficticia. Si bien no se hacen recomendaciones sobre lo que un CSIRT debería adoptar para su política o procedimientos, se describen diferentes posibilidades para brindar

algunos ejemplos. Lo más importante es que un CSIRT tenga una política y que quienes interactúan con el CSIRT puedan obtenerla y comprenderla. 

Como siempre, no se pueden cubrir todos los aspectos de cada entorno y/o equipo. Este esquema debe verse como una sugerencia. Cada equipo debe sentirse libre de incluir lo que crea necesario para apoyar a su electorado.

3.1 Obtención del Documento

Los detalles de un CSIRT cambian con el tiempo, por lo que la plantilla completa debe indicar cuándo se modificó por última vez. Además, se debe proporcionar información sobre cómo enterarse de futuras actualizaciones. Sin esto, es inevitable que con el tiempo surjan malentendidos y conceptos erróneos; Los documentos obsoletos pueden hacer más daño que bien.

­­ Fecha de la última actualización		Esto debería ser suficiente para permitir
cualquier persona interesada en evaluar la versión de la plantilla.

­ Lista de distribución	Las listas de correo son un mecanismo conveniente para distribuir información actualizada a una gran cantidad de usuarios. Un equipo puede decidir utilizar su propia o una lista ya existente para notificar a los usuarios cada vez que el documento cambia. La lista normalmente podría incluir grupos con los que el CSIRT tiene interacciones frecuentes.

 Se deben utilizar firmas digitales para los mensajes de actualización enviados por un CSIRT.
­ Ubicación del documento		La ubicación donde se encuentra una versión actual del documento es accesible a través de los servicios de información en línea del equipo. Los integrantes pueden entonces aprender más fácilmente sobre el equipo y comprobar si actualizaciones recientes. Esta versión en línea también deberá ir acompañada de una firma digital


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



