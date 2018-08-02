## Server
* agregar `robot.txt`. M�s informaci�n [ac�](https://yoast.com/ultimate-guide-robots-txt/#robots-txt-location)
* agregar `.htaccess`.
* agregar `favicon.ico`.
* Pasar el test de �conos a trav�s de los distintos dispositivos _et alia_. URL: https://realfavicongenerator.net/
* Chequear / generar archivo `CNAME` en el servidor (esta es la �ltima instancia, una vez que est� todo listo para ir _online_).

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
* ~~habilitar el plugin `Google Analytics Plugin`.~~
* hay que relacionarlo con una cuenta de Gmail

## OJS Tipograf�a
* [Webfonts Beginner�s guide](https://design.google/library/choosing-web-fonts-beginners-guide/)  
* enfocarse en el `HTML Markup` y en el esquema `xlm`
* [Font Testing Page](https://github.com/impallari/Font-Testing-Page/): tests de tipograf�as en pantalla (kerning, interlineado, etc.)

## OJS Seguridad
* restringir qu� tipo de documento puede subirse (l�ase `.doc`, `.docx`, `.rtf`)
* Restricci�n en qu� tipo de archivos se pueden subir ---> ver [ac�](https://bitbucket.org/imhicihu/open-journal-system-ojs-project/src/6fdb683c746db6179f7cce22e45c74316ab5d737/file_type_restriction.md?at=master&fileviewer=file-view-default).   Soluci�n: habilitar el plugin [`Allowed uploads`](https://github.com/ajnyga/allowedUploads)
* agregar la direcci�n definitiva del sitio en 
     - [UptimeRobot](https://uptimerobot.com/); 
     - [Monitor.Us](http://www.monitis.com/); 
     - [Montastic](http://montastic.com/);  
     - [BasicState](http://basicstate.com/)

## OJS Legales
* ~~Cookies (Pol�tica de cookies). (creaci�n de alerta acerca de las cookies de acuerdo a la legislaci�n de cada pa�s. Ir [aqu�](https://cookieconsent.insites.com/download/) para generar el archivo de javascript~~ --> Hecho. M�s info [aqu�](https://bitbucket.org/imhicihu/open-journal-system-ojs-project/issues/6/workflow-texto-de-las-cookies)
* Pol�tica de privacidad (creaci�n del texto legal de acuerdo a nuestro pa�s y de acuerdo a cada pa�s). 

## OJS Miscel�neas
* Generar mapa del sitio. Primera condici�n: definir la direcci�n de internet definitiva (URL). Despu�s seguir estos [pasos](https://github.com/pkp/ojs/blob/master/docs/README-SITEMAP)
* Generar estas p�ginas est�ticas:
     - 404 (p�gina no encontrada)
* Donde dice: `Contacte con su administrador/a del sitio (imhicihu conicet, mail@imhicihu-conicet.gov.ar) para avisarles de esta nueva versi�n`. **CAMBIAR EL CORREO ELECTRONICO** Esta leyenda se encuentra [ac�](http://ojs-imhicihu.experttel.com.ar/index.php/TemasMedievales/management/settings/context)
* todas las im�genes deben tener su correspondiente descripci�n, uno para semantizar todos los elementos de la p�gina, m�s aun, mejorar la "calificaci�n" de los buscadores, m�s aun, para cumplir con las reglas de "Buenas pr�cticas" (**agregar referencias de ARIA norms**)
* dar soporte a [Citation Style](https://github.com/citation-style-language)
* formato de archivos contemplados: 
```
     LibreOffice 
     [OpenOffice](http://www.openoffice.org)
     [NeoOffice](http://www.neooffice.org)
```
