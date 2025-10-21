* RAM
	* ejecución de muchos programas cuando no cabe los manda al pagefile.sys
* Pagefile.sys
	* son paginas de memoria ram volcadas al disco duro 
	* contiene contraseñas textos 
	* técnica carving
		* busca y extrae texto legible mediante palabra o patronos
* swapfile.sys
	* área de intercambio de aplicaciones de windows conocido como UWP 
* hiberfile.sys
	* una imagen de memoria ram en estado comprimido para la hibernación del OS 
* hives se encuentra en windows/system32/config/file
	* las colmenas son los registros de windows:
		* system
			* esta la configuracion del sistema tehnemos nombre del equipo interfaz de red zona horia uso de programas
		* sofware
			* software instalados rutas ejecutados extensiones de archivos claves de productos
		* sam
			* cuentas locales y hashes usuarios e historial de logins, hashes de claves
		* security
			* hashe de claves 
		* default
			* perfil de usuarios 
* ntuser.dat
	* solo hay uno por usuario se encuentra dentro de la carpeta c:users
	* contiene documentos del usuario 
	* user asist 
	* rdp 
	* rutas de trabajo 
	* historial de aplicaciones 
	* mru
* usrClast.dat
	* artefacto que tiene informacion que se denomina los shellbags que son las carpetas abiertas vistas de OS y pequeña info
* EVTX
	* son los eventos de logs 
	* lo logs se guardan c:windows/system32/winevt/logs
* prefetch.(pf)
	* c:/windows/prefetch
	* es una cache de archivos binarios ejecutados 
* amcachae.hve
	* catalogo de ejecutables del sistema 
	* contiene rutas y hashes 
	* ç
* SRUM (SRUBD.dat)
	* es un archivo que tiene informacion sobre el uso de conectividad y red 
* jump list/ LNK
	* son los accesos directos 
	* c:/user/mi usuario/appdata/roaming/microsoft/windows/recent
* 
* 
