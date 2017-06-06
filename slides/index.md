# Crafting a reactive application  
using **Vue**, **Vuex**, and, **Feathers**  
[www.involved-it.be](https://www.involved-it.be)



# Choosing the stack


## [Vuejs](https://github.com/vuejs/vue)
- learning curve
- simple
- browser <-> build
- cli
- documentation
Note: ask question about using build process or browser based imports


## [Vue-router](https://github.com/vuejs/vue-router)
- integration
- learning curve


## [Vuex](https://github.com/vuejs/vuex)
- state management
- tailor made for vue
- async & sync
Note: ask for alternatives


## [Feathers](https://github.com/feathersjs/feathers)
- composable api
- authentication
- transport friendly
- persistence friendly
- javascript client


## [Firebase](https://firebase.google.com/)
- bindings via [VueFire](https://github.com/vuejs/vuefire)
Note: cool but not going to do anything with it



# Choosing the tools
- Vscode
    - Vetur plugin
    - eslint plugin
- Docker
    - Mongodb



# Implementing the stack
- technical
- not feature filled
- touch concepts


## Vue
- unpackaged / cdn
- cli (with option router)
```bash
npm i -g vue-cli
vue init webpack app
```


## Vuex
```bash
npm i -S vuex
```


## Feathers-client
```bash
npm i -S feathers-client socket.io-client
```


## Mongo
```bash
docker run --name jsvalley -d -p 27017:27017 mongo
```


## Feathers

```bash
npm i -g feathers-cli
feathers generate app
feathers generate connection
feathers generate authentication
feathers generate service
feathers generate hook
```



# Code it!
