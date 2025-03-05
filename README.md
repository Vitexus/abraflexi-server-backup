# abraflexi-server-backup

![AbraFlexi Server Backup](abraflex-server-backup.svg?raw=true)

Nastaví Cron aby každý den provedl kompletní zálohu AbraFlexi.

Pro funkci je nutné mít nainstalovaný příkaz /usr/share/flexibee/bin/flexibee-backup  který je součástí [oficiálního balíčku](https://www.flexibee.eu/download/latest/deb/). 

Instalace
---------

Pro Debian či Ubuntu prosím použijte [repozitář](http://vitexsoftware.cz/repos.php):

```shell
sudo apt install lsb-release wget apt-transport-https bzip2


wget -qO- https://repo.vitexsoftware.com/keyring.gpg | sudo tee /etc/apt/trusted.gpg.d/vitexsoftware.gpg
echo "deb [signed-by=/etc/apt/trusted.gpg.d/vitexsoftware.gpg]  https://repo.vitexsoftware.com  $(lsb_release -sc) main" | sudo tee /etc/apt/sources.list.d/vitexsoftware.list
sudo apt update

sudo apt install abraflexi-server-backup
```

![Instalace](dirsel.png?raw=true)
