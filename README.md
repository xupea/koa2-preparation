# koa2-preparation

用Node.js创建自签名的HTTPS服务器
```
https://cnodejs.org/topic/54745ac22804a0997d38b32d
```

```
https://github.com/koajs/koa/tree/v2.x#babel-setup
```

```
npm install koa-bodyparser@next --save
```

```
var koa = require('koa');
var bodyParser = require('koa-bodyparser');
 
var app = koa();
app.use(bodyParser());
 
app.use(function *() {
  // the parsed body will store in this.request.body 
  // if nothing was parsed, body will be an empty object {} 
  this.body = this.request.body;
});
```

```
https://www.npmjs.com/package/koa-log4
```

```
https://github.com/queckezz/koa-views
```
