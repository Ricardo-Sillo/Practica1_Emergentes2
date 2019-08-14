# Práctica 1
# Sistemas Empresariales


| Carrera: | INGENIERIA DE SISTEMAS | | 
| --- | :--- | :---|
| Materia: | TECNOLOGIAS EMERGENTES II | 
| Apellidos y nombres: | SILLO RAMOS ROMARIO RICARDO | S 
| C.I: | 13551311 L.P. | 
| Lugar y fecha: | EL ALTO 13 DE AGOSTO

**1. Explique que son los sistemas empresariales**

Un sistema empresarial es un sistema central de la organización, que garantiza que la información se pueda transmitir a través de todas las funciones empresariales, y todos los niveles de gestión, para soportar la operación y administración de una empresa.

**2. Describa cuales son las características más importantes de una aplicación empresarial**

![](http://3.bp.blogspot.com/_GbVgv3VY5Po/S5UsVJBv92I/AAAAAAAAAQA/iVOOwA61Bdg/s1600/caracter%C3%ADsticasSistemaEmpresarial.png)  

**3. Investigue y proponga cinco (5) instituciones que requerirían aplicaciones de misión crítica. Justifique su respuesta**

**4. Explique cuáles son las diferencias entre la escalabilidad horizontal y escalabilidad vertical**

Se entiende por escalabilidad a la capacidad de adaptación y respuesta de un sistema con respecto al rendimiento del mismo a medida que aumenta de forma significativa el número de usuarios del mismo. Aunque parezca un concepto claro, la escalabilidad de un sistema es un aspecto complejo e importante del diseño. La escalabilidad está íntimamente ligada al diseño del sistema. Influye en el rendimiento de forma significativa. Si una aplicación esta bien diseñada, la escalabilidad no constituye un problema. Analizando la escalabilidad, deduzca la implementación y del diseño general del sistema. No es atributo del sistema configurable. La escalabilidad supone un factor crítico en el crecimiento de un sistema. Si un sistema tiene como objetivo crecer en el número de usuarios que sufren su rendimiento actual,
Con un hardware de mayor potencia o
Con una mejor combinación de hardware y software.
Se pueden distinguir dos tipos de escalabilidad, vertical y horizontal:
El escalar verticalmente o escalar hacia arriba, significa el agregar más recursos a un solo nodo en particular dentro de un sistema, tal como el agregar memoria o un disco duro más rápido a una computadora.
La escalabilidad horizontal, significa agregar más nodos a un sistema, tal como agregar una computadora nueva a un programa de aplicación para espejo.

**5. Que es un servidor Web y que es un servidor de aplicaciones**

***Servidor Web. -***

Es un programa que gestiona cualquier servidor realizando conexiones bidireccionales y/o unidireccionales y síncronas o asíncronas con el cliente generando una respuesta en cualquier lenguaje o aplicación en el lado del cliente. El código recibido por el cliente suele ser compilado y ejecutado por un Navegador Web. Para la transmisión de todos estos datos se utiliza algún protocolo. Generalmente se utiliza el protocolo HTTP para estas comunicaciones, perteneciente a la capa de aplicación del Modelo OSI. El término también se emplea para referirse al ordenador que ejecuta el programa.

***Servidor de Aplicaciones. -***

“Básicamente, un servidor de aplicaciones consiste en un contenedor que abarca la lógica de negocio de un sistema, y que provee respuestas a las peticiones de distintos dispositivos que tienen acceso a ella. Son un claro ejemplo del modelo cliente-servidor, cuyo lado cliente ejecuta requerimientos de procesamiento al otro lado, donde el servidor se encarga de procesar y responder.” 
En la actualidad existe una gama muy amplia de tipos de servidores de aplicación, basados en distintas tecnologías. Los más usados son los que funcionan con arquitectura J2EE 7 hechos con tecnología Java, ya que garantizan multiplataformidad. Entre ellos se puede encontrar:

1.	JBoss.
2.	GlassFish.
3.	Oracle application server.
4.	Jetty.
5.	IBM WebSphere.
6.	JOnAS
7.	Geronimo

**6. Con un gráfico explique cómo funciona el protocolo HTTP**
![](http://2.bp.blogspot.com/_jUCZth_DkjU/TID-jK9rWcI/AAAAAAAAAAQ/3JNIssF_KeQ/s1600/protocolo.png)

**7. Explique los elementos importantes de REQUEST en HTTP**
Elementos clave de REQUEST
-	Método HTTP (la acción a realizar)
-	La pagina para acceder (una URL)
-	Parámetros de forma (como argumentos de un método)

**8. Explique los elementos importantes de RESPONSE en HTTP**

Elementos clase de RESPONSE

-	Código de estado (Para saber si la solicitud fue exitosa)
-	Tipo de contenido (texto, imagen HTML, etc)
-	El contenido (el HTML real, la imagen, etc)

**9. Describa con un gráfico la arquitectura Java EE**

![](https://users.dcc.uchile.cl/~jbarrios/J2EE/arq.gif)

**10. Explique cuáles son los contenedores, componentes y servicios de Java EE**

En la siguiente figura se muestra los tipos de contenedores para los diferentes componentes:



![](http://2.bp.blogspot.com/-xtOAc9rZSpc/U9_4CLOvnRI/AAAAAAAAAPQ/vX2vnfJhcWk/s1600/Captura.PNG)

El servidor y los contenedores son:

**Java EE Server:** La porción de tiempo de ejecución de un producto Java EE. provee los contenedores web y de ejb.

**Contenedor EJB:** Maneja la ejecución de los enterprise beans.

**Contenedor Web:** Maneja la ejecución de las paginas web, servlets y algunos componentes ejb para las aplicaciones Java EE.

**Contenedor de aplicación cliente:** Maneja la ejecución de la aplicación cliente no necesita un servidor de aplicaciones.

**Contenedor Applet:** Maneja la ejecución de applets, no necesita servidor de aplicaciones, consiste en un browser y el plugin web de java.

