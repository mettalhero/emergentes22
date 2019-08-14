
# TECNOLOGIAS EMERGENTES II

## PRACTICA 1

## SISTEMAS DE INFORMACION EMPRESARIAL 

CARRERA: INGENIERIA DE SISTEMAS
APELLIDOS Y NOMBRES: NOEL PITER TAPIA GUTIERREZ
CI:9943951 LP
LUGAR Y FECHA: EL ALTO 13 de agosto de 2019_

>1) Explique que son los sistemas empresariales

Un Sistema de Información Empresarial es un sistema que tiene un impacto muy importante en el funcionamiento de la organización o negocio y cuya falla traería graves consecuencias.

Son aquellos que constituyen el conjunto de recursos de la empresa, que sirven como soporte para el proceso basico de captacion, transformacion y comunicacion de la informacion.

Esta debe ser eficaz y eficiente

>2) Describa cuales son las características más importantes de una aplicación empresarial

En la actualidad practicamente todas las tareas que llevamos acabo atravez de un ordenador las realizamos gracias a la implantacion de un software de *aplicacion*.

Cada una de ellas presentan sus propias caracteristicas:

Las aplicaciones de negocios donde los programas mas utilizados son:

**--Procesadores de palabras** gracias a ellos podemos escribir textos, borrarlos, revisar la ortografia, hacer cambios en la escritura, entre otras muchas cosas.

**--Procesadores de numeros** (hojas de calculo), estas son para crear plantillas en donde poder priorizar formulas, hacer operaciones incluso se puede incluir textos.

**--Bases de datos**, que es una herramienta fundamental para poder tener controlado toda la informacion que hemos guardado en el ordenador y consultarla rapidamente.

**--Graficadores** que sirven para crear tablas, graficas y todo tipo de ilustraciones.

**--Operaciones transaccionales**, cumple con las propiedades ACID.

**--Escalables**, permiten escalabilidad vertical y horizontal.

**--Disponibles**, idealmente prestan servicios de forma continua.

**--Seguras**, no todos los usuarios acceden con la misma funcionalidad.

>3) Investigue y proponga cinco (5) instituciones que requerirían aplicaciones de misión crítica.

Justifique su respuesta

Llamamos aplicaciones de mision critica a aquellas aplicaciones que tienen un impacto muy importante en el funcionamiento de la organizacion o negocio y cuya falla traera efectos terribles.

Un ejemplo evidente es el correo electronico un elemento vital en la comunicacion corporativa cuya caida parece convertir todo en un caos.

Estas aplicaciones no estan instaladas en redes locales sino en la nube

>4) Explique cuáles son las diferencias entre la escalabilidad horizontal y escalabilidad vertical

- **Escalabilidad vertical** el escalar hacia arriba un sistema viene a significar una migracion de todo el sistema a un nuevo hardware que es mas potente y eficaz que el actual, una ves se a configurado el sistema futuro, se realizan una serie de validaciones y copias de seguridad y se pone en funcionamiento.

Esta tiene un aspecto negativo al aumentar la potencia en base a aplicaciones de hardware

- **Escalabilidad horizontal** consiste en potenciar el rendimiento del sistema desde un aspecto de mejora global a diferencia de aumentar la potencia de una unica parte del mismo, este tipo de escalabilidad se basa en la modularidad de su funcionalidad, normalmente en esta se añade equipos para dar mas potencia a la red de trabajo.

Como principal e importante defencto este modelo supone una gran modificacion en el diseño, lo que lleva un gran trabajo de diseño y de implantacion.

Las diferencis entre estas escalabilidades es que la horizontal significa que la escala agregando mas maquinas a su grupo de recursos, mientras que la escala vertical significa que la escala agregando mas potencia (CPU,RAM) a una maquina existente

>5) Que es un servidor Web y que es un servidor de aplicaciones

