# Testing Server JSON - JSON-Server

This is the mock json server for testing apps with CRUD functionalities without having to really develop the backend and database.

<br/>

Package to Install:

- JSON-server


```
Run

server:'json-server --watch data/db.json --port 5000
```
---

To run backend & frontend concurrently use

- concurrently

```
Run

dev: "concurrently \"npm run server\" \"npm start\""
```
