<a href='https://github.com/lutilipe/GoFinances'>
  <p align="center" style="border-radius:6px">
    <kbd>
    <img src='https://github.com/lutilipe/GoFinances/blob/master/assets/ezgif.com-video-to-gif%20(1).gif'>
    </kbd>
  </p>
</a>

# GoFinances

GoFinances is a project that allow people submit a CSV file containing all transactions they made and view the total amount of it.

## :rocket: Technologies
  - [NodeJs](https://nodejs.org/en/)
  - [React](https://pt-br.reactjs.org/)
  - [Typeorm](https://typeorm.io/#/)
  - [Postgres](https://www.postgresql.org/)

## :information_source: Installation

You'll need to have installed on your computer before starting the project:
[yarn](https://yarnpkg.com/getting-started), 
[NodeJs](https://nodejs.org/en/).

```bash
# Clone the repository
$ git clone https://github.com/lutilipe/Ecoleta---nlw01.git
```
 
### Configuring the DataBase and Server
Create a .env file in the root of server folder and add the following variables:
- DB_USER=<Your database user>
- DB_PASS=<Your database password>
- DB_NAME=<Your database name>
- DB_HOST=<Your host, usually "127.0.0.1">

### :computer: API
```bash
# Go to server directory
$ cd server

# To install the dependencies
$ yarn

# Run the server
$ yarn dev:server
```
### :computer: Web 
 ```bash
# Go to web directory
$ cd web

# To install the dependencies
$ yarn

# Run the web application
$ yarn start
```

## :pencil: License
To view the license, check out [MIT](https://choosealicense.com/licenses/mit/)!
