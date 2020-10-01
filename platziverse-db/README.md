# platziverse-db

## Usage

``` js
cons setupDataBase = require('platziverse-db')


```

setupDatabase(config).then( db => {
    const { Agent, Metric } = db
    const Agent = db.Agent
    const Metric = db.Metric

}).catch(err => console.error(err))

```