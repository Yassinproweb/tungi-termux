# Install script for termux zsh shell

```bash
 git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting && git clone https://github.com/zsh-users/zsh-autosuggestions.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions && git clone --depth 1 -- https://github.com/marlonrichert/zsh-autocomplete.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autocomplete
```

## Script for powerlevel10k
```bash
git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
```

## Increasing git resilience
```bash
 git config --global http.postBuffer 524288000
```


## Setting up ssh keys for git and github
```bash
# generating key using ed25519
ssh-keygen -t ed25519 -C "yassinkatungi67@gmail.com" #email

# running ssh agent
eval "$(ssh-agent -s)"

# adding the private key
ssh-add ~/.ssh/id_ed25519

# viewing the public key
cat ~/.ssh/id_ed25519.pub

#TODO: copy the result and add it in the github ssh key input
#NOTE: the public key is the one that should be added i.e id_ed25519.pub file
```
```
```

## Setting remote git to github in terminal ssh
```bash
git remote set-url git@github.com:{username}/{name-of-repo}.git
```
```
```
