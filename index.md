### Vryno Public API

---

Vryno public api is websocket/graphql based. 

We have also developed a javascript client which can also provide a traditional request/response api.

---

We support following environments:

stage : ms.vryno.dev

prod : ms.vryno.com

Every request to the vryno api would need a guid/uuid for each request. 

Vryno client(javascript package) abstracts all this information and exposes a `fetch` kind of interface for communicating to the backend. 

Following is demonstration of the public api. Using npm package wscat https://www.npmjs.com/package/wscat

All the sample requests can be found here inside the [requests folder](https://github.com/vryno/api-docs/tree/gh-pages)

#### Basic Echo test

---

[![basic_setup](basic_echo_test.svg)](https://asciinema.org/a/482550)

Ascii recording of above demo can be found here as well https://asciinema.org/a/482550

#### Authentication

---

Signup requires a recaptcha token, so please first signup at https://app.vryno.vom/signup
