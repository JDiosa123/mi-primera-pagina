# mi-primera-pagina

¿Qué es HTML y cuál es su función en la web?
R//HTML no es un lenguaje de programación; es un lenguaje de marcado que define la estructura de tu contenido. HTML consiste en una serie de elementos que usarás para encerrar diferentes partes del contenido para que se vean o comporten de una determinada manera. Las etiquetas de encierre pueden hacer de una palabra o una imagen un hipervínculo a otro sitio, se pueden cambiar palabras a cursiva, v.

¿Qué es una etiqueta HTML y menciona las etiquetas más comunes?
R//Una etiqueta HTML (o tag) es un bloque de código fundamental que define la estructura y el contenido de una página web, indicando al navegador cómo interpretar y mostrar elementos como textos, imágenes o enlaces. Generalmente consisten en una etiqueta de apertura <etiqueta>y una de cierre </etiqueta>.
Las más comunes son: la <html>, <head>, <h1>, <ul>, <a>, <p>.

¿Qué es CSS y cómo se utiliza para el diseño web?
R// CSS (Cascading Style Sheets o Hojas de Estilo en Cascada) es el lenguaje estándar utilizado para definir la presentación visual de documentos HTML, controlando colores, fuentes, maquetación y diseño responsivo. Separa el contenido (HTML) de la apariencia, permitiendo actualizar sitios web completos desde un solo archivo y mejorar la experiencia de usuario en dispositivos móviles y escritorio.
Estructura de Reglas: CSS utiliza reglas compuestas por un selector (ej. h1,. clase) y un bloque de declaración que contiene propiedades y valores (ej. color: red;) entre llaves {}.

¿Que es una propiedad en CSS y menciona las propiedades más comunes?
R//Una propiedad CSS es un aspecto o característica específica de un elemento HTML (como color, tamaño o posición) cuyo valor se modifica para definir su apariencia y comportamiento. Forma parte de una declaración (nombre: valor;) que le dice al navegador cómo visualizar un elemento. 
Las propiedades CSS más comunes son:
color: Define el color del texto.
background-color / background: Cambia el color o imagen de fondo.
font-size: Establece el tamaño de la fuente.
margin: Crea espacio alrededor (fuera) de un elemento.
padding: Crea espacio dentro del borde de un elemento.
border: Define el borde alrededor de un elemento.
display: Especifica cómo se visualiza un elemento (block, inline, flex, grid, etc.).