- **El servidor web** (servidor Http) es un programa informatico que procesa una aplicacion del lado del servidor, realizando conecciones bi-direccionales o uni-direccionales y sincronas o asincronas con el cliente y generando o cediendo una respuesta en cualquier lenguaje o aplicacion de lado del cliente.

- **El servidor de aplicaciones** usualmente se trata de un dispositivo de software que proporciona servicios de aplicacions a la computadoras cliente.

Estas generalmente gestionan la mayor parte (o la totalidad) de las funciones de logica de negociacion y de acceso a los datos de las aplicaciones.

>6) Con un gráfico explique cómo funciona el protocolo HTTP

![](http://2.bp.blogspot.com/_jUCZth_DkjU/TID-jK9rWcI/AAAAAAAAAAQ/3JNIssF_KeQ/s1600/protocolo.png)

>7) Explique los elementos importantes de REQUEST en HTTP

**--Método http** Los métodos más importates de HTTP  son *POST*, *GET*, *PUT*, *DELETE* y *HEAD*.

**--La página para acceder**

**--Formar parámetros**

>8) Explique los elementos importantes de RESPONSE en HTTP

**--un código de estado**, para saber si la solicitud fue exitosa.

**--tipo de contenido**, texto, imagen, html, etc.

**--el contenido**, el html real, imagen, etc

>9) Describa con un gráfico la arquitectura Java EE

![](https://image.slidesharecdn.com/jatunandjavaee-110905104600-phpapp02/95/desarrollo-de-aplicaciones-empresariales-con-java-ee-4-728.jpg?cb=1316098712)

>10) Explique cuáles son los contenedores, componentes y servicios de Java EE

**--Contenedores:** es un entorno de ejecucion que provee al compoente una serie de servicios.

-Contenedores web

-Contenedores de negocio (o de EJBs)

**--Componentes:** es una unidad de software que forma parte de una aplicación.

-Componente cliente: Cliente AWT, Swing, Applet y navegador Web.

-Componenteweb: Servlet, JSP, JSF.

-Componente de negocios: EJB.

**--Servicios:** son los servicios que deben ofrecer los contenedores de Java EE

-De directorio: para la indexacion y búsqueda de componentes y recursos.

-De despliegue: para poder personalizar los componentes y recursos.

-De tranaccionalidad: para poder ejecutar distintas acciones de una misma unidad transaccional.

-De seguridad: para poder autenticar y autorizar a los usuarios de la aplicacion.

-De acceso a datos: para facilitar el acceso a Bases de Datos

-De conectividad: para poder acceder facilmente a distintos EIS.

-De mensajeria: para poder comunicarse con otros componentes, aplicaciones o EIS.

>11) Investigue los métodos más utilizados de las clases HttpServlet, HttpServletRequest y HttpServletResponse, y para cada uno de los métodos muestre un ejemplo.

**--HttpServlet:**

*-init(ServletConfig config)*: Es el método utilizado para crear una nueva instancia del servlet.

*-getServletConfig()*: Retorna la configuración dada para la inicialización del servlet.

*-service(ServletRequest req, ServletResponse res)*: Este método es el que se llama cuando se recibe una petición de un cliente y en su implementación normal para HTTP verifica el tipo de solicitud GET, POST, etc. y la redirige a los métodos respectivos. En general no es necesario reimplementar este método.

*-destroy()*: Este método es llamado por el servidor para indicar que el servlet será destruido.

**--HttpServletRequest:**

*-getHeader(String name)*: Permite obtener el valor de los Headers de HTTP con que fue llamado el servlet.

*-getCookies()*: Retorna un arreglo que contiene todas las _cookies_ que el cliente envía al servlet.

*-getSession()*: Retorna la sesión en la cual se encuentra el cliente.

**-HttpServletResponse:**

*-addCookie(Cookie cookie)*: Para definir nuevas _cookies_ en el cliente.

*-setHeader(String name, String value)*: Para definir un header HTTP a enviar al cliente.

*-sendRedirect(String location)*: Envía un mensaje al cliente para redireccionar la respuesta a la dirección señalada.
