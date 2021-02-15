# app

## Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

### Heroku Python

```

$ pip install flask
$ pip install gunicorn

Create a requirements.txt file with all of the modules:

$ pip freeze > requirements.txt

Create Procfile file with

$ web: gunicorn app:app

```