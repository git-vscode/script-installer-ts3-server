## Instalación automática del servidor Linux TeamSpeak 3 en Debian/Ubuntu
### Lo que hace este script:
- Crea un nuevo usuario para ejecutar TeamSpeak 3 Server
- Descarga e instala el servidor
- Crea un servicio systemd
- Inicia el servidor

### Cómo utilizar:
Descargue o copie el script y péguelo en un archivo nuevo
```bash
https://github.com/git-vscode/script-installer-ts3-server/installer_runscript.sh
```
Cambie las variables de usuario si es necesario
```bash
nano installer_runscript.sh
```
Hacer el script ejecutable
```bash
chmod a+x installer_runscript.sh
```
Ejecutar el script
```bash
sudo ./installer_runscript.sh
```
Para iniciar, detener, reiniciar o verificar el estado del uso del servidor ts3
```bash
sudo systemctl {start|stop|restart|status} ts3server 
```
