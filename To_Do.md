## Plantillas (templates)
* generar plantillas de estilos (`.dot en Microsoft Word`) para generar uniformidad en el resultado final, sea en la versi�n pdf, xml y html.

## Tipograf�as
* en el caso de graf�as (lat�n, idiomas orientales, lenguas muertas) deben suministrarse los archivos: formato truetype, open type, etc. 
* asimismo, debe especificarse si es del tipo `right to left`, `up to down` (japanese)

## Server
* agregar `robot.txt`. M�s informaci�n [ac�](https://yoast.com/ultimate-guide-robots-txt/#robots-txt-location). Agregar [este archivo ya creado](https://bitbucket.org/imhicihu/open-journal-system-ojs-project/src/892c4d1e94a9a0d526aa031baac512c7650baffe/robot.txt?at=master).
* agregar `.htaccess`. M�s informaci�n puede encontrarse [aqu�](https://hipertextual.com/archivo/2012/07/archivo-htaccess-apache/)
* agregar `favicon.ico`.
* Pasar el test de �conos a trav�s de los distintos dispositivos _et alia_. URL: https://realfavicongenerator.net/
* ~~Chequear~~ / ~~generar archivo~~ [CNAME](https://bitbucket.org/imhicihu/open-journal-system-ojs-project/src/ebb5ba07eed0078ac583cfd8e25170832d857228/CNAME?at=master&fileviewer=file-view-default) en el servidor (esta es la �ltima instancia, una vez que est� todo listo para ir _online_). --> hecho
* agregar y configurar este [cron job](https://bitbucket.org/snippets/imhicihu/bed47L/ojs-cron-job) 

## OJS
* ~~actualizar a la �ltima versi�n estable de OJS~~ --> hecho
* C�mo saber que versi�n tenemos instalada. Consultar este [snippet](https://bitbucket.org/snippets/imhicihu/6eggK8/verify-with-version-is-installed-on-my)
* Generar _checklist_ que muestre el flujo de trabajo: env�o, correcci�n, publicaci�n de los _papers_. M�s informaci�n [ac�](https://pkp.sfu.ca/wiki/index.php?title=OJS_Workflow:_Stages)

## OJS Backup
* ~~Backup (no hay plugin para la �ltima versi�n, por ende, hay que hacerlo de manera manual, via FTP o Panel de control)~~
* M�s informaci�n recabada, ver [`backup.md`](https://bitbucket.org/imhicihu/open-journal-system-ojs-project/src/eb57ad32778c727442dbf0b3628681697273e36a/Backup.md?at=master&fileviewer=file-view-default)

## OJS Plugins
* ~~discriminar los _plugins_ a instalar~~  ---> Hecho ----> Ver [`plugins.md`](https://bitbucket.org/imhicihu/open-journal-system-ojs-project/src/17e63fd547d1a2a6bdbac5cfe35cbe4508f15013/Plugins.md?at=master&fileviewer=file-view-default)

## OJS Anal�ticas
* habilitar el plugin `Google Analytics Plugin`.
* hay que relacionarlo con una cuenta de Gmail, ergo, hay que poseer una cuenta de Gmail. 
* procedimiento para insertar el c�digo de seguimiento de Google Analytics dentro del sitio y/o complemento (l�ase `plugin`) [ac�](https://support.google.com/analytics/answer/1008080?hl=es)

## OJS Tipograf�a
* [Webfonts Beginner�s guide](https://design.google/library/choosing-web-fonts-beginners-guide/)  
* enfocarse en el `HTML Markup` y en el esquema `xlm`
![glyphs.png](https://bitbucket.org/repo/rpybXp8/images/3991009943-glyphs.png)
* [Font Testing Page](https://github.com/impallari/Font-Testing-Page/): tests de tipograf�as en pantalla (kerning, interlineado, etc.)

## OJS Seguridad
* restringir qu� tipo de documento puede subirse (l�ase `.doc`, `.docx`, `.rtf`)
* asociar una cuenta de Gmail para despu�s habilitar `Recaptcha`. Aqu� est� el [procedimiento](https://www.google.com/recaptcha/admin?hl=es#list) a seguir. **Crucial para evitar spam**
* Restricci�n en qu� tipo de archivos se pueden subir ---> ver [ac�](https://bitbucket.org/imhicihu/open-journal-system-ojs-project/src/6fdb683c746db6179f7cce22e45c74316ab5d737/file_type_restriction.md?at=master&fileviewer=file-view-default).   Soluci�n: habilitar el plugin [`Allowed uploads`](https://github.com/ajnyga/allowedUploads)
* agregar la direcci�n definitiva del sitio en 
     - [UptimeRobot](https://uptimerobot.com/)
     - [Monitor.Us](http://www.monitis.com/)
     - [Montastic](http://montastic.com/)
     - [BasicState](http://basicstate.com/)

## OJS Legales
* ~~Cookies (Pol�tica de cookies). (creaci�n de alerta acerca de las cookies de acuerdo a la legislaci�n de cada pa�s. Ir [aqu�](https://cookieconsent.insites.com/download/) para generar el archivo de javascript~~ --> Hecho. M�s info [aqu�](https://bitbucket.org/imhicihu/open-journal-system-ojs-project/issues/6/workflow-texto-de-las-cookies)
* Pol�tica de privacidad (creaci�n del texto legal de acuerdo a nuestro pa�s y de acuerdo a cada pa�s). Ver [`Privacidad.md`](https://bitbucket.org/imhicihu/open-journal-system-ojs-project/src/d984b71e541d43893651dacec2ca34eb1ea44e41/Privacidad.md?at=master&fileviewer=file-view-default) a modo de ejemplo

## OJS Plantilla
* intimamente relacionado con la generaci�n/conversi�n autom�tica a formatos `XML` & `html`
* crear plantilla (ej: `.dot` para archivos de Microsoft Word�) conteniendo:
     - t�tulo
     - subt�tulo 1
     - subt�tulo 2
     - subt�tulo 3
     - leyenda
     - Bibliograf�a
* el archivo resultante, copiarlo o transferirlo a este repositorio: https://bitbucket.org/imhicihu/template-of-digital-publication/

## OJS Miscel�neas
* Generar mapa del sitio. Primera condici�n: definir la direcci�n de internet definitiva (URL). Despu�s seguir estos [pasos](https://github.com/pkp/ojs/blob/master/docs/README-SITEMAP)
* Generar estas p�ginas est�ticas:
     - site map
     - status pages
     - colophon page
     - cookie policy
     - 404 Page not found (_P�gina no encontrada_)
     - 503 Service Temporarily Unavailable (_Servicio temporariamente no disponible_)
* Donde dice: `Contacte con su administrador/a del sitio (imhicihu conicet, mail@imhicihu-conicet.gov.ar) para avisarles de esta nueva versi�n`. **CAMBIAR EL CORREO ELECTRONICO** Esta leyenda se encuentra [ac�](http://ojs-imhicihu.experttel.com.ar/index.php/TemasMedievales/management/settings/context)
* todas las im�genes deben tener su correspondiente descripci�n, uno para semantizar todos los elementos de la p�gina, m�s aun, mejorar la "calificaci�n" de los buscadores, m�s aun, para cumplir con las reglas de "Buenas pr�cticas" (**agregar referencias de ARIA norms**)
* dar soporte a [Citation Style](https://github.com/citation-style-language)
* formato de archivos contemplados: 
```
     [LibreOffice](https://www.documentfoundation.org/) 
     [OpenOffice](http://www.openoffice.org)
     [NeoOffice](http://www.neooffice.org)
```
* Open Typesetting Stack --> para convertir doc a html & xml. M�s data [ac�](https://pkp.sfu.ca/open-typesetting-stack/)


## Legal ##

* All trademarks are the property of their respective owners.