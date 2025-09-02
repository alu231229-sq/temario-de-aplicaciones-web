# temario-de-aplicaciones-web
Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web.
# 1.-Introducción al desarrollo web
!https://share.google/images/LHcQJaQKkc2ZG0PgJ

### Historia y evolución del desarrollo web
El desarrollo web comenzó con Tim Berners-Lee en 1989, cuando creó la World Wide Web, el primer navegador y servidor web, con HTML como lenguaje de marcado básico para las páginas. La evolución incluye la Web 1.0 (estática), la Web 2.0 (interactiva y colaborativa), y la Web 3.0 (inteligencia artificial y personalización). La llegada de CSS trajo el estilo y el diseño, mientras que la Web 3.0 y el auge de las APIs y microservicios permitieron aplicaciones web más complejas, inteligentes y conectadas.

## Tipos de aplicaciones web (estáticas, dinámicas, SPA, PWA)
Los tipos de aplicaciones web incluyen estáticas, de contenido fijo; dinámicas, que se actualizan constantemente con datos de bases de datos; de una sola página (SPA), que cargan una página y actualizan contenido dinámicamente para una experiencia más fluida; aplicaciones web progresivas (PWA), que ofrecen características similares a las aplicaciones móviles e incluso funcionan sin conexión; portales, que ofrecen acceso a diversas secciones como foros o correos; aplicaciones de comercio electrónico, diseñadas para tiendas online con pasarelas de pago; y aplicaciones basadas en gestores de contenidos (CMS), que facilitan la publicación y administración de contenido. 

## 2.Arquitectura de aplicaciones web
### Cliente-Servidor
Un cliente (el navegador del usuario) solicita datos y un servidor los proporciona. Esta estructura se divide en componentes del lado del cliente (front-end, como HTML y JavaScript) y componentes del lado del servidor (back-end), que incluyen la lógica de negocio y el acceso a la base de datos para almacenar y recuperar información. 

### Arquitectura de tres capas (presentación, lógica, datos)
La arquitectura de 3 capas es un patrón de diseño de software que divide una aplicación en tres niveles lógicos: presentación, lógica de negocio y acceso a datos. Esta separación de responsabilidades mejora la escalabilidad, la mantenibilidad y la flexibilidad de la aplicación, al aislar cada capa y permitir su desarrollo y actualización de forma independiente.

### REST y API-first design
El diseño de una API-first aplica un enfoque en el que se diseñan las APIs antes de escribir cualquier código de aplicación, con el objetivo de crear un contrato claro que guíe el desarrollo. Esto fomenta la colaboración, la eficiencia y una mejor experiencia del desarrollador, y es especialmente útil para las APIs REST, un estilo arquitectónico popular para el diseño de APIs web. 

# 3. -Lenguajes y tecnologias fundamentales
HTML, CSS, JavaScript, PHP, MySQL

 HTML: HTML, siglas de HyperText Markup Language (Lenguaje de Marcado de Hipertexto), es el lenguaje fundamental para crear páginas web. Su propósito es estructurar y dar formato al contenido de un sitio web, definiendo elementos como párrafos, imágenes, enlaces, videos y tablas, para que un navegador web pueda mostrarlos correctamente. El HTML utiliza etiquetas y atributos para organizar la información, siendo el esqueleto de cualquier página web.
 
 CSS: CSS, que significa Cascading Style Sheets (Hojas de Estilo en Cascada), es un lenguaje de estilos que se utiliza para describir la presentación y el aspecto visual de documentos escritos en lenguajes de marcado como HTML. Su función principal es separar el contenido de la forma en que se muestra, permitiendo controlar aspectos como el color, la tipografía, los márgenes y la disposición general de una página web

 JavaScript: JavaScript (JS) es un lenguaje de programación versátil usado principalmente para dar interactividad y contenido dinámico a las páginas web, aunque también se utiliza en el lado del servidor con Node.js. A través del navegador, JS permite manipular el contenido de una página (DOM), interactuar con el usuario mediante formularios o crear animaciones. Es fundamental para la web moderna, haciendo que las páginas sean funcionales y enriqueciendo la experiencia del usuario. 

PHP: PHP es un lenguaje de programación de código abierto para el desarrollo web del lado del servidor que permite crear sitios y aplicaciones web dinámicas e interactivas. Se ejecuta en el servidor, genera contenido dinámico, interactúa con bases de datos y puede integrarse fácilmente con HTML, CSS y JavaScript. Es gratuito, ampliamente utilizado y cuenta con una gran comunidad que proporciona soporte y documentación, lo que facilita el desarrollo y la gestión de sitios web complejos. 

