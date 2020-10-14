<h1 align="center">welcome to express-server-boilerplate with auth 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
  <img alt="Maintenance" src="https://img.shields.io/badge/Maintained-yes-blue.svg" />
  <a href="https://github.com/alok722/express-server-boilerplate-auth.git/blob/main/LICENSE" target="_blank">
    <img alt="Licence" src="https://img.shields.io/badge/License-MIT-blue.svg" />
  </a>
</p>

> an *auth* [express](https://expressjs.com/) server boilerplate to kickstart your backend development.

## 🛠 usage

```sh
$ git clone https://github.com/alok722/express-server-boilerplate-auth.git

$ npm i

$ npm run start:dev
```

## ❓ what is it

It is an express server boilerplate codes to kickstart your backend development with authentication support. It uses passport-jwt and passport as dependency.

<details>
<summary>:zap: API routes</summary>
* /api/auth/register -- add User <br/>
* /api/auth/login -- authenticate user <br/>
* /api/product/read -- read all products * <br/>
* /api/product/read/:_id -- read product by id * <br/>
* /api/product/add -- add product * <br/>
* /api/product/update/:_id -- update product by id * <br/>
* /api/product/delete/:_id -- delete product by id * <br/>

** _product api expects jwt token as Authorization Bearer header, you can get the token by making an api call to login after registration._
</details>

happy backend-deving 😊

## 👤 author

 **Alok raj (alokr417@gmail.com)**

* website: https://alokraj.tech/
* github: [@alok722](https://github.com/alok722)
* linkedin: [@alok722](https://linkedin.com/in/alok722)

## 🚀 future scope

* adding test-cases
* adding documentation

## 🤝 contributing

contributions, issues and feature requests are welcome!<br />feel free to check [issues page](). you can also take a look at the [contributing guide](https://github.com/alok722/express-server-boilerplate-auth/blob/main/CONTRIBUTING.md).

## 🙌 show your support

give a ⭐️ if this project helped you!


***