# Configuración de Arch Linux / Hyprland

Configuración perzonalizada de Hyprland para laptop (Thinkpad 😊).

## ⚡️ Requerimientos

- git

## Paquetes

- zathura: lector de archivos
- calibre: lector de epub
- node, npm, nvm: javascript
- neovim: editor de texto

## 📦 Instalación

Es buena práctica actualizar el sistema

```bash
sudo pacman -Syu
```

```bash
sudo pacman -S zathura zathura-pdf-mupdf calibre nodejs npm nvm neovim
```

## ⚙️ Configuración

La configuración se encuentra generalmente en el directorio `home/$USER/.config/`.

### NVM

Agregar lo siguiente al archivo `~/.zshrc`

```
source /usr/share/nvm/init-nvm.sh
```
