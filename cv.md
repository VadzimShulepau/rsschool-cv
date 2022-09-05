### rsschool-cv

# Vadzim Shulepau

*****************************

## _Contacts_

__Phone:__ +375 25 618 22 48

__E-mail:__ shulepau.vadzim@gmail.com

__[Linkedin](https://www.linkedin.com/in/vadzim-shulepau)__

__[GitHub](https://github.com/VadzimShulepau)__

## _About me_

I like to study and want to develop :).

## _Skills_

* HTML, CSS, JavaScript;
* REST API / JSON;
* BEM;
* ReactJS (in progress);
* Node.js  (basic knowledge in progress);
* NestJS (basic knowledge in progress);
* TypeScript (in progress);
* GitHub (basic knowledge);
* Docker (basic knowledge);
* IDE: Visual Studio Code;
* Languages:
  * English (elementary, in progress);
  * Ukrainian (pre-intermediate);
  * Russian (second native language);
  * Belarusian (native language);

## _Code example_

```
import express from 'express';

const app = express()
const port = 3000

app.get('/', (req, res) => {
  res.send('Home Page!');
})

app.get('/users', (req, res) => {
  res.send('See Users!');
})

app.post('/users', (req, res) => {
  res.send('User has created!');
})

app.listen(port, () => {
  console.log(`Example app listening on port ${port}`);
})
```

