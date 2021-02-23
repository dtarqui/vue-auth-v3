# vue-coach-project

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

### Changing Async Component
```
const CoachDetail = defineAsyncComponent(() =>
  import('./pages/coaches/CoachDetail.vue')
);
```
```
const CoachDetail = () => import('./pages/coaches/CoachDetail.vue');
```
### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
