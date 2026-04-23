# Установк Oh My Zsh

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

# Установка темы kozub.zsh-theme

```bash
curl -o ~/.oh-my-zsh/custom/themes/kozub.zsh-theme https://raw.githubusercontent.com/kozubsa/kozub.zsh-theme/master/kozub.zsh-theme
```

```bash
sed -i '' 's/^ZSH_THEME=.*/ZSH_THEME="kozub"/' ~/.zshrc
```

```bash
source ~/.zshrc
```
