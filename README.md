
# Listado de herramientas y recursos en hacking etico

![](https://images.alphacoders.com/376/thumbbig-37681.webp)

A lo largo de mis estudios de hacking etico que he realizado en distintos cursos, he utilizado una gran cantidad de herramientas que me han permitido resolver CTF de sitios como tryhackme, por lo que comparto el listado de herramientas como una guia al momento de trabajar en un proyecto de pentesting y recordar la herramienta adecuada dependiendo de la fase de este. 

**Tabla de contenido**

**Índice**
1. [Herramientas utilizadas en curso de hacking octubre 2021](#id1)
2. [Herramientas utilizadas en curso de pentesting web](#id2)
3. [Herramientas utilizadas en curso de hacking febrero 2021](#id3)
4. [Herramientas utilizadas en curso de hacking a celulares mayo 2021](#id4)
5. [Sitios de informacion en ciberseguridad](#id5)
6. [Sitios para practicar hacking](#id6)


<div id='id1' />
## Herramientas utilizadas en curso de hacking octubre 2021

###Fase de reconocimiento
- Informacion whois: dmitry
- Enumerar subdominios: Knowpy
- Busqueda de directorio: dirforcer, dirb
- Busqueda de directorios y archivos: gobuster
- Escaneo CMS: wpscan, Builtwith
- Informacion de dominios: Dnsenum
- Informacion de puertos:nmap
- Enumeracion de dirctorios y archivos: ffuf
- Busqueda en google: Google Hacking
- Obtener informacion de dominio: theharvester
- Identificar WAF: wafw00f
- Obtener informacion de pagina web: Whatweb
- Osint instagram: osi.ig, 
- Osint facebook: yphish
- Obtener contraseñas filtradas de un email:h8mail
- Geolocalizar una ip: cualesmiip
- OSINT: pipl,Truecaller,cqcounter, wolframapalpha, tool.netcraft, OSINTFRAMEWORK, Foca, Maltego, Google hacking

###Enumeracion
- Enumeracion de servicios: Hacer uso de script nmap
- Enumeracion de sistemas: enum4linux

###Analisis de vulnerabilidades
- -Escaneo de servicios: Nmap script vuln
- Escaneo de aplicaciones web: Nikto, ZAP
- Analisis vulnerabilidades en equipos: Nessus, Nmap script, Searchsploit, Exploit-DB, www.Hackersforcharity.org

###Creacion de wordlist
- Utilizar crunch, cupp, listas de github, worlists de kali

###Explotacion
- Explotacion de sistemas: Metasploit
- Phishing: YPhish, Setoolkit, socialphish, zphisher
- Ocultar phishing: Maskphish
- Acortar phishing: bitly
- Enviar phishing por email: copiar plantilla y enviarla
- Obtener acceso a camara: saycheese, camphish
- Obtener patron de desbloqueo: lockphish
- Obtener geolocalizacion de dispositivo: koroni
- Email spoofing:  EMKEI.CZ ANONYMOUSEMAIL.ME
- Beef

###Explotacion de redes
- Conexion remota: netcat
- Ataque con powershell: setoolkit
- Ataque DOS: slowloris y golang-httpflood
- Ataque ARP poissoning:ettercap
- Bloquear internet en la red: evil limiter

###Explotacion con malware
- Crear troyanos: msfvenom
- Ocultar trojanos en un .exe: shellter
- Ocultar trojano en una imagen: winrar
- backdoor para windows: VbRev
- Trojanos con go: Usar go y exportarlos .exe

###Explotacion con evacion de antivirus
- Troyanos dentro de archivo Word: TheFatRat
- Troyanos indetectables: Veil
- Explotacion troyanos en python
- crear troyanos para windows y linux: reverseshell

###Explotacion cracking de contraseñas
- Cracking passwords: john the ripper
- Crear diccionarios: crunch
- Diccionarios de kali: /usr/share/wordlists/
- Ataque de fuerza bruta: Hydra
- Crear diccionarios personalizados: cupp
- Ataque fuerza bruta instragam, fb, gmail: Yphish

###Explotacion desde telefonos android
- Termux

###Explotacion a vulnerabilidad de moviles android
- Usar Android Debug Bridge con ghost

###PostExplotacion
- Elevacion de privilegios https://gtfobins.github.io/

###Esteganografia
- Xiao stenography
- Ocultar archivo dentro de otro: steghide
- Crackear salvocunductos: stegcracker

###Redes alternas
-  Tor, I2P, Freenet, ZeroNet

###Seguridad en sistema informatico
- Firewall
- WAF
- Contraseñas seguras
- Actualizacion de sistema
- Revisar links de acceso
- Antivirus

###Algunos sitios para practicar
- tryhackme
- hackthebox
- vulnhub

<div id='id2' />
## Herramientas utilizadas en curso de pentesting web
###Recoleccion de informacion
- whois 
- wappalyzer
- sitereport.netcraft
- robtex
- viewdns
###Escaneo
Nmap
Scripts para nmap: https://nmap.org/nsedoc/
Nessus
Vulnerabilidades manual: searchsploit, exploitdb, metasploit
Dirb
Gobuster
Nikto
OWASP ZAP
###Explotacion
Inyeccion sql: Sqlmap, Nosqlmap, jmap, Zeus-scanner, themole
Metasploit
Burp suite
<div id='id3' />
## Herramientas utilizadas en curso de hacking febrero 2021
###Fase de reconocimiento
####Herramientas pasivas
- Discover
- Maltego
- Shodan
- HaveIbeenPwned
- Bultwith
- archive.org
- exiftools
- insecam
- ipinfo.io
- P0F
- Wireshark
- Creppy
- FOCA
- Spiderfoot

####Herramientas activas
- Nmap
- Striker

###Enumeracion y analisis de vulnerabilidades
1. Bases de datos de vulnerabilidades:
	- https://www.cvedetails.com/
	- http://cve.mitre.org/
	- https://nvd.nist.gov/
###Vulnerabilidades web
https://owasp.org/
###Analizadores de vulnerabilidades
- Nessus
- Acunetix
- Webhackshl
- WPScan
- Owasp-ZAP
###Explotacion de vulnerabilidades
1. Phishing
	- setoolkit
	- shellphish
	- Email Spoofing
	- dnstwist
2. Troyanos
	- Metasploit(para todos los sistemas operativos, win, linu, mac, android)
	- Shellter(Para windows)
	- Evil-droid(Android)
	- Empire(A traves de documentos de office)
	- beef-xss(Navegador)
3. Ataque MintM
	- Ettercap(ARP poison)
	- Drifnet(Capturar imagenes)
	- Urlsnarf (capturar url)
	- Bettercap(captura https)
4. Exploits
	- Metasploit
	- Armitage
	- https://www.exploit-db.com/(base de datos de exploits)
5. Web
	- sqlmap
###Tecnicas y herramientas post-explotacion
	- Reconocimiento local
		- Sysinfo
		- ps
		- migrate
		- ifconfig
		- download
		- upload
		- comandos unix

	- Ataques
		- sniffing
		- keylogger
		- vnc
		- screenshot
		- webcam
		- microfono
		- killav( desactivar antivirus)
		- getsystem(elevar privilegios)
		- run persistence (tener persistencia)
		- pivoting

###Forense
- Herramienta dawf

###Anonimato
- Utilizar una VPN
- ocultar tu ip real
- deshabilitar geolocalizacion y camaras
- Usar Tor
- Cambiar la MAC
- Deshabilitar cookies
- Usar buscador duckduckgo
<div id='id4' />
## Herramientas utilizadas en curso de hacking a celulares mayo 2021
- Sistema operativo: Kali, Win 10
- Herramientas extra: ngrok
- Explotacion:TheFatRat, EvilDroid, Metasploit, Spynote, 888RAT
- Phishing:Shellpish, FotoSploit, Weeman, Ypish
- Localizacion: Location-hacking
- Camara:CamPish
- Obtener patron de desbloqueo:lockphish
<div id='id5' />
## Sitios de informacion de ciberseguridad
- https://nvd.nist.gov/ncp/repository
- https://www.sei.cmu.edu/about/divisions/cert/index.cfm
- https://isc.sans.edu/
- https://www.acscenter.org/
- https://sectools.org/tag/vuln-scanners/
<div id='id6' />
## Sitios para practicar hacking
-  **Vulnhub**
- Itsecgames
- Dvwa 
-  **Hackthissite **
- Defend the Web 
- Root-me
-  **HackTheBox**
-  **Overthewire **
- Ctftime 
- ** TryHackMe**
- PicoCTF
- hacking-lab
- pwnable.kr
- microcorruption
