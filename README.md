# cockatoos-react-app  [![Linter](https://github.com/cockatoos/cockatoos-react-app/actions/workflows/linter.yml/badge.svg)](https://github.com/cockatoos/cockatoos-app/actions/workflows/linter.yml)  [![Deploy](https://github.com/cockatoos/cockatoos-react-app/actions/workflows/deploy.yml/badge.svg)](https://github.com/cockatoos/cockatoos-app/actions/workflows/deploy.yml)

---
> ### DEPRECATED: switching to Angular - see https://github.com/cockatoos/cockatoos-app
---

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Development build

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### Via Docker

```bash
$ docker-compose build
$ docker-compose up dev
```

### Local

```bash
$ npm install
$ npm start
```

## Production build

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### Via Docker 

```bash
$ docker-compose run prod
```

### Local

```bash
$ npm run build
```

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!
