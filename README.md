# Resumen - APIs

Referencias: https://www.redhat.com/es/topics/api/what-are-application-programming-interfaces

## Introducción
Una API (Application Programming Interface) es un conjunto de definiciones y protocolos que permite diseñar e integrar software. En la práctica, una API actúa como “puente” que permite que distintos servicios o aplicaciones se comuniquen entre sí, independientemente de cómo estén implementadas internamente. Las APIs conectan dos puntos: un cliente y un servidor. La forma más simple de entenderlo es pensar en un contrato, donde ambas partes se ponen de acuerdo en cómo van a comunicarse. Si una parte manda una solicitud con cierta estructura, la otra parte responde siguiendo esas mismas reglas.
Las API surgieron en los comienzos de la informática, mucho antes que la computadora personal. En esa época, una API normalmente se usaba como biblioteca para los sistemas operativos. Casi siempre estaban habilitadas localmente en los sistemas en los que operaban, aunque a veces pasaban mensajes entre las computadoras centrales. Después de casi 30 años, las API se expandieron más allá de los entornos locales. A principios del año 2000, ya eran una tecnología importante para la integración remota de datos.
Las APIs permiten que un cliente envíe una solicitud con una estructura específica, y que un servidor responda según ese contrato. Esa promesa/contrato se describe en documentación: los desarrolladores de ambos lados acuerdan qué tipo de solicitudes se pueden hacer y qué respuestas esperar.  Gracias a esto distintas aplicaciones pueden integrarse sin necesidad de conocer los detalles internos del otro, lo que acelera el desarrollo, reduce costos y simplifica mantenimiento.

## ¿Por qué usar APIs?
- Permiten conectar y reutilizar recursos internos sin exponer detalles internos.
- Permiten modularidad y flexibilidad.
- Permiten escalar rápidamente.
- Facilitan la colaboración entre equipos de negocio y TI.
- Aceleran la inovación.

## Políticas de lanzamiento de las APIs
- Privadas: únicamente para uso interno de la empresa. Tienen más control y seguridad.
- Públicas: permiten que cualquier persona pueda utilizar la API. Permite expandir su alcance, abrir nuevos canales de negocio o impulsar la innovación.
- De partners: se comparten con socios o empresas seleccionadas.

## Tipos de APIs
- SOAP: un protocolo tradicional que usa XML y HTTP para intercambiar mensajes. Permite que aplicaciones en distintos entornos y lenguajes compartan información.
- REST (REpresentational State Transfer): n estilo arquitectónico más flexible que define una serie de restricciones (cliente-servidor, sin estado, caché, interfaz uniforme, etc.). Es actualmente el enfoque más popular para APIs web.
