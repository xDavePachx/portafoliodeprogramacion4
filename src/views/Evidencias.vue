<template>
  <div class="evidencias">
    <!--DOCTYPE html-->
    <html lang="en">
      <head>
        <meta charset="UTF-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Evidencias</title>
      </head>
      <body>
        <div class="evidencias">
          <h1>Resumen de contenidos</h1>
          <h4>1.0 Introducción al desarrollo con PHP</h4>
          <p>
            PHP (acrónimo recursivo de PHP: Hypertext Preprocessor) es un
            lenguaje de programación de código abiertoEs la expresión con la que
            se conoce al software o programas que se pueden usar libremente.
            Normalmente son gratuitos y se puede acceder a su código fuente. muy
            popular especialmente adecuado para el desarrollo web y que puede
            ser incrustado dentro de código HTML
          </p>
          <p>
            El origen de PHP se remonta a 1995 cuando Rasmus Lerdorf, desarrollo
            el producto PHP/FI, el cual consistía simplemente en un conjunto de
            scripts de Perl a los que llamó 'Personal Home Page Tools'. Ramus
            Lerdorf en vista de la necesidad de dotar de mayor funcionalidad a
            sus scripts, fue escribiendo una mayor implementación utilizando C
            que permitía la comunicación con Bases de Datos y el desarrollo de
            aplicaciones web dinámicas.
          </p>
          <h5>Cómo funciona PHP:</h5>
          <p>
            El usuario escribe una URL una ruta o dirección para poder localizar
            una página web, imagen, servidor etc. en su navegador y éste envía
            un petición al servidor web. Un servidor web es la maquina o
            computador donde se almacena una página web. El servidor lee la
            página PHP (la interpreta). Envía al navegador del usuario un
            documento compilado en formato HTML
          </p>
          <p>
            Lo mejor de usar PHP es que es extremadamente simple para el
            principiante, pero a su vez, ofrece muchas características avanzadas
            para los programadores profesionales.
          </p>
          <h5>¿Qué puede hacer PHP?</h5>
          <p>
            Permite la ejecución de scripts en la parte del servidor. Se
            necesitan tres elementos: El analizador PHP (CGI ó módulo), un
            servidor web y un navegador. Ejecución de scripts desde la línea de
            comandos sin la necesidad de un servidor Web o navegador. Escritura
            de aplicaciones gráficas clientes por medio de una extensión llamada
            PHP- GTK. Puede ser utilizado en cualquiera de los principales
            sistemas operativos del mercado. Linux, Unix, Microsoft Windows, Mac
            OS X, RISC OS y probablemente alguno más. Soporta la mayoría de
            servidores web de hoy en día. Incluyendo Apache, Microsoft Internet
            Information Server, Personal Web Server, y muchos otros
          </p>

          <h5>Ventajas de utilizar PHP</h5>
          <p>
            Lenguaje de programación totalmente libre y de código abierto. Es la
            expresión con la que se conoce al software o programas que se pueden
            usar libremente. Normalmente son gratuitos y se puede acceder a su
            código fuente, es decir, es un lenguaje que se puede usar de forma
            gratuita. Su curva aprendizaje es muy rápida, comparado con otros
            lenguajes de programación. Con PHP se puede tener un fácil acceso a
            diferentes sistemas de gestión de bases de datos. La programación en
            este lenguaje se puede hacer desde cualquier editor de texto. Existe
            una comunidad muy grande alrededor del mundo desarrollando en PHP y
            mejorándolo día a día.
          </p>
          <p>
            El cliente, hace la petición al servidor, éste ejecuta acciones y
            devuelve información al cliente. Es decir, para poder ejecutar php
            se debe disponer de un servidor y una conexión hacia un cliente.
          </p>

          <h5>ejemplo de php</h5>
          <p>el siguiente:</p>
          <img alt="Practicas" width="500" src="@/assets/m27.png" />
          <h4>2.0 CRUD con Laravel Formularios con Laravel</h4>
          <h5>Agregar ruta de recursos</h5>
          <p>
            Agregar rutas para las operaciones CRUD, Laravel proporciona una
            ruta de recursos e se encargará del CRUD, que es una ruta para
            Crear, otra ruta para Recuperar, una ruta separada para Actualizar y
            finalmente una ruta para Eliminar.
          </p>
          <h5>Crear controlador y modelo</h5>
          <p>
            el segundo parámetro para el recurso es AlumnoController, por lo que
            se debe crear el controlador y especificar el modelo de recurso
            agregando --model
          </p>
          <p>
            Método create y store profesores En primer lugar, empecemos metiendo
            código a nuestro método create() del controlador ProfesorController,
            aquí lo único que haremos es retornar al formulario crear del
            directorio resources/views/profesores.
          </p>
          <p>
            En el método store() iniciamos un nuevo objeto de tipo Profesor
            donde le pasaremos como parámetro la variable $request con el método
            All(), con el propósito de recuperar todos los datos enviados desde
            el formulario. En segundo lugar, es llamar al método save() de
            nuestro objeto $profesor para almacenar la información en nuestra
            base de datos. Por último, retornar a nuestra vista el listado de
            profesores donde ya se encontrará el nuevo registro.
          </p>
          <p>
            Método create y store alumnos Realizamos el mismo procedimiento con
            los métodos de create() y store() del controlador AlumnoController.
            En el método create() escribimos el siguiente código:
          </p>
          <img alt="Practicas" width="500" src="@/assets/m28.png" />
          <h4>3.0 Sistema de rutas y controladores</h4>
          <h5>Que es una ruta?</h5>
          <p>
            Una ruta señala la localización exacta de un archivo o directorio
            mediante una cadena de caracteres concreta. Esta puede ser de
            diversas formas dependiendo del sistema operativo y del sistema de
            archivos en cuestión. En líneas generales se compondrá de los
            nombres de los directorios que conforman el camino hasta el archivo
            o directorio a lo largo del árbol de directorios, y finalmente
            estará el nombre del archivo o directorio que se quiere referenciar.
            Estos nombres estarán separados por un carácter delimitador que
            usualmente será la barra inversa (\) en sistemas operativos MS-DOS y
            Windows (de Microsoft) o la barra diagonal (/) en sistemas UNIX o
            Linux.
          </p>
          <h5>Ruta absoluta</h5>
          <p>
            Las rutas absolutas señalan la ubicación de un archivo o directorio
            desde el directorio raíz del sistema de archivos. Por ejemplo, en un
            sistema *nix, /home/dir1/arc1.fil es una ruta absoluta, que señala
            la ubicación del archivo arc1.fil desde la raíz del sistema de
            archivos. En sistemas Windows, una ruta absoluta sería
            C:\usuarios\juan\arc1.fil. Una ruta UNC también es considerada como
            absoluta, por ejemplo \\servidor\carpeta\arc1.fil
          </p>
          <h4>Ruta relativa</h4>
          <p>
            Las rutas relativas señalan la ubicación de un archivo o directorio
            a partir de la posición actual del sistema operativo en el sistema
            de archivos. Por ejemplo, es una ruta relativa dir1/arc1.fil que
            señala al archivo arc1.fil dentro del directorio dir1 en la
            ubicación actual. En sistemas tipo UNIX, la ruta ~/ es una ruta
            relativa que lleva al directorio personal del usuario que ha
            insertado la ruta relativa; por ejemplo, si el usuario Fulano tiene
            una imagen en su directorio personal, esta imagen podría tener dos
            rutas de acceso
          </p>
          <h5>Que son los controladores?</h5>
          <p>
            Un controlador es responsable de controlar la manera en que un
            usuario interactúa con una aplicación MVC. Un controlador contiene
            la lógica de control de flujo para una ASP.NET MVC. Un controlador
            determina qué respuesta se debe devolver a un usuario cuando un
            usuario realiza una solicitud de explorador. Un controlador es
            simplemente una clase (por ejemplo, una Visual Basic o C#). El
            ejemplo ASP.NET aplicación MVC incluye un controlador denominado
            HomeController.vb ubicado en la carpeta Controllers.
          </p>
          <h4>4.0 Validacion de Datos</h4>
          <p>
            Validaciones en Laravel Existen varias formas de validar una
            aplicación para cubrir aspectos de seguridad como SQL Injection,
            ataques XSS o CSRF, algunas de ellas son:
          </p>
          <ol>
            <li>
              Validación de lado del cliente (Javascript y etiquetas HTML).
            </li>
            <li>
              Validación a nivel de base de datos (Migraciones y modelos).
            </li>
            <li>Validación de formularios (Request).</li>
          </ol>
          <h5>Validación del lado del cliente</h5>
          <p>
            Se puede validar que los campos de un formulario sean requeridos al
            agregar el atributo required
          </p>
          <p>
            El atributo required es un atributo booleano. Cuando esta presente,
            este especifica que un campo debe ser rellenado antes de ser enviado
            el contenido del formulario.
          </p>
          <p>
            El atributo required trabaja con los siguientes tipos de input:
            •text • search • url • tel • email • password • data pickers •
            number • checkbox
          </p>
          <h4>El atributo pattern</h4>
          <p>
            Con required solo se necesita de cualquier valor en el elemento
            input para ser válido, pero utilizando el atributo pattern en
            conjunto, se logra que se verifique no solo la presencia de un
            valor, sino que este valor debe contener un formato, una longitud o
            un tipo de dato especifico. Esto último se logra definiendo un
            patrón con expresiones regulares.
          </p>
          <h4>Validación de formularios con plugins JQuery</h4>
          <p>
            El mejor plugin JQuery para validar formularios es formvalidation.
            Sin embargo formvalidation es un plugin que tiene un costo
            dependiendo la licencia que se requiera utilizar. Formvalidation es
            compatible con los formularios de los frameworks css más populares:
            • Bootstrap • Foundation • Pure • Semantic UI • Otros
          </p>

          <h4>5.0 Rest API con Laravel</h4>
          <p>
            REST significa transferencia de estado representacional y es un
            estilo arquitectónico para la comunicación de red entre
            aplicaciones, que se basa en un protocolo sin estado (generalmente
            HTTP) para la interacción.
          </p>
          <h5>Verbos HTTP</h5>
          <p>
            Los verbos HTTP representan acciones En las API RESTful, se utilizan
            los verbos HTTP como acciones y los puntos finales son los recursos
            sobre los que se actúa. Verbos HTTP por su significado semántico:
          </p>
          <ol>
              <li>GET: recuperar recursos</li>
              <li>POST: crear recursos</li>
              <li>PUT: actualizar recursos</li>
              <li>DELETE: eliminar recursos</li>
          </ol>
          <h4>Importancia de los contenidos</h4>
          <p>
            En la materia de Programacion comp 4 los contenidos son de suma
            importancia por el peso que estos tienen tambien que depende de la
            importancia que les demos por que cada quien valora los contenidos
            de diferente forma quiza alguien que quiera ser programador los
            valorara mas que alguien que solo quiere ser administrador de bases
            de datos, asi mismo como alguien que no sepa valorar el sacrificio
            de sus padres no lo valorara igual que alguien con el deseo de
            estudiar que se paga los estudios el mismo.
          </p>
          <br>
          <br>
          <br>
          <br>
          
        </div>
      </body>
    </html>
  </div>
</template>