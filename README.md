1. Download and run script
```bash
wget -O - https://raw.githubusercontent.com/roman-tiukh/linux-setup/master/linux_setup.sh | bash
```
2. Enter to the zsh and configure
```bash
zsh
```

3. Replace time format
```bash
sed -i "s/typeset -g POWERLEVEL9K_TIME_FORMAT='.*'/typeset -g POWERLEVEL9K_TIME_FORMAT='%D\{%Y-%m-%d %H:%M\}'/g" ~/.p10k.zsh
```

4. Ensure that zsh works correctly and change default shell to it
```bash
chsh -s $(which zsh)
```
