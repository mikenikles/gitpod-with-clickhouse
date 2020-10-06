[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/mikenikles/gitpod-with-clickhouse)

# gitpod-with-clickhouse
A Gitpod template repo with built-in support for [ClickHouse](https://clickhouse.tech/)

## Access ClickHouse
In the terminal, run `clickhouse-client`. It will connect to the local instance of ClickHouse.

The [HTTP interface](https://clickhouse.tech/docs/en/interfaces/http/) is available too:

```bash
curl 'http://localhost:8123/'
```