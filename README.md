### .zshrc

```sh
curl https://raw.githubusercontent.com/Bing-su/.dotfiles/main/.zshrc > ~/.zshrc
```

### install [starship](https://starship.rs/)

```sh
curl -sS https://starship.rs/install.sh | sh
```

```sh
echo 'eval "$(starship init bash)"' >> ~/.bashrc
```


### install [zplug](https://github.com/zplug/zplug)

```sh
curl -sL --proto-redir -all,https https://raw.githubusercontent.com/zplug/installer/master/installer.zsh | zsh
```

### change default shell to `zsh`

```sh
sudo chsh -s $(which zsh) [USER_NAME]
```

### conda

[miniconda](https://docs.conda.io/en/latest/miniconda.html)

- [linux amd64](https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh)
- [linux arm64](https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-aarch64.sh)

[mambaforge](https://github.com/conda-forge/miniforge)

- [linux amd64](https://github.com/conda-forge/miniforge/releases/latest/download/Mambaforge-Linux-x86_64.sh)
- [linux arm64](https://github.com/conda-forge/miniforge/releases/latest/download/Mambaforge-Linux-aarch64.sh)

### torch

```
https://download.pytorch.org/whl/torch_stable.html
```

### WSL cuda LD_LIBRARY_PATH

```sh
export LD_LIBRARY_PATH=/usr/lib/wsl/lib
```

### [code-server](https://code.visualstudio.com/docs/remote/vscode-server)

```sh
wget -O- https://aka.ms/install-vscode-server/setup.sh | sh
```

### Long live colab session

```py
%%html
<audio src="https://github.com/Bing-su/.dotfiles/raw/main/silence.flac" controls>
```

<audio src="https://github.com/Bing-su/.dotfiles/raw/main/silence.flac" controls>

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/F1F1L7V2N)
