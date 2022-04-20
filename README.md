# github-readme-user-languages

## Usage

To use, add the following line to a markdown file and replace ```USERNAME``` with your github username.
```md
[![Langs](https://github-readme-user-languages.herokuapp.com/?user=<USERNAME>)](https://github.com/umaryusuf11/github-readme-user-languages)
```

<br />

## Deploy Your Own
To deploy to your own heroku server, first install the heroku cli by running,
```bash
npm install heroku -g
```

then login to heroku by running,

```bash
heroku login
```
You can then deploy to a new heroku app like so,
```bash
git clone https://github.com/umaryusuf11/github-readme-user-languages.git

heroku create -a github-readme-user-languages

heroku git:remote -a github-readme-user-languages

git push heroku main
```