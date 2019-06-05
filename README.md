# backupYupdateLinux
Pasos y desarrollo de backup y update de linux

## Download and installation:
- Descargar Rufus [ver página](https://rufus.ie/es_ES.html). Se usará soporte de arranque usb.
- [otra opción desde terminal](https://lignux.com/usb-booteable-con-gnu-linux-desde-la-terminal/)

## Backup:
### Opción nube:
[cloud](https://www.txemijendrix.com/index.php?option=com_content&view=article&id=90:linux-script-para-crear-backups-y-almacenarlos-en-la-nube-con-dropbox&catid=15:tutoriales&Itemid=7)

### Opción Uno:
 [Ver página](https://ubunlog.com/backups-desde-la-terminal-con-un-script-en-bash-shell/)
 
 
### Opción Dos:
 [Ver página de ejemplo1](https://www.taringa.net/+linux/como-hacer-un-backup-en-linux-desde-la-terminal_u0tp9)
 
- Pararse en el directorio '$/home/tu usuario/backup' y copy/paste:

'$tar cvpjf backup.tar.bz2 --exclude=/proc --exclude=/lost+found --exclude=/backup.tar.bz2 --exclude=/mnt --exclude=/sys / --exclude=/tmp'

Para después restaurar el backup:
'tar xvpfj backup.tar.bz2 -C /'


