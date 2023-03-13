- Как создать ssh-ключ:
ssh-keygen -t ed25519 -C "filippov.ad@phystech.edu"
Далее можно дать название ключу, например, keyname

- Как добавить ключ в аккаунт на GitHub:
Settings -> SSH and GPG keys -> New SSH key
В поле "key" вставить текст из файла keyname.pub

- Как склонировать репозиторий:
git clone git@github.com:username/repository.git
