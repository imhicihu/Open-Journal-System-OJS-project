### Checklist
- [ ] Servidor
	- [ ] Plantillas
		- [ ] Subirlas y habilitarlas
		- [ ] Habilitar Custom page plugin
		- [ ] Crear estas páginas estáticas:
			- [ ] 404.html (Page not found)
			- [ ] Colophon page
			- [ ] 503.html (service unavailable)
			- [x] [Status online](https://imhicihu.statuspage.io/) (estado del arte del servidor)
			- [ ] Política de cookies (texto)
			- [ ] Política de privacidad (texto)
			- [ ] Mapa del sitio
	- [ ] Iconos
		- [ ] favicon.ico
		- [ ] verificar con: https://realfavicongenerator.net/
	- [ ] Backup
		- [x] CRON job
			- [x] Ver: https://bitbucket.org/snippets/imhicihu/bed47L/ojs-cron-job
		- [x] Habilitar Backup plugin
			- [x] Ver: https://pkp.sfu.ca/ojs/doxygen/master/html/group__plugins__generic__backup.html
		- [x] Scheduled tasks
			- [x] Ver: https://github.com/pkp/ojs/tree/master/docs#scheduled-tasks
		- [ ] mySQL database
			- [ ] Ver: http://www.mysqltutorial.org/how-to-backup-database-using-mysqldump.aspx
	- [ ] Tipografías
		- [ ] webfont: hosted by Google
		- [ ] left to right / right to left (take in count for screen reader and font, kerning and spacing between parties)
		- [ ] western / eastern idioms
		- [ ] Google Noto: multi-idiom, ligatures, kerning, no bandwidth consume
		- [ ] Font testing page: https://github.com/impallari/Font-Testing-Page/
	- [-] Seguridad
		- [ ] https & ssl certificates
		- [+] .hjtaccess
		- [ ] Spam & bots
			- [ ] Relacionar cuenta de Gmail con Google Recaptcha. Ver: https://www.google.com/recaptcha/intro/v3beta.html
		- [x] robots.txt
			- [x] Ver: https://bitbucket.org/imhicihu/open-journal-system-ojs-project/src/765edcf5ce11273f580fc422216a9e8adb3cc760/robot.txt?at=master&fileviewer=file-view-default
		- [x] CNAME
			- [x] Ver: https://bitbucket.org/imhicihu/open-journal-system-ojs-project/src/765edcf5ce11273f580fc422216a9e8adb3cc760/CNAME?at=master
		- [x] config.inc.php
			- [x] Ver: https://bitbucket.org/imhicihu/open-journal-system-ojs-project/src/765edcf5ce11273f580fc422216a9e8adb3cc760/config.inc.php/config.inc.md?at=master&fileviewer=file-view-default
		- [x] Habilitar File Type restriction plugin
			- [x] Ver https://bitbucket.org/imhicihu/open-journal-system-ojs-project/src/765edcf5ce11273f580fc422216a9e8adb3cc760/file_type_restriction.md?at=master&fileviewer=file-view-default
		- [ ] Monitor online
			- [ ] Agregar URL a estos sitios:
				- [ ] Monitor us > https://www.monitis.com/
				- [ ] UptimeRobot > https://uptimerobot.com/
				- [ ] Montastic > https://montastic.com/
				- [ ] BasicState > http://basicstate.com/
	- [x] Plugins
		- [x] iThenticate: habilitado
		- [x] QuickSubmit: habilitado
		- [x] Allowed uploads: habilitado
		- [x] Custom header: habilitado
		- [x] Backup: habilitado
		- [x] Google Analytics: habilitado
		- [x] DOI: habilitado
	- [x] Analíticas
		- [x] Habilitar Google Analytics plugin
		- [ ] abrir cuenta de Gmail. Relacionar dicha cuenta con Google Analytics y el servidor conteniendo el OJS
	- [ ] Legales
		- [ ] Política de cookies
			- [ ] Ver: https://bitbucket.org/imhicihu/open-journal-system-ojs-project/issues/6/workflow-texto-de-las-cookies
		- [ ] Política de privacidad
			- [ ] Ver: https://bitbucket.org/imhicihu/open-journal-system-ojs-project/src/d984b71e541d43893651dacec2ca34eb1ea44e41/Privacidad.md?at=master&fileviewer=file-view-default
