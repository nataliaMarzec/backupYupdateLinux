# backupYupdateLinux
Pasos y desarrollo de backup y update de linux

## Download and installation:
- Descargar Rufus [ver página](https://rufus.ie/es_ES.html). Se usará soporte de arranque usb.


## Backup:

### Opción Uno:
 [Ver página de ejemplo1](https://www.taringa.net/+linux/como-hacer-un-backup-en-linux-desde-la-terminal_u0tp9)
 
- Pararse en el directorio '$/home/tu usuario/backup' y copy/paste:

' $tar cvpjf backup.tar.bz2 --exclude=/proc --exclude=/lost+found --exclude=/backup.tar.bz2 --exclude=/mnt --exclude=/sys / --exclude=/tmp '

' $# tar xvpfj backup.tar.bz2 -C / '