MYySQL: MySQL es un sistema de gestión de bases de datos relacionales (RDBMS) de código abierto que se utiliza para almacenar y gestionar datos. Su fiabilidad, rendimiento, escalabilidad y facilidad de uso hacen de MySQL una opción popular para los desarrolladores. De hecho, lo encontrarás en la base de aplicaciones exigentes y de alto tráfico como Facebook, Netflix, Uber, Airbnb, Shopify y Booking.com.



# 4.-Control de versiones
Git y GitHub
Git es un sistema de control de versiones, una herramienta que permite rastrear cambios y gestionar el historial de un proyecto, funcionando de manera local en tu computadora. Por otro lado, GitHub es una plataforma web que utiliza Git para ofrecer un servicio de alojamiento de repositorios en la nube, facilitando la colaboración en equipo, el trabajo remoto y proporcionando herramientas de gestión de proyectos, como la gestión de incidencias y la revisión de código. 

## Flujo de trabajo con ramas (branching, merge, pull requests)
Un flujo de trabajo con ramas en sistemas de control de versiones como Git consiste en crear ramas aisladas para desarrollar nuevas funcionalidades, corregir errores o realizar tareas específicas, separando el trabajo del equipo para mantener la rama principal limpia y estable. Una vez que el trabajo en la rama de desarrollo se completa y se aprueba, se fusiona con la rama principal mediante un proceso conocido como pull request, asegurando la integridad del código. 

Rama (Branch):
Una línea de desarrollo independiente donde se implementan cambios sin afectar la línea principal de código. 

Fusión (Merge):
El proceso de combinar los cambios de una rama en otra, integrando el trabajo. 

Pull Request (Solicitud de Extracción):
Una solicitud formal para incorporar los cambios de una rama a la rama principal, que permite una revisión del código por parte del equipo. 

Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web
# 1.-Diseño e implementación del frontend

## Maquetación/Wireframe/Mockup
Una maquetación (o wireframe) es el esqueleto de un diseño que se enfoca en la estructura y el flujo, mientras que un mockup es una representación visual más detallada y estática que incluye la apariencia estética como colores, tipografía e imágenes. Ambas herramientas son cruciales en el proceso de diseño de interfaces de usuario (UI) y experiencia de usuario (UX), siendo el wireframe una etapa inicial de baja fidelidad y el mockup una versión de mayor fidelidad antes de crear un prototipo interactivo. 

## API
Una API (interfaz de programación de aplicaciones) es un conjunto de reglas y definiciones que permite que dos aplicaciones de software diferentes se comuniquen entre sí, actuando como un puente para el intercambio de datos y servicios. Permite a las aplicaciones enviar y recibir información de manera estandarizada, facilitando la creación de aplicaciones más complejas al no tener que desarrollar todas sus funcionalidades desde cero. Por ejemplo, una aplicación de redes sociales usa APIs para obtener tu "feed" de noticias o publicar nuevos contenidos, y una aplicación del clima usa una API para acceder a los datos meteorológicos de otro servicio. 

# 2.-Diseño e implementación del backend

## Servidor
Un "servidor" puede referirse a una computadora especializada que proporciona recursos y servicios a otros dispositivos (clientes) en una red, o a una persona que realiza una tarea en beneficio de otros, especialmente dentro de una organización. El término se utiliza comúnmente en informática para referirse al equipo que administra y comparte datos, archivos y aplicaciones, y también se emplea en el lenguaje cotidiano para describir a alguien que presta un servicio. 
## Manejo de peticiones y respuestas HTTP
El manejo de peticiones y respuestas HTTP implica que un cliente (como un navegador web) envía una petición a un servidor, que luego responde. Las peticiones incluyen un método HTTP (GET, POST, etc.) y la dirección del recurso, mientras que las respuestas contienen un código de estado (como 200 OK o 404 No encontrado) y el recurso solicitado, si lo hay, o un mensaje de error. Este intercambio es la base del modelo cliente-servidor en la web. 

## Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)

## 3.-Bases de datos
 Modelado de datos y relaciones
ORM (Object Relational Mapping)
CRUD desde el backend

4.-Seguridad básica en aplicaciones web
Validación de formularios
Autenticación y autorización 

Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional
1. -Integración de frontend y backend
Interfaz de usuario Frontend
Manejo de API
Proceso de Solicitud y Respuesta de Backend

2.- Almacenamiento en Servidor
Tipos de servidores 
Servidores y servicios de hosting 
Proveedores de Servicios de Almacenamiento

3.-Optimización y rendimiento
Optimización de recursos (imágenes, scripts)
Despliegue de aplicaciones web
CI/CD básico
Documentación del proyecto
                                                                                                        
