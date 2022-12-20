# ethereum-lite-explorer-backend

## Description
This project is an open-source block explorer on EVM chain. If you follow this repository, you can run explorer in localhost. This repository provides backend code. This server uses a RESTful API to access the database and fetch data.

## Getting Started

### Installing
- If you have not built a crawling server, please follow the link below first.
  - <https://github.com/Generation-Foundation/ethereum-lite-explorer-crawling>

- Git clone this repo
```bash
git clone https://github.com/Generation-Foundation/Explorer-Backend-test.git
```
- Create ``.env`` to update MySQL database settings.
```env
DB_HOST="host"
DB_USER="user"
DB_PASSWORD="password"
DB_DATABASE="explorer_db"
```
- Run it local with the following command
```bash
npm install --save
node server.js
```
- Go to the following link to build your frontend server
  - <https://github.com/Generation-Foundation/Explorer-Frontend-test>

### Api Reference
This is GENERATION's rpc url api documentation. ([API Docs](https://documenter.getpostman.com/view/22780180/2s8YszMpBe#intro))
</br>Use your blockchain rpc url. Access the endpoint and check the data.

## Contributors
Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<table>
  <tr>
    <td align="center"><a href="https://github.com/Booyoun-Kim"><img src="https://avatars.githubusercontent.com/u/34641838?v=4" width="100px;" alt=""/><br /><sub><b>Ben</b></sub></a><br /><a>🧑‍🏫</a> <a>🤔</a> <a>📆</a> <a>💬</a></td>
    <td align="center"><a href="https://github.com/Jaewoneeee"><img src="https://avatars.githubusercontent.com/u/93761302?v=4" width="100px;" alt=""/><br /><sub><b>Danny</b></sub></a><br /><a>💻</a> <a>🤔</a> <a>🔣</a> <a>📖</a> <a>🚧</a></td> 
  </tr>
</table>

## Developed
Developing by [Generation Foundation](https://github.com/Generation-Foundation)

## Our Services and Community
- [Official Website](https://gen.foundation/)
- [Generation Explorer](https://dev-explorer.gen.foundation/)
