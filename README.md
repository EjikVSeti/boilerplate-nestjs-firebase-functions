
## Description
Boilerplate for nestjs and firebase-functions

## Installation
```
firebase login
```

add file .firebaserc to the directory where firebase.json and fill:
```
{
  "projects": {
    "default": "PROJECT_NAME_FIREBASE"
  }
}

```


```bash
$ npm install
```

## Running the app

```bash
# local
$ npm run serve

# deploy on firebase
$ npm run deploy

```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```
