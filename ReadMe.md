# Working on the site
1. Check git status
   1. git status
1. Cache your credentials
   1. git config --global credential.helper cache
   1. git config --global credential.helper 'cache --timeout=3600'
1. Do your thing on the files
1. Check if it works
   1. bundle exec jekyll serve
1. Build it
   1. bundle exec jekyll build
1. Add, commit and push
   1. git add .
   1. git commit -m "bla"
   1. git push origin master
   
#Updating web server
1. Update FTP
   1. ssh ssh-w01a7ed0@w01a7ed0.kasserver.com
   1. cd to luisoala.net
   1. do git pull origin master
Done!
