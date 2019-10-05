# my-linux-issues-and-solutions
Curated lists of all my issues/problems encountered in linux and their solutions

## 1. npm always asking for permission
### https://stackoverflow.com/questions/33725639/npm-install-g-less-does-not-work

## 2. Solving Docker permission denied while trying to connect to the Docker daemon socket
### https://docs.docker.com/install/linux/linux-postinstall/

## 3. Nuxtjs not hot reloading
### yarn upgrade
### Or install latest webpack and yarn upgrade

## 4. Laravel Passport Key path oauth-public.key does not exist or is not readable on heroku
I found a solution running with heroku cli `heroku ps:exec` then running command `php artisan passport:keys`

## 5. OJET command not found after installation
`export PATH=$PATH:~/.npm-global/bin`
