`heroku auth:whoami`

make sure you are the user you wish to own this

`cd ~/src/github/`

`mkdir joelectronic`

`heroku create joelectronic`

`curl -d '{"name": "joelectronic"}' -H X-GitHub-OTP:123456 -u davejagoda https://api.github.com/user/repos`

`git init`

`git remote add origin git@github.com:davejagoda/joelectronic.git`

`printf '%s\n' '#emacs' '*~' > .gitignore`

`git add .gitignore`

`git commit -m 'add .gitignore'`

`git push -u origin master`
