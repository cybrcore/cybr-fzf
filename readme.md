<img src="https://raw.githubusercontent.com/cybrcore/cybrcore/refs/heads/main/assets/repo-banners/cybr-fzf-banner.png" height=200px/>

# Showcase
<img src="https://raw.githubusercontent.com/cybrcore/cybrcore/refs/heads/main/assets/showcase/cybr-fzf.png"/>

# Steps
## 0. Before you start
- Make sure [Geist Mono Nerd Font](https://www.nerdfonts.com/font-downloads) is installed, you can do that from terminal with:
```bash
curl -L https://github.com/ryanoasis/nerd-fonts/releases/latest/download/GeistMono.zip -o GeistMono.zip
mkdir -p ~/.local/share/fonts
unzip GeistMono.zip -d ~/.local/share/fonts/GeistMono
fc-cache -fv
```
- Make sure kitty is installed: `sudo pacman -S kitty` and [cybrcore theme](https://github.com/cybrcore/cybr-kitty) is applied
- Make sure fzf is installed: `sudo pacman -S fzf`
- See [Installation Guide](https://github.com/cybrcore/cybrland/blob/main/INSTALL.md) if you`re coming from [cybr-hyprland](https://github.com/cybrcore/cybrland) and haven't set up prerequisites yet
- [fzf Github](https://github.com/junegunn/fzf) | [Arch Wiki](https://wiki.archlinux.org/title/Fzf)

## 1. Open terminal
## 2. Apply the cybrcore theme
Insert:
```sh
set -Ux FZF_DEFAULT_OPTS "\
  --color=fg:#F24848,fg+:#F24848,bg:-1,bg+:#331215 \
  --color=hl:#29BECC,hl+:#F2D230,info:#3061F2,marker:#29BECC \
  --color=prompt:#29BECC,spinner:#3061F2,pointer:#F24848,header:#4D5A80 \
  --color=border:#631F21,label:#ffffff,query:#29BECC"
```