## Diseño Dracula+

Compiar el contenido settings_windowsterminal.json en settings.json de windows terminal

tener en cuenta los siguiente:
*  "defaultProfile": ID de wls 
*  "startingDirectory" : "//wsl$/Ubuntu/home/<user>" (cambiar la ruta por defecto wls)

## customize shell

instalar Nerd Font https://www.nerdfonts.com/ -->download--> DroidSansMono Nerd Font, instalar.

## instalar zsh

sudo apt update

sudo apt install zsh -y

sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

## instalar powerlevel10k zsh theme

git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/themes/powerlevel10k

* Seguir el tipo de diseño.

* Para activar el tema, necesita editar su archivo "~ / .zshrc" en su carpeta personal y reemplazar ZSH_THEME = "robbyrussel" con ZSH_THEME = "powerlevel10k / powerlevel10k" . Después del cambio, debe cerrar y reiniciar su terminal.


## Nota
Para que renderice los iconos en visual code ir a settings-->Text Editor-->settings.json en "terminal.integrated.fontFamily": "DroidSansMono Nerd Font", (agrega la fuente, reinciar visual code)