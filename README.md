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

### nvm

Agregar lo siguiente al archivo `~/.zshrc`

```
source /usr/share/nvm/init-nvm.sh
```

### LaTeX

Es necesario instalar LaTeX en el sistema. Para ello hay que seguir los pasos en la web de [TeX Live](https://www.tug.org/texlive/quickinstall.html).

### nvim

La configuración de neovim se encuentra su repositorio particular [nvim](https://github.com/ArlandBarrera/nvim).
