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

### install [miniconda](https://docs.conda.io/en/latest/miniconda.html) (linux)

```sh
curl -o miniconda.sh https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
```
