## Máquina: [Mailing]
**Descripción:** Esta máquina es una introducción básica al hacking. El objetivo es obtener la contraseña del usuario "root".

**Pasos para la solución:**

1. Escanear la máquina para encontrar vulnerabilidades.
2. Explotar la vulnerabilidad XSS para obtener acceso como usuario "www-data".
3. Escalar privilegios a "root" utilizando la técnica de escalada de privilegios local (LPE).
4. Obtener la contraseña de "root" del archivo "/etc/shadow".

**Herramientas utilizadas:**

* Nmap
* Burp Suite
* Metasploit