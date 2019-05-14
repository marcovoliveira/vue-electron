# vue/electron Boilerplate

## Project setup
```
npm build
npm start
```

### Compiles and hot-reloads for development
```
npm run dev
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

"scripts": {
    "dev": "NODE_ENV=DEV vue-cli-service serve & sleep 5 && NODE_ENV=DEV electron main.js",
    "serve": "vue-cli-service serve --open",
    "build": "vue-cli-service build",
    "lint": "vue-cli-service lint",
    "start": "electron main.js"
  },
