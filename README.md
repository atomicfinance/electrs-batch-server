## ⚡️ Electrs Batch Server [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

> 🚨 Experimental tool

### Why?

- https://github.com/Blockstream/electrs/pull/20

### Run your own server

```bash
export PORT=5000
export ELECTRS_URL=http://localhost:3000
export CONCURRENCY=10

npm start
```

### Docker

```bash
docker build -t electrs-batch-server .
docker run \
    --env-file .env \
    --network=host \
    --name electrs-batch-server \
    electrs-batch-server
```

### License

[MIT](./LICENSE.md)
