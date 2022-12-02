<h1>My nvim config</h1>

<h2>Install Nerd Font:</h2>
<h3>https://www.nerdfonts.com/font-downloads</h3>

<h2>Install Zsh:</h2>

```bash
sudo apt install zsh
```

<h2>Install Oh-my-zsh:</h2>

```bash
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

> <h2>Apply the theme editing the .zshrc file:</h2>

```bash
ZSH_THEME="agnoster"
```

<h2>Install NodeJS:</h2>

```bash
sudo apt install nodejs
```

<h2>Install Python3:</h2>

```bash
sudo apt install python3
```

<h2>Install Pip:</h2>

```bash
sudo apt install python3-pip
```

<h2>Install Pynvim:</h2>
 
```bash
pip install pynvim
```

<h2>Install Ripgrep:</h2>

```bash
sudo apt-get install ripgrep
```

<h2>Install fd:</h2>
 
```bash
sudo apt install fd-find
```

<h2>Install Vim-plug:</h2>

```bash
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```

<h2>Install CLang-15:</h2>

```bash
sudo apt-get install clang-15
```

<h2>Replace clang-15 with clang:</h2>

```bash
sudo update-alternatives --install /usr/bin/clang clang /usr/bin/clang-15 100
```

<h2>Install CLangd-15:</h2>

```bash
sudo apt-get install clangd-15
```

<h2>Replace clangd-15 with clangd:</h2>

```bash
sudo update-alternatives --install /usr/bin/clangd clangd /usr/bin/clangd-15 100
```

<h2>Install CLang-Format-15:</h2>

```bash
sudo apt-get install clang-format-15
```

<h2>Replace clang-format-15 with clang-format:</h2>

```bash
sudo update-alternatives --install /usr/bin/clang-format clang-format /usr/bin/clang-format-15 100
```

> <h2>Create a txt file named compile_flags inside the root folder of the project and flag the c++20 version:</h2>

```bash
-std=c++20
```

> <h2>Create a folder inside .config named nvim, put init.vim and coc-settings.json inside that folder.</h2>

> <h2>Credits (Wallpapers):</h2>
<h3>https://github.com/linuxdotexe/nordic-wallpapers/tree/master/wallpapers</h3>
