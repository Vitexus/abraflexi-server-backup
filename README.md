# abraflexi-server-backup

![FlexiBee Server logo](abraflex-server-backup.png?raw=true)


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
