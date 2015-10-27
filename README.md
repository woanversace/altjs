# Fresh
---

* `npm start`: Will start up the webserver
* `npm test`: Will run test case
* `npm run dist`: Create the packed version

* `yo react-webpack-alt:action my/namespaced/action/name`: Generate new Action
* `yo react-webpack-alt:store my/namespaced/stores/name`: Generate new store
* `yo react-webpack-alt:all my/namespaced/functions/name`: Generate a new store, as well as a dedicated aciton for it

* `yo react-webpack-alt:source my/namespaced/functions/name`: Generate a new empty [source](http://alt.js.org/docs/async/). You will then able to include it in your stores via
```js
  import NameSource from 'sources/my/namespaces/sources/nameSource';
  NameSource.remoteAction();
```

> This based on [generator-react-webpack-alt](https://github.com/weblogixx/generator-react-webpack-alt)
> License MIT License

