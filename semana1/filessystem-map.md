# Mapa del Sistema de Archivos Linux

## Directorios Principales

### /  (Root)

Directorio raíz del sistema.
Todos los demás directorios dependen de este.
Solo root puede escribir durectamente

### /home

Directorios personales de usuarios

'/home/usuario1' , '/home/usuario2'

Cada ususario solo accede a su directorio
/home/juan/Documentos

### /etc

Archivos de configuracion del sistema

**Archivos importantes:**
/etc/passwd
/etc/group
/etc/hosts
/etc/ssh/sshd_config
### /var

Datos variables durante operacion

/var/log/
/var/www/
/var/cache/
/var/spool/

### /bin

Binarios esenciales del sistema.

ls
cp
mv
cat
bash

Para todos los usuarios.


### /usr

 programas y librerías de usuario.

Subdirectorios importantes:

/usr/bin
/usr/lib
/usr/local
/usr/share/

### /opt

software adicional o de terceros.

/opt/google/chrome


### /tmp

Directorio para archivos temporales.

Características:

- Se limpia automáticamente al reiniciar el sistema
- Cualquier usuario puede escribir aquí


### /boot

Contiene archivos necesarios para iniciar el sistema operativo.

Ejemplo:

kernel de Linux
GRUB

### /dev

Contiene archivos que representan dispositivos del sistema.

Ejemplos:

/dev/sda → disco duro
/dev/null → descarta información
/dev/random →generador aleatorio


### /proc

Sistema de archivos virtual que contiene información del sistema y procesos.


/proc/cpuinfo
/proc/meminfo
/proc/1234/
---

### /sys

Contiene información sobre dispositivos y controladores del sistema.