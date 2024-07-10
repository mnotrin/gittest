# How to set up GIT
## Create an ssh key and add it to your github to authenticate yourself from the terminal
```sh
ssh-keygen -t ed25519`
# accept everything, empty password
cat ~/.ssh/ed25519.pub
```
Copy this key and add it to your ssh keys on github.

## Clone a repository
```sh
git clone git@github.com:mnotrin/gittest.git
cd gittest
```
