# Setup new env/pc

## Install

* chrome, set default browser
* vscode
* setup ssh key (mac/linux: `ssh-keygen -t rsa`
* go
* homebrew (mac)
* setup git config, github remote ssh setup
* setup ssh config if need multiple github account/ssh keys: https://gist.github.com/jexchan/2351996

```
# .ssh/config

Host github.com-eaglerayp
  HostName github.com
  AddKeysToAgent yes
  UseKeychain yes
  User git
  IdentityFile ~/.ssh/eagle_rsa

Host *
  AddKeysToAgent yes
  UseKeychain yes
  IdentityFile ~/.ssh/id_rsa
  
# ~/#user or org/.gitconfig
[user]
	name = eaglerayp
	email = b98705002@gmail.com

# change hostname to fit ssh config
[url "git@github.com:eaglerayp"]
	insteadOf = git@github.com-eaglerayp:eaglerayp
```


* setup zshrc/bashrc, ohmyzsh & fonts
* slack
* kubectl, k9s
* docker
* protobuf: protoc, protoc-gen-go, protoc-gen-go-grpc, linter: buf
* postman
* ngrok
* mongoDB GUI: studio 3T
* SqlDB GUI: tablePlus/sequelpro (mac), 
