# Testing Server JSON - JSON-Server


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
run: dev: "concurrently \"npm run server\" \"npm start\""
```
