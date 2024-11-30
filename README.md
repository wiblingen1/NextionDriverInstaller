## Installing NextionDriver (on Pi-Star)

log in to your Pi-Star with SSH

* use PuTTY
* or go to your dashboard -> configuration -> expert -> SSH access
  (http://pi-star.local/admin/expert/ssh_access.php)

go to the /tmp directory
```
cd /tmp
```

get the software
```
git clone https://github.com/wiblingen1/NextionDriverInstaller.git
```

go !
```
sudo NextionDriverInstaller/install.sh
```


## Checking the installing (on Pi-Star)

log in to your Pi-Star with SSH

* use PuTTY
* or go to your dashboard -> configuration -> expert -> SSH access (http://pi-star.local/admin/expert/ssh_access.php)

go to the /tmp directory
```
cd /tmp
```

get the software
```
git clone https://github.com/wiblingen1/NextionDriverInstaller.git
```
>NOTE: if you get an error that the destionation path exists,
>you already downloaded the software. The just go to the next step.

go !
```
sudo NextionDriverInstaller/check_installation.sh
```