¿Qué es un selector en CSS y cuales tipos existen?
R// Un selector en CSS es un patrón utilizado para identificar y seleccionar elementos HTML específicos en una página web, permitiendo aplicarles reglas de estilo (color, tamaño, diseño). Actúa como una "ruta de navegación" hacia los elementos del documento, siendo la primera parte de una regla CSS. 
Los principales tipos de selectores CSS incluyen: 
Selector Universal (*): Aplica estilos a todos los elementos del documento.
Selector de Tipo/Etiqueta (h1, p, div): Selecciona todos los elementos HTML con ese nombre de etiqueta específico.
Selector de Clase (.nombre-clase): Selecciona elementos que tienen un atributo class específico. Se pueden usar varias veces.
Selector de ID (#nombre-id): Selecciona un único elemento basado en su atributo id único.

¿Qué es JavaScript y cómo añade la interactividad a las páginas web?
R// JavaScript es un lenguaje de programación interpretado de alto nivel, esencial en el desarrollo web junto a HTML y CSS, que permite crear contenido dinámico, controlar multimedia y animar imágenes. A diferencia del contenido estático, JavaScript añade interactividad en el navegador del usuario al responder a eventos (clics, teclado) y actualizar el DOM en tiempo real sin recargar la página. 
¿Cómo añade interactividad a las páginas web?
JavaScript transforma páginas estáticas en aplicaciones interactivas a través de los siguientes mecanismos principales:
Manipulación del DOM (Document Object Model): JavaScript puede modificar, añadir o eliminar elementos HTML y estilos CSS directamente en la página que el usuario está viendo.
Gestión de Eventos: Responde a acciones del usuario como hacer clic, pasar el ratón, presionar teclas o enviar formularios, permitiendo acciones inmediatas.
Actualizaciones en Tiempo Real (AJAX/Fetch): Permite obtener datos de un servidor y actualizar partes de una página (como el feed de una red social) sin necesidad de recargar todo el sitio.
Validación de Formularios: Verifica los datos introducidos por el usuario antes de enviarlos al servidor.
Multimedia y Animaciones: Controla elementos gráficos, carruseles de imágenes y reproductores de video.
¿Cuáles son los tipos de datos primitivos en Javascript?
R// string: Representa datos textuales, por ejemplo: 'Hola'.
number: Representa valores numéricos, tanto enteros como de punto flotante (\(42\), \(3.14\)).
bigint: Utilizado para números enteros extremadamente grandes que superan el límite seguro de number.
boolean: Valor lógico que representa verdadero (true) o falso (false).
undefined: Indica que una variable ha sido declarada pero no se le ha asignado un valor.
null: Representa la ausencia intencional de cualquier valor o un valor vacío. Nota: typeof null devuelve "object", lo cual es un error histórico, pero es un primitivo.
symbol: Identificador único e inmutable, introducido en ES6. 

¿Cómo funcionan las estructuras de control de flujo como if, else, switch y bucles en Javascript?
R// Las estructuras de control de flujo en JavaScript (if, else, switch, for, while) determinan el orden de ejecución de las instrucciones basándose en condiciones booleanas (true/false) o valores específicos. Permiten la toma de decisiones (bifurcaciones) y la repetición de tareas (bucles) de forma dinámica, controlando si un bloque de código se ejecuta, se omite o se repite.

¿Por qué es importante usar nombres significativos para variables y métodos?
R// El uso de nombres significativos para variables y métodos es fundamental para la legibilidad, mantenibilidad y colaboración en el desarrollo de software. Permite que otros programadores (y tú mismo en el futuro) entiendan rápidamente el propósito del código sin necesidad de comentarios adicionales, reduciendo errores y facilitando la depuración. 
Legibilidad y Comprensión: Nombres descriptivos (como userAge en lugar de x) hacen que el código sea intuitivo y expliquen por qué existe una variable o qué hace un método.
Mantenibilidad: Un código bien nombrado es más fácil de actualizar, escalar y refactorizar, lo que ahorra horas de trabajo en proyectos futuros.
Colaboración y Calidad: Mejora la comunicación dentro del equipo, permitiendo una "conversación" fluida sobre el código y reduciendo la curva de aprendizaje para nuevas incorporaciones.
Evita Errores: Al tener claridad sobre el contexto y la función de cada elemento, se minimizan los malentendidos que generan bugs.

¿Qué es una variable de entorno y por qué son importantes para Javascript o la programación en general?
R//Una variable de entorno es un valor dinámico configurado fuera del código fuente de una aplicación —generalmente en el sistema operativo o un archivo.env— que influye en su comportamiento en tiempo de ejecución. Son cruciales en JavaScript (Node.js) y programación general para separar la configuración del código, mejorar la seguridad al ocultar credenciales y adaptar la aplicación a distintos entornos (desarrollo, producción) sin modificar el código. 
¿Por qué son importantes en programación y JavaScript?
Seguridad: Permiten almacenar información sensible como contraseñas de bases de datos, claves API y tokens sin exponerlos en el código fuente (evitando subirlos a repositorios como GitHub).
Gestión de Entornos: Facilitan usar distintas configuraciones según se trabaje en modo local, prueba (staging) o producción (por ejemplo, cambiar la URL de la API de localhost a un dominio real).
Flexibilidad y Portabilidad: La misma aplicación puede funcionar en diferentes máquinas o servidores cambiando solo las variables de entorno, no el código fuente.
Colaboración: Permiten que cada desarrollador tenga su propia configuración local sin afectar la configuración general del proyecto.

¿Qué son las herramientas de desarrollo de Chrome y cómo se accede a ellas?
R//Las herramientas de desarrollo de Chrome (Chrome DevTools) son un conjunto de utilidades integradas directamente en el navegador Google Chrome, diseñadas para que los desarrolladores web puedan inspeccionar, depurar, editar y optimizar el código HTML, CSS y JavaScript de cualquier sitio web en tiempo real. 
Cómo acceder a ellas:
Clic derecho: Haga clic derecho en cualquier elemento de una página web y seleccione "Inspeccionar".
Atajos de teclado:
Windows/Linux: Ctrl + Shift + I (o F12).
Mac: Cmd + Option + I.

¿Qué se puede hacer en el panel "Elements" de las herramientas de desarrollo?
R//El panel "Elements" (Elementos) de las herramientas de desarrollo del navegador es fundamental para inspeccionar y manipular en tiempo real el DOM (HTML) y los estilos (CSS) de una página web. Permite modificar contenido, editar atributos, reordenar nodos, depurar CSS, visualizar el modelo de caja y ajustar diseños instantáneamente. 
Las funcionalidades principales incluyen:
Inspección del DOM: Visualizar la estructura jerárquica del árbol DOM y navegar por ella.
Edición en tiempo real: Modificar el texto, las etiquetas HTML, los atributos o el orden de los elementos directamente en el navegador.
Manipulación de CSS (Pestaña Styles): Ver y cambiar las reglas CSS aplicadas a un elemento, añadir nuevas declaraciones, interactuar con el modelo de caja (Box Model) y desactivar reglas no deseadas.
Depuración de estilos: Identificar estilos anulados, inactivos o inválidos en la pestaña Styles en GeeksforGeeks.
Uso del Panel "Computed": Analizar los estilos finales calculados de un elemento, incluyendo la herencia.
Ocultar o eliminar nodos: Probar la apariencia de la página eliminando o escondiendo elementos temporales.
Inspección de sombras DOM: Visualizar hojas de estilo adoptadas en raíces de sombra (shadow roots).

¿Cómo se utiliza el panel "Console" de las herramientas de desarrollo y para qué es útil?
R//El panel "Console" (Consola) en las herramientas de desarrollo del navegador es un entorno interactivo esencial para desarrolladores. Se utiliza principalmente para visualizar registros, errores y advertencias de JavaScript en tiempo real, así como para ejecutar scripts, probar código JavaScript y depurar la interacción con el DOM, facilitando el diagnóstico rápido de páginas web. 
Para qué es útil la Consola:
Depuración de JavaScript (console.log): Permite imprimir mensajes, valores de variables y objetos para entender el flujo de ejecución y encontrar errores en el código.
Visualización de errores: Muestra automáticamente errores de sintaxis, errores en tiempo de ejecución, advertencias y problemas de red (como errores CORS) que impiden el funcionamiento correcto del sitio.
Interacción directa (REPL): Se puede escribir y ejecutar código JavaScript directamente sobre el contexto de la página actual para probar cambios al instante, manipular elementos DOM o probar funciones.
Inspección de objetos: A través de comandos como console.dir(), se puede visualizar la estructura de objetos y elementos DOM de forma detallada y expandible.

¿Qué información se puede obtener del panel "Network" y por qué es importante?
R//El panel "Network" (Red) de las herramientas de desarrollo del navegador es esencial para analizar el rendimiento y comportamiento de una aplicación web. Permite inspeccionar en tiempo real todas las solicitudes HTTP/HTTPS (imágenes, scripts, CSS, APIs), tiempos de carga, tamaño de archivos, estados de error (códigos 404, 500) y cabeceras.
