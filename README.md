# Repos-ArchLinux
Useful Repositories for Arch LInux

***
### Repos
(BlackArch, Paru, Package-query, Yaourt)
Realizar como usuario
```
git clone https://github.com/Manuel-Camacho-Padilla/Repos-ArchLinux.git
cd Repos-ArchLinux

# Instalación de blackarch
cd blackarch 
sudo ./strap.sh

# Instalación de paru
cd .. && cd paru
sudo makepkg -si

# Instalación de package-query (Necesario para Yaourt)
cd .. && cd package-query
sudo makepkg -si

# Instalación de yaourt
cd .. && cd yaourt
sudo makepkg -si

# Instalación de snap
cd .. && cd snapd
sudo makepkg -si

sudo systemctl enable snapd
reboot


