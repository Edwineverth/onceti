#OnceTI-DB
##Usage

```js
const setupDatabase = require("onceti-db");

setupDataBase(config)
  .then((db) => {
    const { Agent, Metric } = db;
  })
  .catch((err) => console.error(err));
```
