## Git Tutorial for windows

1. Download and install git bash with all default options
2. Open git Bash or you can open it in windows terminal.
3. Generate ssh key using `ssh-keygen -t ed25519 -C "your_github_email"`
4. Add the ssh key in ssh agent run following commands
  - `eval ``ssh-agent``
  - `ssh-add path_to private key`
5. Generally key is available at the directory in `C\Users\username\.ssh`.
6. add content of public key in github settings -> ssh and gpg keys -> new ssh key
7. update your gitconfig to add necessary requirememts
  - `git config --global user.email "your_email"`
  - `git config --global user.name "your_name"`
  - `git config --global url."git@github.com:".insteadOf https://github.com/`
  - `git config --global url."git://".insteadOf https://`
8. Done you can use git now start with cloning
