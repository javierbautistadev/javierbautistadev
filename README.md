<h1 align="center">¡Hola! Soy Javier Bautista 👋</h1>
<h3 align="center">🛡️ Ciberseguridad · Pentesting · Bastionado de sistemas</h3>

<p align="center">
  <a href="https://javierbautistadev.es"><img src="https://img.shields.io/badge/Web-javierbautistadev.es-0d1117?style=flat-square&logo=googlechrome&logoColor=white" alt="Web" /></a>
  <img src="https://img.shields.io/badge/📍-Algeciras,%20Cádiz-0d1117?style=flat-square" alt="Ubicación" />
</p>

---

### 🙋‍♂️ Sobre mí

Me estoy formando para dedicarme a la **ciberseguridad ofensiva y defensiva**: pentesting, análisis de vulnerabilidades y bastionado de sistemas.

Antes de llegar aquí fui desarrollador, y esa base es mi punto fuerte: entiendo cómo se construyen las aplicaciones y los servidores, así que sé por dónde suelen romperse.

- 🛡️ Cursando el **Máster de FP en Ciberseguridad en Entornos de las Tecnologías de la Información** (720 h)
- 🏠 Construyendo y securizando mi propio **homelab**, que uso como laboratorio de ataque y defensa
- 🧪 Resolviendo máquinas en **DockerLabs** y siguiendo rutas en **TryHackMe**
- 🎓 **Técnico Superior en Desarrollo de Aplicaciones Multiplataforma** (2026)

---

### 🎯 Áreas en las que me formo

| Ofensiva 🔴 | Defensiva 🔵 |
| --- | --- |
| Hacking ético y pruebas de intrusión | Bastionado de redes y sistemas |
| Análisis de vulnerabilidades | Detección y respuesta ante incidentes |
| Explotación web (OWASP Top 10) | Análisis forense informático |
| OSINT y reconocimiento | Puesta en producción segura |
| Auditoría de redes | Normativa: RGPD, ISO 27001 y ENS |

---

### 🏠 Homelab: laboratorio de seguridad

Servidor casero sobre un Lenovo ThinkCentre M93p con **Ubuntu Server 26.04 LTS**, diseñado y bastionado desde cero.

| Área | Qué he aplicado |
| --- | --- |
| **Acceso** | SSH solo con clave Ed25519 y autenticación por contraseña desactivada |
| **Firewall** | UFW con política *deny incoming* y reglas restringidas por origen |
| **Protección contra fuerza bruta** | fail2ban sobre SSH |
| **Acceso remoto** | OpenVPN: los servicios solo son accesibles desde la VPN, sin exponerlos a Internet |
| **DNS** | Pi-hole como DNS de la red, con bloqueo de publicidad y rastreadores |
| **Servicios** | Docker + Portainer, Nextcloud + MariaDB aislados en contenedores |

**🗺️ Hoja de ruta**

- [ ] Auditoría con **Lynis**: puntuación antes y después del bastionado
- [ ] Escaneo con **Nmap** desde Kali antes y después del firewall
- [ ] 2FA (TOTP) en Nextcloud y copias de seguridad con prueba de restauración
- [ ] fail2ban sobre OpenVPN y **CrowdSec**
- [ ] **OWASP Juice Shop** en una red aislada, atacado desde Kali
- [ ] **Wazuh** como SIEM para detección y monitorización

---

### 🔐 Prácticas y laboratorios

**🐳 DockerLabs** — [writeups completos aquí](https://github.com/javierbautistadev/Maquinas-realizadas-Ciberseguridad)

| Máquina | Técnicas trabajadas |
| --- | --- |
| Acme | Fuga de credenciales en el banner SSH, enumeración de WordPress y manipulación directa de la base de datos para tomar el panel |
| FirstHacking | Explotación del backdoor de vsftpd 2.3.4 (CVE-2011-2523) hasta conseguir shell root |
| Analyst | Análisis forense de una captura `.pcap` con Wireshark y bypass de un filtro de subida de archivos (`.jpg.php`) |
| Injection | Inyección SQL automatizada con sqlmap y acceso por reutilización de credenciales *(escalada de privilegios en curso)* |

**🌐 TryHackMe:** siguiendo la ruta de fundamentos.

**🔎 Reconocimiento y OSINT:** Nmap y netdiscover para la auditoría de redes. theHarvester, Sherlock, exiftool, Maltego y SpiderFoot para OSINT.

---

### 🧰 Herramientas

**Seguridad**

<p>
  <img src="https://img.shields.io/badge/Kali%20Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white" alt="Kali Linux" />
  <img src="https://img.shields.io/badge/Nmap-0E83CD?style=for-the-badge&logo=nmap&logoColor=white" alt="Nmap" />
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" alt="Wireshark" />
  <img src="https://img.shields.io/badge/sqlmap-222222?style=for-the-badge&logo=databricks&logoColor=white" alt="sqlmap" />
  <img src="https://img.shields.io/badge/Maltego-1A1A2E?style=for-the-badge&logoColor=white" alt="Maltego" />
  <img src="https://img.shields.io/badge/OpenVPN-EA7E20?style=for-the-badge&logo=openvpn&logoColor=white" alt="OpenVPN" />
  <img src="https://img.shields.io/badge/fail2ban-B22222?style=for-the-badge&logoColor=white" alt="fail2ban" />
  <img src="https://img.shields.io/badge/Pi--hole-96060C?style=for-the-badge&logo=pihole&logoColor=white" alt="Pi-hole" />
  <img src="https://img.shields.io/badge/TryHackMe-212C42?style=for-the-badge&logo=tryhackme&logoColor=white" alt="TryHackMe" />
</p>

**Sistemas e infraestructura**

<p>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Ubuntu%20Server-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" alt="Ubuntu Server" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white" alt="Proxmox" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
</p>

**Programación** *(la base que me ayuda a entender y auditar código)*

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white" alt="MariaDB" />
</p>

---

### 💻 Background en desarrollo

<details>
<summary>Proyectos reales que he desarrollado para clientes y empresas (clic para ver)</summary>

<br>

| Proyecto | Descripción | Stack |
| --- | --- | --- |
| [**Medcontrol**](https://github.com/javierbautistadev/medcontrol) | Gestión operativa para una empresa logística, con usuarios, roles y permisos | Laravel · PostgreSQL · Docker |
| **Sistema de fichaje** | Control de acceso y asistencia con reconocimiento facial en local | Rust · Tauri · SQLite |
| **Reservas · Barbería Guille Dávila** | Sistema de citas con panel de administración | Web · Base de datos |
| **Landing · Estudio Virginia Calderón** | Web para un estudio de tatuajes | Astro · HTML · CSS · JS |
| [**FichApp**](https://github.com/javierbautistadev/FichApp) | App móvil para registrar turnos de trabajo | Flutter · Dart |
| **Generador de contraseñas** | Script para generar contraseñas seguras | Python |

</details>

---

### 📊 Estadísticas

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=javierbautistadev&show_icons=true&theme=radical&hide_border=true" alt="Estadísticas de GitHub" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=javierbautistadev&layout=compact&theme=radical&hide_border=true" alt="Lenguajes más usados" />
</p>

---

### 🤝 Contacto

<p>
  <a href="https://javierbautistadev.es"><img src="https://img.shields.io/badge/Portfolio-javierbautistadev.es-0d1117?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
</p>

<p align="center"><i>"Para defender un sistema, primero hay que entender cómo se ataca."</i></p>
